# How CopyDetect Works (High-Level)

CopyDetect checks content for plagiarism using Google's Custom Search API (Google Search technology).

## Process Overview
1. Content is received from the user (text or documents)
2. The content is processed line-by-line
3. Each line is checked against web sources indexed by Google Search
4. Matching lines are detected
5. Results show:
   - the matched line
   - the source website (URL)
   - match context where applicable

## Important Notes
- CopyDetect is not an AI content detector
- Results depend on public web availability and indexing
- The tool focuses on plagiarism and source attribution
