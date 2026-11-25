# Vhiper

A fast, lightweight, **single-file** web tool to validate, normalize, deduplicate, and detect mobile network operators for Bangladeshi phone numbers—with zero external dependencies.

**Live Demo:** `https://vhiper.vercel.app/`

## Features

- **Bulk Validation & Parsing:** Paste hundreds of numbers separated by new lines, commas, or spaces.
- **Format Normalization:** Automatically converts mixed inputs (`017...`, `88017...`, `+88017...`, or hyphenated numbers) into clean **Local (`01...`)** and **International (`+8801...`)** formats.
- **Operator Detection:** Identifies all Bangladeshi mobile operators based on prefix:
  - **Grameenphone:** `013`, `017`
  - **Robi:** `018`
  - **Airtel:** `016`
  - **Banglalink:** `014`, `019`
  - **Teletalk:** `015`
- **Duplicate & Invalid Filtering:** Automatically separates duplicate entries and invalid numbers for easy cleanup.
- **One-Click Copy & CSV Export:** Copy clean `01...` or `+8801...` lists directly to your clipboard or download a structured `.csv` file.
- **100% Client-Side & Private:** Everything runs locally in your browser; no phone numbers are ever uploaded to any server.

## Quick Start

1. Download `index.html`.
2. Double-click the file to open it in any modern web browser.
3. Paste your phone number list and click **Process Numbers**.

## Use Cases

- Cleaning SMS marketing or customer contact lists before bulk campaigns.
- Verifying user-submitted phone numbers from e-commerce orders or forms.
- Standardizing phone columns for CRM, Excel, or database imports.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request to improve operator rules, UI, or export options—while keeping the project self-contained in a single HTML file.

## License

Distributed under the **MIT License**. See `LICENSE` for more information.
