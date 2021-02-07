# Ricky Image Embedder

A tool to merge two images into one in such a way that different programs seem to display either one or the other.
Notably, when uploaded to discord, the preview only shows the master image, but when clicking on it or when opened in a browser, the embedded image appears.

Also called "ricky" because the original purpose was to embed Rickrolls into unsuspecting images, however it can be used with two images.

# Usage

To embed `rick.png` into `bait.png`:
```sh
python ricky.py embed bait.png rick.png totally_innocent_image.png
```

To extract an embedded image:
```sh
python ricky.py extract totally_innocent_image.png rick_extracted.png
```
