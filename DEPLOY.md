# How to Deploy NFCycle

Since your code is already on GitHub, you can easily deploy it using **Vercel** or **Netlify**. Both are excellent, free alternatives to Cloudflare Pages.

## Option 1: Vercel (Recommended)
Vercel is extremely fast and easy to use.

1.  **Sign Up/Login:** Go to [vercel.com](https://vercel.com) and log in with **GitHub**.
2.  **Add New Project:** Click **"Add New..."** > **"Project"**.
3.  **Import Repository:** Find `nfcycle-web` in the list and click **Import**.
4.  **Deploy:** You don't need to change any settings. Just click **Deploy**.
5.  **Wait:** In about 1 minute, your site will be live!

### Connecting Your Domain (`nfcycle.shop`) on Vercel
1.  Go to your project dashboard on Vercel.
2.  Click **Settings** > **Domains**.
3.  Enter `nfcycle.shop` and click **Add**.
4.  Vercel will give you **Nameservers** (e.g., `ns1.vercel-dns.com`, `ns2.vercel-dns.com`).
5.  **Go to GoDaddy:**
    *   Manage your domain `nfcycle.shop`.
    *   Go to **DNS Management**.
    *   Change "Nameservers" from "Default" (or Cloudflare) to **Custom**.
    *   Paste the Vercel nameservers there.
6.  Wait for propagation (usually 15 mins to 1 hour).

---

## Option 2: Netlify
Netlify is another popular choice for static sites.

1.  **Sign Up/Login:** Go to [netlify.com](https://netlify.com) and log in with **GitHub**.
2.  **New Site:** Click **"Add new site"** > **"Import an existing project"**.
3.  **Connect to GitHub:** Select GitHub and authorize it.
4.  **Select Repo:** Choose `nfcycle-web`.
5.  **Deploy:** Click **Deploy site**.

### Connecting Your Domain (`nfcycle.shop`) on Netlify
1.  Go to **Domain Management** > **Add a domain**.
2.  Enter `nfcycle.shop`.
3.  Click **Verify**.
4.  Netlify will give you **Nameservers** (e.g., `dns1.p01.nsone.net`, etc.).
5.  **Go to GoDaddy:**
    *   Manage your domain `nfcycle.shop`.
    *   Go to **DNS Management**.
    *   Change "Nameservers" to **Custom**.
    *   Paste the Netlify nameservers there.

## Summary
- **Source:** GitHub Repository (`nfcycle-web`)
- **Host:** Vercel OR Netlify (Your Choice)
- **Domain:** GoDaddy (Point Nameservers to your chosen host)
