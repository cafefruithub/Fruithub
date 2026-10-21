# Fruit Hub Cafe – Delivery Tracker

A single-page delivery tracking site. It runs entirely in the browser and syncs between devices through a private GitHub Gist.

## Put it online (GitHub Pages, free)

1. Sign in at github.com and click **New repository**. Name it, for example, `fruit-hub-deliveries`.
2. Click **uploading an existing file** and upload `index.html` (and this README if you like). Click **Commit changes**.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, set Source to **Deploy from a branch**, choose the `main` branch and the `/ (root)` folder, then **Save**.
5. After about a minute your site is live at `https://YOUR-USERNAME.github.io/fruit-hub-deliveries/`. Open it on every phone or computer and add it to the home screen.

## Connect all devices (Gist sync)

1. Go to github.com/settings/tokens and choose **Generate new token (classic)**.
2. Tick only the **gist** permission, set an expiry you are happy with, and generate the token. Copy it.
3. On the site, open **Sync devices**, paste the token and press **Connect**. A private Gist is created automatically.
4. On every other device, open the site and paste the **same token**. The site finds the same Gist and the data matches everywhere.

## Good to know

- The site address is public, but your orders are not: they live in your private Gist and need your token to read.
- Never write the token into the code or share it. If it leaks, delete it in GitHub settings and create a new one.
- The WhatsApp report opens WhatsApp with the message ready. Tap Send to deliver it to +94775104591.
- To change the report number, search for `NOTIFY` near the top of the script in `index.html`.
