# RAG-Assistant Examples

## Example 1: Academic Research Assistant

**Scenario:** You have research papers and want to query them.

**Steps:**
1. Place PDFs in `./data` folder
2. Run: `python cli.py ingest`
3. Ask questions like:
   - "What are the main findings?"
   - "Compare methodologies in papers X and Y"
   - "What datasets were used?"

## Example 2: Technical Documentation Helper

**Scenario:** Query software documentation.

**Steps:**
1. Upload markdown/text docs via web UI
2. Ask:
   - "How do I install this software?"
   - "What are the configuration options?"
   - "Show me API endpoints"

## Example 3: Meeting Notes Search

**Scenario:** Search through meeting transcripts.

**Steps:**
1. Save transcripts as TXT files in `./data`
2. Ingest: `python cli.py ingest`
3. Query:
   - "What did we decide about feature X?"
   - "List all action items from last month"
   - "Who was responsible for task Y?"
