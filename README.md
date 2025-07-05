# Find Safari Tab

An Alfred 5 workflow to search open Safari tabs by keyword (in title or URL) and jump to the first match.

---

## Requirements

- Alfred 5.0 or later  
- macOS Sonoma (or later)  
- Alfred must be granted **Accessibility** and **Automation** permissions for Safari

## Installation

1. Clone this repo (if you haven’t already):  
   ```bash
   git clone git@github.com:jason-vanderburg/FindSafariTab.git
   cd FindSafariTab
   ```

2. Import the workflow:  
   - Double-click `FindSafariTab.alfredworkflow`  
   - Open **System Settings → Privacy & Security → Accessibility** and ensure **Alfred 5** is checked  
   - Then in **Privacy & Security → Automation**, allow **Alfred** to control **Safari**

## Usage

- **Keyword trigger**  
  In Alfred, type:
  ```
  findtab <search-term>
  ```
  e.g.
  ```
  findtab github
  ```
  Safari will front the first tab whose title or URL contains `<search-term>`.


## Troubleshooting

- **No response?**  
  - Verify Alfred’s Accessibility & Automation permissions  
  - Check that the workflow is enabled in Alfred Preferences → Workflows

- **Multiple matches?**  
  - This script picks the first match. You can extend it later to list all matches if needed.

## License

MIT © Jason Vanderburg
