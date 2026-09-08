# Ecotera Asia file updates

This package contains the 10 HTML files retrievable from the referenced conversation and a welcome-email draft. account.html was not returned by attachment retrieval and is not included. Keep your existing account.html; it has not been modified or verified here.

Before using signup confirmation or password reset, fill in LOGIN_REDIRECT_URL and PASSWORD_RESET_REDIRECT_URL in login.html with the confirmed absolute Asia site URLs, and allow them in Asia Supabase Auth settings. These are intentionally blank with TODO comments because no Asia GitHub Pages URL was present in the retrieved files.

The existing Asia URL and publishable key were verified to match across index.html, admin.html and practice.html, and copied into the seven remaining pages. The field-data bucket, field_data table and file_path column mappings were updated. Admin uses sample-images. Only the visible homepage brand text was changed. practice.html is byte-for-byte unchanged. new-sample.html differs only in its Supabase URL/key; RPC names and kit logic are unchanged. Field Data WebP compression is preserved.

Validation: inline JavaScript was syntax-checked. my-samples.html has a pre-existing invalid multiline quoted string, preserved to keep this migration scoped to the requested edits; that page needs a separate fix before it can run. Legacy Home Supabase credentials and old field-data/admin bucket references are absent. No live authentication, uploads, database operations or email sending were performed. The New Sample backend RPC definitions still require inspection before confirming compatibility.
