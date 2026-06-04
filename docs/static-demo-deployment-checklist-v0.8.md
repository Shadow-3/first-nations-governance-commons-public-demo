# Static Demo Deployment Checklist v0.8

Project: First Nations Governance Commons  
Target: public fake-data static demo

## Purpose

Deploy the static public demo safely so advisors can review it without needing to unzip local files.

## Deployment Options

- GitHub Pages.
- Netlify.
- Cloudflare Pages.
- Static VPS.
- Private file share or ZIP.

## Pre-Deployment Checks

- [ ] All data is fake/sample data.
- [ ] No real community records.
- [ ] No member data.
- [ ] No cultural material.
- [ ] No secrets.
- [ ] No private API keys.
- [ ] Public demo warning visible.
- [ ] Links work locally.
- [ ] Desktop screenshot checked.
- [ ] Mobile screenshot checked.

## Deployment Steps

1. Create hosting project.
2. Upload contents of `outputs/public-demo`.
3. Set `index.html` as default page.
4. Disable unnecessary analytics/tracking.
5. Confirm HTTPS.
6. Open public URL.
7. Test nav, filters, support button, evidence links.
8. Send public URL to reviewers.

## Post-Deployment Checks

- [ ] Public URL opens.
- [ ] Fake-data warning visible.
- [ ] Evidence links work.
- [ ] Download buttons work.
- [ ] Mobile view works.
- [ ] No unexpected files are publicly exposed.

## Review Link Email Snippet

This is a public fake-data demo. It is not a real consultation and contains no real community/member/cultural data. Please review the model, not the sample numbers.
