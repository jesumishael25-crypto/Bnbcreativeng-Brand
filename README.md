# BNBCREATIVENG Portfolio Website

**Tagline:** HOME OF COMPLETE OUTFITS  
**Brand colours:** Navy `#00123B`, wine `#5A1028`, ivory `#FAF7F2`, champagne gold `#C6A56B`.

A responsive, static portfolio website for BNBCREATIVENG. It is designed to be edited directly in GitHub and published free with GitHub Pages. It is a portfolio/contact website, **not** an online shop: there is no cart, checkout, or payment processing.

## Files and where to edit

- `index.html` — page content, navigation, service cards, gallery entries, contact details and page text.
- `assets/css/style.css` — colours, typography, layout, spacing, responsive/mobile styles and animations.
- `assets/js/main.js` — mobile navigation, portfolio filters, image lightbox and WhatsApp enquiry form.
- `assets/images/` — add your own product and brand photos here.

## Publish with GitHub Pages

1. Sign in to [GitHub](https://github.com/) and create a new repository, for example `bnbcreativeng-website`.
2. Upload the **contents** of this folder to the repository root. Ensure `index.html` is at the root, not inside another nested folder.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then save.
6. Wait for the Pages deployment to finish. GitHub will show the public website URL on the Pages settings screen.

The included `.github/workflows/pages.yml` also provides a GitHub Actions deployment workflow. If you use this workflow, go to **Settings → Pages** and set the source to **GitHub Actions** instead of **Deploy from a branch**.

## How to edit later

1. Open the file in your GitHub repository (`index.html`, `assets/css/style.css`, or `assets/js/main.js`).
2. Click the pencil **Edit** icon.
3. Make your changes, preview if available, then click **Commit changes**.
4. GitHub Pages redeploys the site after the commit. It may take a short time for changes to appear.

You can also clone the repository and edit the files in Visual Studio Code.

## Replace the temporary photos

The site currently uses remote stock/inspiration photos. Replace them with actual BNBCREATIVENG images before representing the gallery as the brand's work. Upload image files into `assets/images/`, then update image `src` values in `index.html` and the hero/delivery background URLs in `assets/css/style.css`. Keep the images optimized for the web (usually WebP or JPG, sized appropriately).

## Contact settings to verify

The WhatsApp and telephone links use `+2348032310582` based on the contact number provided. Test this number and the enquiry form before publishing. The form opens WhatsApp with a prepared message; it does not save form submissions or send email. No email address or social media URLs have been invented.

## Domain

To use `bnbcreativeng.com`, first publish the site, then configure the custom domain under **Settings → Pages** and follow GitHub's DNS instructions for your domain registrar. DNS changes can take time to propagate.

## Notes

- Uses plain HTML, CSS and JavaScript; no build tools or paid dependencies are required.
- Google Fonts and the current remote photos need an internet connection.
- Check the mobile layout and test all links after editing.
