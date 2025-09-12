# Azure Storage SAS Token Generator

https://samdobson.github.io/azure-sas-token-generator/

A simple, client-side HTML application for generating Azure Storage Shared Access Signature (SAS) tokens.

It's fully local. All processing happens in your browser - no data is sent to external servers.

## Usage

1. Save and open `index.html` (or click the link above) in any modern web browser
2. Fill in the required parameters:
   - Storage Account Name
   - Storage Account Key
   - Container Name
3. Configure permissions, resource types, and time settings
4. Click "Generate SAS Token" to create your token

## Security

- All cryptographic operations use the Web Crypto API
- Your storage account key never leaves your browser
- No network requests are made during token generation

## Requirements

- Modern web browser with Web Crypto API support (Chrome, Firefox, Safari, Edge)
- No additional dependencies or installation required

