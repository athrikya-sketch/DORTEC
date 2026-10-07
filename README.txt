DORTEC website - deploy guide
1. Upload this whole folder (or the zip) to a static host. Easiest free options: Cloudflare Pages or Netlify (drag and drop).
2. In the host's dashboard, add your custom domain (e.g. dortec.com) and follow its DNS instructions. HTTPS is automatic.
3. The _headers file adds security headers on Cloudflare Pages and Netlify. On other hosts, set the same headers in the host's settings.
4. To edit content later, change index.html (each text has data-en / data-ar attributes for English and Arabic).
