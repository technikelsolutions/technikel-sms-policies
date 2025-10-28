
# Technikel Solutions SMS Policies

This repository contains static HTML pages for Technikel Solutions's SMS program:

- `terms.html` — SMS Terms & Conditions
- `privacy.html` — SMS Privacy Policy
- `index.html` — Landing page linking to both documents (optional)

## How to publish on GitHub Pages

1. Create a new public repository on GitHub (for example, `technikel-sms-policies`).
2. Upload `terms.html`, `privacy.html`, and `index.html` to the root of the repo.
3. In the repository, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
5. Choose the `main` branch and the `/ (root)` folder, then click **Save**.
6. Wait 1–2 minutes. Your site will be available at:
   
   ```
   https://<your-github-username>.github.io/technikel-sms-policies/
   ```

7. Update the links you use in Microsoft Teams SMS campaign to point to:
   
   - Terms: `https://<your-github-username>.github.io/technikel-sms-policies/terms.html`
   - Privacy: `https://<your-github-username>.github.io/technikel-sms-policies/privacy.html`

## Copy-paste snippets for your campaign

**Call to Action (CTA)**

```
Text JOIN to [insert phone number] to receive SMS alerts from Technikel Solutions. By subscribing, you agree to our Terms and Privacy. Up to 4 msgs/mo. Msg & data rates may apply. Reply HELP for help or STOP to cancel. Terms: <link to terms> Privacy: <link to privacy>
```

**Opt-in confirmation**

```
You’re subscribed to Technikel Solutions SMS alerts. Up to 4 msgs/mo. Msg & data rates may apply. Reply HELP for help or STOP to cancel.
```

**Opt-out**

```
You’ve been unsubscribed from Technikel Solutions SMS alerts. No further messages will be sent.
```

**HELP**

```
For help, contact support@technikel.ca. Reply STOP to unsubscribe.
```

> Tip: Replace `[insert phone number]` with your Teams Phone number and paste the published GitHub Pages links where indicated.

## Notes

- These pages include the disclosures commonly required by carriers and Microsoft for Teams SMS campaigns, including message frequency, STOP/HELP instructions, data rates, and an explicit statement that mobile opt-in data is not shared with third parties.
- Keep these pages public and accessible.
- Update the **Last updated** date in each file whenever you change content.

