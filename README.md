# Shri Hari Wellness Center — Multilingual Website

A 13-language static website for Shri Hari Wellness Center, Kurukshetra.

## Languages
English (index.html) plus: Hindi, Bengali, Marathi, Telugu, Tamil, Gujarati,
Kannada, Malayalam, Odia, Punjabi, Assamese and Nepali.

Each language is a separate page (e.g. hi.html, ta.html). A language switcher
in the header links between them.

## Files
- index.html  — English (default)
- <code>.html — one page per language
- logo.png    — shared logo

## Enquiry form
Every page has an enquiry form (Name, Age, Height, Weight, City, Mobile).
On submit it opens WhatsApp with all the details pre-filled, addressed to
+91 96909 80001. No server, database or third-party service is required.

## Hosting on GitHub Pages
1. Create a new public repository.
2. Upload every file in this folder to the repository root.
3. Repository Settings -> Pages -> Source: "Deploy from a branch",
   Branch: main, Folder: / (root). Save.
4. Your site appears at https://<username>.github.io/<repo-name>/

No build step and no dependencies are required.
