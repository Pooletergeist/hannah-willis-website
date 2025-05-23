change themes/zola-grayscale/templates/index.html to change landing page

make sure base_url matches the url youre deploying to for css
make sure config.toml variables are not the empty string or theyll be ignored
make sure you deploy to cloudflare build system 1 or it wont find zola, even if u select the framework
