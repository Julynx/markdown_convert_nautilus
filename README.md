# markdown_convert_nautilus

_Nautilus script to add Markdown to PDF conversion to the right click menu._

## Requirements

- The [markdown-convert](https://github.com/Julynx/markdown_convert) Python package: `pip install markdown-convert`.
- The [nautilus](https://packages.debian.org/bookworm/nautilus) file manager.

## Installation

```bash
wget https://raw.githubusercontent.com/Julynx/markdown_convert_nautilus/main/Convert%20to%20PDF -P ~/.local/share/nautilus/scripts/Markdown/Convert\ to\ PDF
wget https://raw.githubusercontent.com/Julynx/markdown_convert_nautilus/main/Convert%20to%20PDF%20(live) -P ~/.local/share/nautilus/scripts/Markdown/Convert\ to\ PDF\ \(live\)
chmod +x ~/.local/share/nautilus/scripts/Markdown/Convert\ to\ PDF
chmod +x ~/.local/share/nautilus/scripts/Markdown/Convert\ to\ PDF\ \(live\)
```

## Usage

- Right click on any Markdown file, then click `Scripts` > `Markdown` > `Convert to PDF`.
- For real-time conversion to PDF, click `Scripts` > `Markdown` > `Convert to PDF (live)`.
- You can also select both a CSS file and a Markdown file, and the output PDF will be styled with the selected CSS file.
