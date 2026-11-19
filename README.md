# Lead form embed test site (fictional)

Kererū Lane Immigration is a made-up firm. This site exists only to test AdviserAide lead-form embeds (AA-2410, scenarios 23–26).

- `visa-enquiry.html` – the embed code exactly as copied from Share > Embed (tst1 form `WVbc1PcrWkeg`).
- `embed-test.html` – QA helper: `?form=<id>&host=<forms host>` loads any form and logs postMessage events and frame height.
- `wp-blueprint.json` – opens a second, throwaway WordPress site in WordPress Playground with the same embed (use it as the "not allowed" website).
