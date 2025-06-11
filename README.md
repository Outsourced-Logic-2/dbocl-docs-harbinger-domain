# Analog Labs Documentation

This repository contains the public documentation for **Analog Labs** and our flagship product, the **Human Verification Card**. The documentation site is powered by [Mintlify](https://www.mintlify.com/).

## Development

1. Install the Mintlify CLI:
   ```bash
   npm i -g mintlify
   ```
2. Run the development server from the repository root:
   ```bash
   mintlify dev
   ```

## Publishing Changes

Push changes to the default branch to deploy the updated documentation site.

## Troubleshooting

- If the development server fails to start, run `mintlify install` to reinstall dependencies.
- If a page loads as a 404, make sure you are running commands from the folder containing `docs.json`.
