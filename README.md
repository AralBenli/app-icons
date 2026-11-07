# app-icons

Store icons for the developer's apps, served at a fixed address for the `house_ads` Remote Config
list (the `:crosspromo` house-ad module):

`https://raw.githubusercontent.com/AralBenli/app-icons/main/icons/<app id>.png`

- One PNG per app, named after its `id` in `house_ads`, 256×256.
- To change an icon, replace the file and push. The address stays the same, so `house_ads` doesn't
  change. Apps keep icons in memory only, so the new one shows on the next launch (GitHub caches raw
  files for about 5 minutes).
