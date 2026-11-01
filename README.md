# SOHA Coffee & Tea

Static mobile-friendly website in Vietnamese, English, and Russian. Open `index.html` or upload all files and folders to GitHub Pages. No build or dependency installation is required.

For local development, run `python3 -m http.server 8000 --bind 127.0.0.1` from the repository directory.

- Edit drink names, translations, prices, sizes, and image paths in `menu-data.js`. Prices are in thousands of VND. Two-price items use **M / L**; latte, matcha, and cacao list **M** only.
- The photographed replacement menu contains 52 drink entries and 15 toppings. The kumquat/lemon black tea choices are separate entries. Milk tea includes black pearls.
- Product photos live in `assets/drinks/` and `assets/toppings/`. New generated photographs are illustrations based on menu names, using the existing SOHA image style.
- Replace the logo in `assets/logo/`.
- Edit links and phone in `index.html`.

Check JavaScript syntax with `node --check menu-data.js` and `node --check script.js`. In a browser, check the language switcher, all category tabs, M/L prices, and image loading.

Note: Verify that the Google Maps destination and Zalo account match the business.
