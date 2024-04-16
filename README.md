# markdown_convert_nautilus

_Nautilus script to add Markdown to PDF conversion to the right click menu._

## Requirements

- The [markdown-convert](https://github.com/Julynx/markdown_convert) Python package: `pip install markdown-convert`.
- The [nautilus](https://packages.debian.org/bookworm/nautilus) file manager.

## Installation

```bash
wget https://raw.githubusercontent.com/Julynx/markdown_convert_nautilus/main/Convert%20to%20PDF -P ~/.local/share/nautilus/scripts/Markdown/Convert\ to\ PDF
chmod +x ~/.local/share/nautilus/scripts/Markdown/Convert\ to\ PDF
```

## Usage

- Right click on a Markdown file and select `Scripts` > `Markdown` > `Convert to PDF`.

- You can also select both a CSS file and a Markdown file by dragging your mouse or holding the CTRL key.
  
  When you click `Convert to PDF`, the selected CSS file will be passed to `markdown-convert` as `--css=<selected_css_file>`.

