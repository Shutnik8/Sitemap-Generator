# 🗺️ Sitemap Generator

A VK-style mini app for quickly generating a valid `sitemap.xml` file. Designed for webmasters, developers, and SEO specialists who want a simple tool to create a sitemap without writing code manually.

## 🚀 Features

- Add unlimited URLs
- Specify:
  - Page **priority**
  - **Change frequency**
  - **Last modification** date
- Generate a valid XML Sitemap
- One-click download of the sitemap
- Mobile-friendly, works inside **VK Mini Apps**

## 📸 UI

The interface is styled like VKontakte, clean and responsive for both desktop and mobile devices.

## 🧰 Technologies Used

- **HTML5 / CSS3**
- **Vanilla JavaScript**
- **VK Bridge** (for VK Mini App integration)

## 📄 Sitemap Format

Each entry in the generated sitemap includes:

- `<loc>` — the page URL
- `<priority>` — page priority (from `0.0` to `1.0`)
- `<changefreq>` — update frequency (`daily`, `weekly`, `never`, etc.)
- `<lastmod>` — last modification date in `YYYY-MM-DD` format

## 🛠 How to Use

1. Enter a URL and its properties
2. Click **"Add URL"**
3. Repeat for all desired pages
4. Click **"Generate Sitemap"**
5. Click **"Download sitemap.xml"** to save the file

## 🔄 Reset

The **"Reset"** button clears all entered data and the generated output.


