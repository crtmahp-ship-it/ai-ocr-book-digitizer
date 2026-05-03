# AI OCR Book Digitizer

A browser-based AI-powered OCR tool that converts physical book photos into formatted DOCX files — no installation required.

## What it does

- Upload multiple book page photos (batch processing)
- AI reads and extracts text with full formatting preserved
- Outputs a structured DOCX file with headings, bullet points, and tables
- Supports Vietnamese and multilingual content

## How it works

Built as a single HTML file that runs entirely in the browser. Uses Gemini Vision API to OCR each image, then generates a formatted Word document via docx.js — no backend, no server.

## Use case

Personal knowledge management: digitizing business and educational books into searchable, editable documents for study and AI-assisted learning workflows.

## Tech stack

- Gemini Vision API (image understanding + OCR)
- docx.js (DOCX generation)
- Vanilla JavaScript, runs offline after loading

## Status

Active — currently digitizing a library of Vietnamese business books.
