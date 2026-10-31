Precious Metals USA – Landing Page
A simple one-page landing site for a gem and precious metal appraiser. It shows images of precious metals and gemstones and a single contact email: contact@preciousmetalsusa.com.
Project structure
```
index.html          The landing page (HTML and CSS in one file)
images/
  gold-bars.jpg       Hero image
  silver-bullion.jpg
  diamond.jpg
  gold-nuggets.jpg
  ruby.jpg
  emerald.jpg
  sapphire.jpg
README.md           This file
```
View locally
Double-click `index.html`. It needs no build step and no internet connection. Keep the `images` folder next to it.
Update the site
Change an image: replace the file in `images/` with a new one that has the same filename.
Change layout or colours: edit `index.html`. The colours are defined at the top of the file under `:root`.
Change the email: edit the `mailto:` link in the footer of `index.html`.
Publish with GitHub Pages
Make sure `index.html` and `images/` are at the top level of the repository.
Go to Settings → Pages.
Set Source to Deploy from a branch, then choose branch `main` and folder `/ (root)`, and click Save.
After a minute or two, the site is live at `https://<username>.github.io/<repository>/`.
To update the live site, upload the changed files to the repository (Add file → Upload files → Commit changes). The same link shows the new version after about a minute.
Image notes
Keep each photo under about 2 MB so the page loads quickly.
Use images you have the right to publish, such as Unsplash or Pexels photos.
Filenames must match the list above. The page tries other common extensions (`.jpeg`, `.png`, `.webp`) if `.jpg` is missing.
