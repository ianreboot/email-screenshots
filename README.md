# Email Screenshots Repository

## Purpose
Storage for anonymized email creative screenshots for conversion analysis.

## Security & Privacy
- All filenames are anonymized using SHA256 hashing (8-character IDs)
- No identifying information in filenames or commit messages
- Screenshots contain only creative content, no PII

## Structure (v3.1 - Anonymized)
- **Anonymous IDs only** (e.g., `8787d6ac.png`)
- **No creative IDs or company names in repository**
- **Mapping maintained separately (never committed)**

## Usage
1. Generate anonymous ID from creative ID using SHA256
2. Upload with anonymous filename
3. Get raw URL: `https://raw.githubusercontent.com/ianreboot/email-screenshots/main/[anon_id].png`
4. Use URL in analysis database

## Important
This is a public repository. Never commit:
- Original creative IDs
- Company/offer names
- Mapping files
- Any identifying information