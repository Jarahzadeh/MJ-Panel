# MJ Panel

MJ Panel is a Cloudflare Workers and D1 based panel.

## Install

1. Upload the contents of this `panel/` folder to your GitHub repository.
2. Make sure `Source.js` is the Worker entry file.
3. Add a `DB` binding for your D1 database in Cloudflare.
4. Add these runtime variables in Cloudflare:
   - `CF_ACCOUNT_ID` as `Text`
   - `CF_API_TOKEN` as `Secret`
5. Connect the GitHub repository to Cloudflare Workers.
6. Use this deploy command:
   ```bash
   npx wrangler deploy
   ```

## Contact

- WhatsApp: `+971557256658`

## Notes

- Do not commit your API token to GitHub.
- If you change the Worker source, redeploy the repository.
- The Worker expects a D1 binding named `DB`.

