# YT Solutions website

A responsive, static one-page website built with HTML, CSS and vanilla JavaScript.

## Files
- `index.html`: complete website. No build step or package installation required.

## Before publishing
1. Confirm that `jo@yohan-ts.com` is the preferred public contact address.
2. Confirm the project descriptions and that Veristock, SouqNote and StyleAddis are approved for public portfolio mention.
3. Replace any copy that does not accurately describe the services or availability you offer.

## Deploy to `YTsolutions.yohan-ts.com`

### 1. Upload the website
Upload `index.html` to the document root of the hosting account for the subdomain. The file must be named `index.html`.

### 2. Point the subdomain to hosting
In the DNS manager for `yohan-ts.com`, create the DNS record requested by your hosting provider:
- If the host provides an IP address: create an `A` record with host/name `YTsolutions` and value equal to that IP.
- If the host provides a target hostname: create a `CNAME` record with host/name `YTsolutions` and value equal to that hostname.

Do not create both records for the same subdomain. Use the exact target supplied by the host.

### 3. Add the subdomain in hosting
In your hosting control panel, add `YTsolutions.yohan-ts.com` as a subdomain and set its document root to the folder where `index.html` was uploaded.

### 4. Enable HTTPS
Issue/enable an SSL certificate for `YTsolutions.yohan-ts.com` in the hosting panel (often Let's Encrypt or AutoSSL), then enable HTTPS redirect if the host offers it.

### 5. Verify
Open:
- `https://YTsolutions.yohan-ts.com`
- `https://ytsolutions.yohan-ts.com`

DNS names are case-insensitive, so both should resolve to the same host.

## Notes
- The page uses Google Fonts when online and falls back to system fonts if unavailable.
- No backend, database, build process or framework is required.
- The contact CTA opens the visitor's email app using `mailto:jo@yohan-ts.com`.
