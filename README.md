# Product Page Swipe File

Full-page clones of high-converting product pages for reference when building new ones. Mirrors the [advertorial-swipes](https://github.com/primalconversions/advertorial-swipes), [listicle-swipes](https://github.com/primalconversions/listicle-swipes), and [quiz-swipes](https://github.com/primalconversions/quiz-swipes) setup.

**Live site (once swipes are added):** https://primalconversions.github.io/product-page-swipes/

## Status

Empty scaffold — drop URLs into `urls.txt` and run the pipeline.

## Adding swipes

```bash
# 1. Append URLs to urls.txt (one per line)
# 2. Clone only new URLs (skips already-cloned)
python3 clone_new.py

# 3. If any clone is >50MB, shrink its images
python3 shrink_images.py swipes/<slug>/index.html

# 4. Strip embedded FB tokens / API keys
python3 scrub_secrets.py

# 5. Rebuild README index
python3 build_readme.py

# 6. Push
git add -A && git commit -m "Add N product page clones" && git push
```

## Requirements

```bash
brew install monolith
python3 -m pip install --user Pillow
```
