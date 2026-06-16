# Sentinel Financial Threat Intelligence

A browser-based financial transaction screening tool designed to help identify potentially suspicious activity in bank statements and transaction records.

## Features

- Upload TXT, CSV, or PDF bank statements
- Scan for predefined risk indicators
- Detect keywords associated with:
  - Gambling
  - Cryptocurrency
  - Money transfer services
  - Fraud and scam indicators
  - Dark web references
- Create custom categories and keywords
- Generate a risk score
- Export investigation findings

## How It Works

Sentinel is able to extract text from multiple uploaded files and compares transaction descriptions against predefined and user-defined keyword lists. Matching transactions are flagged and grouped into categories for review.

## Example Use Cases

- Financial investigations
- Cybercrime investigations
- Digital forensics exercises
- Fraud awareness and research
- Educational demonstrations

## Technologies Used

- HTML
- CSS
- JavaScript
- PDF.js

## Limitations

- This is a proof-of-concept project.
- Results are based on keyword and rule matching.
- Findings should be treated as indicators requiring review, not evidence of wrongdoing.
- Not intended for production or law-enforcement operational use.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/sentinel-financial-threat-intelligence.git
