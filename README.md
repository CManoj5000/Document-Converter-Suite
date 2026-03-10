# Document-Converter-Suite

## Team Name: 

Crazy Coders

## Team Members: 

S.Mahesh Naik

C.Manoj Kumar


## Documentation

I built the Document Converter Suite because I was frustrated with "free" online tools that were either cluttered with ads or, more importantly, required me to upload sensitive files to their servers.

This is a local-first, privacy-focused workspace where you can manipulate your files without them ever leaving your browser. Your data stays yours.

# Why I built this

The suite handles the document tasks I find myself doing most often:

PDF Merging: A simple way to stack multiple files into one.

Precision Splitting: No more re-printing; just extract the specific pages or ranges you actually need.

Smart Compression: Makes your PDFs small enough for email without destroying the quality.

Word to PDF: Quick .docx conversions that run entirely in the browser—no Microsoft account required.

Protection: Add custom text watermarks for drafts or confidential files with adjustable angles and transparency.

Text Scraping: Pull out metadata and raw text for a quick look inside the file.

# Behind the Scenes

I wanted a modern, "glassmorphism" look that felt smooth and responsive. To make that happen:

Tailwind CSS handles the dark-mode aesthetic.

PDF-Lib and Mammoth.js do the actual file processing right in your browser's memory.

Local Data SDK keeps a history of your work so you don't lose track of your files, while keeping that data strictly offline.

# How to get it running

There is no "installation" or server setup required.

Clone or download this repository.

Open index.html in any modern browser.

Drag your files in and get to work.

# Privacy & Transparency

Most online converters are black boxes. You don't know where your files go once you hit "Upload." With the Document Converter Suite, there is no upload. The processing logic happens on your CPU. If you are dealing with sensitive contracts, resumes, or financial statements, this is a much safer alternative to the big "cloud" converters.

# Contributing

If you have an idea for a new feature—like an image-to-PDF tool or a digital signature pad—I'd love to see it. Feel free to fork the repo, experiment with the code, and send over a pull request.

## Features

### File Conversion

PDF to Word (.docx)

PDF to Excel (.xlsx)

PDF to PowerPoint (.pptx)

Word to PDF

Excel to PDF

PowerPoint to PDF

### PDF Tools

Merge Multiple PDFs

Split PDF into Separate Pages

### Tech Stack

Frontend Design: Canva (UI Design)

Backend: (Add your backend technology here)

File Processing Libraries: (Add libraries used, if any)

Deployment: Self-hosted / Local Server Compress PDF Files

Add Watermarks to PDF
