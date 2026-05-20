# LEGO Canada Expert Chatbot with n8n + Claude

This project shows how to build a chatbot in n8n that answers questions as an expert on the LEGO Canada website (`lego.com/en-ca`). The workflow uses:

- n8n Webhook to receive user questions
- n8n HTTP Request nodes to retrieve LEGO site content
- Claude LLM (Anthropic API) to answer using the retrieved website data

## Files

- `lego-chatbot-n8n.json` — n8n workflow export
- `lego-chatbot-n8n.md` — this setup guide

## Setup Steps

1. Install n8n if you do not already have it. For example:
   ```bash
   npm install -g n8n
   n8n start
   ```

2. Create an environment variable for your Claude / Anthropic API key:
   ```bash
   export ANTHROPIC_API_KEY="your_api_key"
   ```

3. Import `lego-chatbot-n8n.json` into n8n:
   - Open n8n
   - Click **Import**
   - Paste the JSON from `lego-chatbot-n8n.json`
   - Save the workflow

4. Activate the workflow and note the webhook URL.

5. Send a POST request with JSON to the webhook endpoint:
   ```bash
   curl -X POST "http://localhost:5678/webhook/lego-chatbot" \
     -H "Content-Type: application/json" \
     -d '{"question":"Does LEGO ship to Canada?"}'
   ```

## How it works

1. User message enters via the Webhook node.
2. The workflow fetches LEGO Canada search content for the query.
3. A prompt is built that asks Claude to answer as a LEGO Canada expert using the page content.
4. Claude returns a site-grounded response.

## Notes

- The workflow uses HTML search page content from `lego.com/en-ca/search` as the source.
- If LEGO changes its site or search structure, adjust the HTTP Request and prompt logic.
- Always validate the chatbot response before using it in production.
