# Higuchi Publisher 0.8.10

Draft articles, prepare text and illustrations for Dzen, and export to Markdown or HTML. The interface supports English, Russian, and Simplified Chinese. Requires desktop Obsidian 1.13.0 or later.

## Installation

In desktop Obsidian, open **Settings → Community plugins → Browse**. Search for **Higuchi Publisher**, then select **Install** and **Enable**.

## Language

Open **Settings → Higuchi Publisher → Interface language**, choose a language, and restart Obsidian. Existing articles and saved Dzen transfer records keep their contents.

## Usage

Open Publisher from the feather icon or the command palette. Confirm the articles folder and create your first article. Select **Prepare for Dzen** to preview the layout at phone width, crop screenshots, and export numbered copies of the illustrations. Use the copy buttons to paste the title, text and captions into your Dzen draft. After you transfer the article, mark that version to compare it with later edits.

In the Articles panel, use **Check** to find missing notes and images, **Preview** to review the assembled article, or **Export** to save Markdown and HTML. In the editor, run **Insert illustration** to pick an image or paste one from the clipboard, add a caption, and crop a Dzen copy. The original image stays in the project.

The plugin writes to the clipboard when you choose a copy command. Articles and images are processed locally in your vault. The plugin does not make network requests or collect telemetry. It can open your saved Dzen draft in your browser. Use Dzen in your browser to create the draft. HTML export embeds local images as Base64 data to make the file self-contained. The official build is free for personal and commercial use. The source code is private and available to Obsidian for review.

See the [binary license](LICENSE) and [third-party notices](THIRD-PARTY-NOTICES.txt).

[Руководство на русском](README.ru.md)
