# Webpage Snapshot Plugin

A Claude Code plugin that enables capturing screenshots of webpages using browser automation.

## Features

- Capture full-page or viewport screenshots of any webpage
- Automatic page load detection
- Clean browser management

## Installation

This plugin is included in the claude-code-plugins bundle. To use it:

1. Ensure you have Claude Code installed
2. The plugin is automatically available in projects that include the marketplace

## Usage

Use the `/webpage-snapshot` command followed by the URL you want to capture:

```
/webpage-snapshot https://example.com
```

The command will:
1. Open a browser window
2. Navigate to the specified URL
3. Wait for the page to load
4. Capture a screenshot
5. Save it with a descriptive filename
6. Close the browser

## Examples

Capture a screenshot of a website:
```
/webpage-snapshot https://www.anthropic.com
```

## Requirements

- Claude Code with browser automation support
- Internet connection for accessing webpages

## Author

Created by 大粒子 for the Claude Code ecosystem.

## Version

1.0.0
