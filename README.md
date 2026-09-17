# Rule34.xxx Link Extractor — Converter & Downloader

A simple way to extract, convert, and batch download images and videos from Rule34.xxx.

The project combines the **R34 Link Extractor Chrome Extension** with the **S8Utility URL Converter** to turn thumbnail URLs into corrected media URLs that can be downloaded in bulk.

> **Browser support:** Google Chrome and Chromium-based browsers such as Microsoft Edge.

---

## 🚀 How It Works

The process is split into three parts:

**Extract → Convert → Download**

### 1. Install the R34 Link Extractor

Download the **R34 Link Extractor** Chrome Extension and install it in your browser.

The extension is compatible with:

* Google Chrome
* Microsoft Edge
* Other Chromium-based browsers

---

### 2. Browse Rule34.xxx

Open Rule34.xxx and browse to a gallery/results page containing multiple media posts.

For best results, use the standard **6×7 gallery grid**.

---

### 3. Scan the Current Page

Click the **R34 Link Extractor** icon in your browser toolbar.

Then click:

`Scan current page`

The extension scans the gallery and extracts the thumbnail URLs belonging to the Rule34.xxx media posts on the current page.

It separates the detected media into:

* 🖼️ Images
* 🎬 Videos

The scanner is designed to target gallery media rather than unrelated page assets such as advertisements.

---

## 🔗 Convert the Extracted URLs

Once the scan is complete, copy the extracted URLs from the extension.

Open the S8Utility R34 Image & Video Downloader:

**https://s8utility.com/tools/rule34-xxx-downloader**

Paste the URLs into the input box and click:

`Build previews`

The converter will process the URLs and display a preview for each detected media item.

---

## 🔄 Fix Invalid Preview URLs

Some thumbnail URLs may not immediately resolve to the correct full media URL.

If this happens, the converter will mark them as invalid.

Click:

`↻ Try next URL for all invalid previews`

The converter will automatically modify the URL structure and try alternative supported paths and file formats.

Keep clicking **Try next URL for all invalid previews** until:

`Invalid previews: 0`

When everything has been successfully resolved, you'll see:

`✓ All previews valid`

---

## 📋 Export the Corrected URLs

Once your media URLs have been resolved, click:

`Copy corrected preview URLs`

The final working URLs will be copied to your clipboard.

These are the corrected media URLs rather than the original thumbnail URLs.

---

## ⬇️ Batch Download Images & Videos

Open the **R34 Link Extractor** extension again.

Click the button in the top-right corner:

`⬇ Download corrected URLs`

Scroll down to the **Download corrected URLs** section.

You'll see:

> Paste the final corrected URLs from the preview page, one per line.

Paste the corrected URLs you copied from the converter.

Then click:

`⬇ Download all pasted files`

The extension will begin processing the URLs and downloading the images and videos.

The downloader also displays statistics for the current batch, including successful and failed download requests.

---

## ❌ Excluding Media From a Download

Don't want a particular image or video included in your batch?

Before exporting the corrected URLs, find the unwanted media preview and click the **red × button** in the top-right corner of its preview card.

That media item will be removed from the current batch.

Its URL will therefore not be included when you copy or export the corrected URLs.

---

## 💡 Recommended Workflow

```text
Rule34.xxx Gallery
        ↓
R34 Link Extractor
        ↓
Scan Current Page
        ↓
Copy Extracted URLs
        ↓
S8Utility URL Converter
        ↓
Build Previews
        ↓
Resolve Invalid Previews
        ↓
Copy Corrected URLs
        ↓
R34 Link Extractor
        ↓
Download Corrected URLs
        ↓
Download All Pasted Files
```

---

## ⚠️ Notes

* The scanner processes the currently viewed gallery page.
* Some media may require several URL fallback attempts before a valid preview is found.
* Do not export immediately if you want every image URL resolved first. Continue retrying until the invalid preview counter reaches **0**.
* You can remove unwanted media from the batch before exporting.
* Availability of individual files depends on the third-party media host.
* Only download or use content you are legally permitted to access and save.

---

## 🛠️ Project Components

### R34 Link Extractor

Chrome/Edge extension used to:

* Scan the current gallery page
* Detect image and video thumbnails
* Copy extracted URLs
* Accept corrected media URLs
* Batch-download corrected images and videos
* Display download statistics

### R34 Image & Video Downloader

Web-based URL converter used to:

* Parse extracted thumbnail URLs
* Separate images and videos
* Generate media URLs
* Preview images
* Try alternative image paths and extensions
* Identify invalid previews
* Remove unwanted media
* Copy corrected URLs
* Export corrected URLs to a text file

---

## 🌐 URL Converter

**S8Utility R34 Image & Video Downloader**

https://s8utility.com/tools/rule34-xxx-downloader

---

## 💬 Questions, Bugs & Suggestions

Have a question, found a bug, or have an idea for improving the project?

Visit:

**https://s8utility.com/**

Or contact:

**[contact@s8utility.com](mailto:contact@s8utility.com)**

---

## 📄 Disclaimer

This project is an independent browser utility and is not affiliated with, endorsed by, or sponsored by Rule34.xxx or its operators.

Third-party media remains subject to the rights of its respective owners and the terms and policies of the services hosting that content.

Users are responsible for ensuring that their use of this utility and any downloaded content complies with applicable laws, third-party terms, and content-owner rights.

---

**R34 Link Extractor — v1.0.0**

Project by **S8Utility**
