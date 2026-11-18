# Dawset Benzin | Public policies

Current bilingual policy files are mirrored from `totalosy2020-art/dawset-benzin` (release/1.0-accounts-alpha, `docs/`), updated 15 November 2026.

- `index.html` and `privacy.html`: Privacy policy for device storage, optional Google sign-in, Google ML Kit and encrypted Firebase cloud backups.
- `deletion.html`: Public account and data deletion request instructions.
- `terms.html`: Terms of use.

## Publication checklist

These files are in a **public GitHub repository**, but that alone does not make them working hosted policy pages.

1. Enable GitHub Pages for this repository (Settings → Pages → Deploy from a branch → `main` / root), or publish all three HTML pages on another owner-controlled public HTTPS website.
2. Verify the privacy and deletion URLs from an incognito browser, without logging into GitHub.
3. Use the verified public URLs in Google Play Console's Privacy policy and Account deletion fields.
4. Verify that the email inbox in the policy is monitored, and test an authenticated deletion request end-to-end (Firebase account plus associated Firestore backup).
5. Reconcile Play Data safety disclosures against the exact signed account-enabled AAB before submission.

If Pages is enabled with default GitHub Pages naming, URLs are expected to be under `https://totalosy2020-art.github.io/dawset-benzin-privacy/`, but **do not submit these URLs until they respond successfully**.

When the app policy changes, regenerate `docs/` from `policies/content.json` in the app repository and mirror the updated HTML here.
