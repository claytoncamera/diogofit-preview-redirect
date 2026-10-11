# diogofit-preview-redirect

Redirects the retired preview address `diogofit.loopholemaxing.com` to **https://diogofit.com**, keeping the path, so links already sent to Diogo for review keep working.

- One page (`index.html`, copied to `404.html` so every path redirects). No tracking, no content.
- Safe to delete once nobody is using the old link. When it goes, also delete the `diogofit` CNAME record on loopholemaxing.com at GoDaddy.
- The site itself lives in `claytoncamera/diogo-fitness-site` (built files) and is built from the private Ascent-Vision repo.
