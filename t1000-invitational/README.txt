Unzip. Upload the contents (index.html, img folder, wrangler.toml) to the ROOT of your GitHub repo.

Do not upload this zip as a single file. Do not put them in a nested folder.

Cloudflare Pages: leave the build command blank. Root / output directory: /
Workers: keep wrangler.toml; deploy command can stay npx wrangler deploy.

The file MUST be named index.html (not "index (10).html").
