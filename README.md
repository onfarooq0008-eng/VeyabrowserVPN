# Veya website (static)

Plain HTML/CSS — no build step. Upload the **contents** of this folder to the root of **fastvpnn.pp.ua**
(GitHub Pages, Cloudflare Pages, Netlify, or any web host).

## Public URLs to paste into Google Play Console
| Play Console field | URL |
|---|---|
| Privacy policy | https://fastvpnn.pp.ua/privacy-policy.html |
| Website | https://fastvpnn.pp.ua/ |
| Support email | admin@fastvpnn.pp.ua |
| Account / data deletion URL (Data safety) | https://fastvpnn.pp.ua/data-deletion.html |
| VPN disclosure (extra link, optional) | https://fastvpnn.pp.ua/vpn.html |
| Terms of use | https://fastvpnn.pp.ua/terms.html |

Note: the VPN backend already uses `api.fastvpnn.pp.ua`; this site lives on the root domain, so they don't clash.

## Before you publish — please check
1. **Server logging:** the pages say we do not use VPN data for ads/selling and that registration is removed on disconnect.
   If your VPN servers keep connection logs (even short-term), add that to `privacy-policy.html` §6 and `vpn.html`. Google checks that the policy matches reality.
2. **Governing law** in `terms.html` §12 is generic; add your country if you want.
3. **Google Play link** on the home page points to the listing for package `veyabrowser.vpn` — it works once the app is live.
4. **app-ads.txt:** Yandex Ads asks you to host `/app-ads.txt` at the root of your developer website. Copy the exact line(s) from your Yandex Partner (Ad network) dashboard into a file named `app-ads.txt` in this folder.
5. Dates: pages say "Last updated: November 15, 2026". Update them whenever you change a policy (edit the pages or re-run the generator).

## Files
index, features, vpn, privacy-policy, terms, data-deletion, permissions, support (FAQ), contact, about, licenses, 404,
style.css, sitemap.xml, robots.txt, assets/ (icons & logo).
