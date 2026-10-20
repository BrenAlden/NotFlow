# AI Document Extractor to Notion

An n8n workflow that accepts a question and one or more documents, extracts
their text, asks Google Gemini to summarize or answer in Indonesian, and saves
the structured result to a Notion page.

## Supported files

- PDF
- TXT
- Markdown (`.md`)
- Word (`.docx`)
- PowerPoint (`.pptx`)

Slides containing only images are not read. The workflow limits combined
document text sent to the language model to 80,000 characters.

## Requirements

- An n8n instance with the workflow's node types available.
- A Google Gemini API credential configured in n8n.
- A Notion API credential configured in n8n.
- A Notion integration with access to the destination page or database.

## Setup

1. Import `NotFlow.json` into n8n.
2. In the **Google Gemini Chat Model** node, select your Google Gemini API
   credential.
3. In both Notion HTTP Request nodes, select your Notion API credential.
4. Grant your Notion integration access to the page or database where the
   workflow should create pages. Configure the destination in the workflow's
   **Parse & Build Notion** node if needed.
5. Test the form and workflow, then activate it when ready.

The exported workflow intentionally contains `Fill Your ...` credential
placeholders, not API keys. Configure credentials through n8n; do not add
secrets to the exported JSON or commit them to Git.

## Form behavior

The form asks for a question, an optional document, and a level of detail
(Low, Medium, or High). The workflow extracts supported file text, creates
structured JSON with a title, summary, key points, answer, action items, and
tags, then creates a Notion page.
