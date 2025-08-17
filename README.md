# Literature Manager Data Repository

This repository stores data for the Literature Management System.

## Directory Structure

- `papers.json` - Main papers database (JSON format)
- `pdfs/` - PDF files storage
- `thumbnails/` - Thumbnail images for papers

## File Formats

### papers.json
Contains an array of paper objects with the following structure:
```json
{
  "id": "unique-id",
  "title": "Paper Title",
  "authors": ["Author1", "Author2"],
  "year": 2024,
  "journal": "Journal Name",
  "abstract": "Paper abstract...",
  "keywords": ["keyword1", "keyword2"],
  "doi": "10.xxxx/xxxx",
  "pdfUrl": "url-to-pdf",
  "thumbnailUrl": "url-to-thumbnail",
  "uploadDate": "2024-01-01T00:00:00.000Z"
}
```

## Usage

This repository is automatically managed by the Literature Management System. 
Data is synced automatically when papers are uploaded through the web interface.

## Access

- Repository: https://github.com/formicrogses/literature-manager-data
- Web Interface: https://formicrogses.github.io/literature-manager