# VeriPath Africa — Landing Page

Static site (no build step) for veripath.co.ke. Deploys to Truehost.
Separate from VeriPath-core (the Streamlit app on Railway/Streamlit Cloud).

## Still to do before launch
1. Photos — swap the two dashed placeholder boxes in index.html for real images
   (Crops: packhouse/export produce. Livestock: herder/animals in the field.)
   Source from unsplash.com or pexels.com, save into assets/images/.
2. WhatsApp number — replace 254XXXXXXXXX in the floating button link in index.html.

## Deploying to Truehost
1. cPanel or DNS Manager → File Manager → public_html/
2. Upload index.html and the assets/ folder directly into public_html/
3. Visit veripath.co.ke to confirm

## Connecting app.veripath.co.ke
DNS Manager → add CNAME record, host "app", pointing to your Streamlit/Railway app's domain.
