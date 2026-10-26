# Complete project — wearjd.pk
This is the complete version 3 project, not an update patch. Extract into a separate folder. Keep old versions as backups. Do not place this inside the old project.

## Preview
Open this folder in VS Code. Choose Terminal > New Terminal and run:

    python3 -m http.server 8000

Open http://localhost:8000. If that port is busy, use 8001 instead.

## GitHub first
1. Sign into https://github.com and create a repository named wearjd. Private is fine. Add a README to make uploading easier.
2. In the new repository choose Add file > Upload files.
3. Open the extracted wearjd folder and drag its CONTENTS, including the assets folder, into GitHub. Do not upload the ZIP. index.html must appear at the repository root, beside app.js, styles.css, products.js and vercel.json.
4. Commit changes. Use the new README in this folder if replacing the automatically generated one.

## Then Vercel
1. Sign into your existing account and choose Add New > Project.
2. Connect GitHub if needed and grant access to the wearjd repository.
3. Import wearjd.
4. Framework preset: Other. Root Directory: repository root. No install/build command; leave overrides disabled. If Output Directory must be specified, use a single dot (.).
5. Deploy. Vercel supplies the actual vercel.app URL. Future pushes to the connected production branch trigger deployments.
6. To attach wearjd.pk later, register it, then add it under project Settings > Domains and use the exact DNS records Vercel supplies.

## What changed
Forest-green/cream visual system, refined typography/spacing, clearer hero, matching-sets feature section, quieter category strip, improved product cards, size filtering, dynamic category titles and saved favourites. Desktop rendering and combined size/search filtering verified. JavaScript syntax passed. Mobile CSS is included; physical-device QA still recommended.

## Before customer orders
Product visuals and prices are still examples. Cart, search, sorting, favourites and size selection work. Checkout remains a labelled demo. Real orders require final products/prices, business contact or backend integration, delivery rates and policies. This download is not yet deployed and does not register the domain.

Official help:
https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository
https://vercel.com/docs/git
