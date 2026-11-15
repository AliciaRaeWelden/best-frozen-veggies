# Publishing a recipe to Best Frozen Veggies

This is a lightweight personal kitchen notebook, not a standardized cookbook. A recipe can be published after one test, provided that uncertainty is clearly labeled.

## The easy workflow

1. **Cook.** Take a photo if you feel like it. Don't interrupt cooking to measure everything.
2. **Record what happened.** Copy the short template below into a ChatGPT message, filling in whatever you remember. Missing measurements are fine.
3. **Choose a name and card art.** Make or select a **full PNG or JPG** illustration. Keep the original image, rather than replacing it with a vector approximation.
4. **Publish.** Ask ChatGPT to add the recipe to the existing flip-through Recipe Box in `index.html`, preserving all previous cards, details, and navigation. If the image cannot be uploaded through the GitHub connector, upload it to the repository root first.
5. **Verify.** Open the live site, refresh after GitHub Pages deploys, and check both the thumbnail and enlarged card. Make sure the image is not cropped.

## Copy/paste recipe intake

**Working name:**

**What I made:**

**Ingredients (approximate is fine):**

**What I did (in order):**

**What worked:**

**What I'd change next time:**

**Test count:** 1

**Card artwork:** attached / already uploaded as `filename.png` / not yet made

You do not have to fill in every field. ChatGPT can ask only for essential missing details.

## Publish request to ChatGPT

> Publish this as a new card in my Best Frozen Veggies recipe box. Use the full PNG/JPG illustration, not an SVG replacement. Keep the existing recipes and flip-through behavior. Label estimates and recipes tested once. Check the actual image filename in GitHub, update the image reference in index.html, and make sure the card uses object-fit: contain so the art is not cropped. Tell me what you changed and what remains unverified.

## Image conventions

- Use descriptive lowercase hyphenated names: `recipe-name-card.png`.
- Upload the **actual** PNG or JPG to the repository; do not rename an SVG to PNG.
- Prefer one full illustration per recipe; the same image is used for the thumbnail and popup.
- The recipe box reads the card image source from each tile in `index.html`.
- Use `object-fit: contain` for full-art cards; the default site's `cover` setting crops artwork.
- If an old image persists, check that the file exists, the HTML points to it, and GitHub Pages has deployed before assuming the upload failed.

## Publishing standard

Keep the voice playful and the claims modest. Record a useful technique or observation. Don't invent exact quantities, cooking times, or repeatability. Recipes tested once should say so. The next experiment can revise the existing card rather than requiring a brand-new one.
