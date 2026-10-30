# Jalali Insurance Agency — Version 2 (developmental)

Changes: clickable expandable coverage cards, personal auto/homeowners/renters feature, expanded quote dropdown, preselected quote options. Form remains preview-only (no submissions sent).

## Update GitHub without changing the live site
1. Open your GitHub repository and switch to **developmental**.
2. Open **jalali-agency-clean-logo/index.html** and click the pencil to edit.
3. Open the UPDATED index.html in this ZIP in a text editor, copy its entire contents, and replace the contents of the GitHub index.html editor.
4. Commit directly to **developmental** with message `Add expandable coverage and personal insurance`.
5. Wait for the Cloudflare developmental preview build, then open the preview URL and test all cards and quote selection.
6. Do not merge into main until production deployment settings are reviewed.

Alternatively use GitHub's Add file > Upload files while inside `jalali-agency-clean-logo` on the developmental branch; drag only the updated `index.html`, replace the existing file, and commit. Do not upload the ZIP as a single file.

The included wrangler.jsonc is the same as the working root configuration and need not be changed.
