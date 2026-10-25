NINE REALMS SAGA — CHARACTERS PAGE ADD-ON

FILES
- characters.html: replacement Characters page with clickable portraits, story popups, filters and NFT collectible messaging.
- nine-realms-collection.png: cinematic banner image.

INSTALL
1. Open the existing characters.html in GitHub and replace its entire contents with the characters.html in this package. Commit changes.
2. Upload nine-realms-collection.png into the repository ROOT, beside index.html and characters.html.
3. Check the existing portrait files are in the root (odin.webp, thor.webp, freya.webp, skadi.webp, loki.webp, frigg.webp, baldr.webp, heimdall.webp, njord.webp, idunn.webp, sif.webp, bragi.webp, hodr.webp, ullr.webp, eir.webp, forseti.webp). Cards still work without a portrait, but the image will be blank.
4. Both upper and lower Characters links on the homepage must use href="characters.html". For text links/buttons, use <a href="characters.html">CHARACTERS</a>.
   If your homepage is a single flat image with words embedded in the image, those words are not separate clickable links; actual HTML links must be added over/around the image.

IMPORTANT
This is a static prototype. The character cards and story popups work without a backend. Actual NFT minting, wallet connection, metadata, ownership checks and paid/unlocked content are not implemented yet. NFT ownership rights/benefits should be defined in official collection terms.
