# KeepFlip GitHub Pages Website

This folder is a static website for:

- `https://www.keep-flip.com/`
- `https://www.keep-flip.com/privacy/`
- `https://www.keep-flip.com/terms/`
- `https://www.keep-flip.com/support/`

## Files

```text
index.html
styles.css
404.html
CNAME
.nojekyll
privacy/index.html
terms/index.html
support/index.html
```

## Publish it with GitHub Pages

1. Create a new GitHub repository named `keepflip-site`.
2. Upload every file and folder from this website folder to the root of the repository.
3. Open the repository's **Settings** → **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder.
6. Save. GitHub will give you a temporary `github.io` address.
7. In GitHub Pages settings, enter `www.keep-flip.com` as the custom domain.
8. At Squarespace, create the CNAME DNS record GitHub tells you to add for `www`.
9. Wait for GitHub Pages to verify the domain, then enable **Enforce HTTPS**.

The `CNAME` file in this project is already set to:

```text
www.keep-flip.com
```

## Update your KeepFlip app

Use this exact app link after GitHub Pages and HTTPS are ready:

```ts
const PRIVACY_POLICY_URL = "https://www.keep-flip.com/privacy/";
```

## Important legal review note

The Privacy Policy and Terms are launch-ready drafts tailored to the current KeepFlip feature set: account access, item records, photos, optional location, AI-assisted analysis, repair/parts research, and listing preparation.

Before launch, have a qualified attorney review them—especially before you add:
- payments;
- buyer/seller transactions;
- a public marketplace;
- ads or analytics trackers;
- subscriptions;
- data sharing beyond the listed providers.
