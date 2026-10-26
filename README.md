# Copywell — Markdown to Office

Copywell is a lightweight, browser-based utility that converts Markdown into formatted text you can copy and paste into Microsoft Word, Outlook, and other applications that support rich text.

## Features

- **Live preview:** See formatted content as you type or paste Markdown.
- **File import:** Open `.md`, `.markdown`, or `.txt` files.
- **Copy formatted:** Copy headings, bold and italic text, lists, tables, links, quotes, and code.
- **Formatting styles:** Choose **Office classic** or **Compact email**.
- **Copy plain text:** Copy the rendered content without formatting.
- **HTML download:** Save the formatted content as a standalone HTML document.
- **Example content:** Use the built-in example to explore the available formatting.

## How to Use Copywell

1. Paste Markdown into the **Markdown** panel, or select **Open .md file**.
2. Review the result in the **Formatted Preview** panel.
3. Choose a formatting style.
4. Select **Copy formatted**.
5. Paste into your destination application using **Ctrl + V** on Windows or **⌘ + V** on macOS.
6. Choose **Keep Source Formatting** if the application offers paste options.

For Outlook, compose your message in **HTML format** to preserve formatting.

### Using Content from ChatGPT

Copy the Markdown text from a ChatGPT response and paste it into Copywell.

If the copied content does not include Markdown syntax, ask ChatGPT:

> Provide this response as raw Markdown inside a single code block.

Then copy the contents of that code block into Copywell.

### Downloading HTML

Select **Download HTML** to save a formatted document. Open the downloaded file in your browser to view, select, and copy its content.

## Privacy and Security

Copywell processes your content locally in your browser. The application does not upload or save the Markdown you enter, and it does not require an account, API key, or backend service.

The application sanitizes rendered HTML and restricts scripts, embedded content, and external resource loading. Browser extensions, clipboard history, and the destination application operate independently of Copywell.

## Limitations

- Formatting support varies between destination applications.
- Tables, spacing, fonts, and code formatting may change when pasted.
- Images, embedded media, scripts, and custom HTML styling are not supported.
- Documents are limited to **200,000 characters**.
- Imported files must be **1 MB or smaller**.
- Content is not saved between sessions. Keep a separate copy before closing or refreshing the page.
- Automatic clipboard access may be restricted by your browser. If copying is blocked, follow the on-screen instructions or download the HTML document.

## Hosting

Copywell is a static website that can be hosted on GitHub Pages or another static hosting service. No build step or server-side installation is required.

Keep the application files together and serve the site over **HTTPS** for browser clipboard support.