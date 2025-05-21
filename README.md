
# Unified Blocklist

## Overview
This project aggregates multiple domain blocklists from various online sources into a single unified blocklist file. It helps clean up browsing by blocking ads, trackers, and malicious domains.

## Features
- Downloads and merges over 40 different blocklists.
- Automatically removes empty lines and comments.
- Saves the unified list into a plain text file compatible with various blocking tools.
- Handles download errors gracefully and skips unavailable URLs.

## Requirements
- Python 3.7 or higher
- `requests` library (install with `pip install requests`)

## Usage
1. Open your command prompt or terminal.
2. Navigate to the project directory:
   ```
   cd path\to\unified-blocklist
   ```
3. Run the update script:
   ```
   python scripts/update_blocklist.py
   ```
4. The combined blocklist will be saved to:
   ```
   data/unified_blocklist.txt
   ```

## Customizing Sources
You can add, remove, or modify the blocklist URLs by editing the `urls` list inside:
```
scripts/update_blocklist.py
```

## Notes
- Ensure you have an active internet connection when running the script.
- Invalid or unreachable URLs are skipped with an error message.
- It’s recommended to run the script regularly to keep the blocklist updated.

## License
This is an open-source project. Feel free to use and modify it.

---

## Contact
For questions or suggestions, please open an issue on the GitHub repository page.
