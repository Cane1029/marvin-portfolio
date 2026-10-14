# GitHub Pages upload files

Upload the contents of this folder to the root of a new GitHub repository: `index.html` and `CNAME`.

In the repository, open **Settings → Pages**, set the source to **Deploy from a branch**, choose the `main` branch and `/(root)`, then save. Set `marvinguevarra.com` as the custom domain if GitHub has not picked it up from `CNAME`.

At Hostinger, add the GitHub Pages DNS records shown in the site setup. Keep the existing Hostinger email MX, SPF, DKIM, and DMARC records so `connect@marvinguevarra.com` continues working. GitHub Pages instructions: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site
