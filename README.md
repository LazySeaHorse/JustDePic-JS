# Just De Pic JS

A fully in-browser, pure HTML (well, mostly!) version of my Python image metadata remover [Just De Pic](https://github.com/LazySeaHorse/Just-De-Pic). With a clean, modern UI inspired by [shadcn/ui](https://ui.shadcn.com/), this tool lets you strip metadata from your images—right in your browser, with no data ever leaving your device.

<table>
  <tr>
    <td align="center">
      <img src="https://i.postimg.cc/rwGgB83t/6hydtgfd.png" alt="Image 1" width="300"/>
    </td>
    <td align="center">
      <img src="https://i.postimg.cc/FK9GmMXC/fthnjtcfyhgjv.png" alt="Image 2" width="300"/>
    </td>
  </tr>
</table>


## ✨ Features

- **100% In-Browser:** All processing happens locally in your browser.
- **Batch Processing:** Remove metadata from one or many images at once.
- **Modern UI:** Inspired by shadcn/ui, built with Tailwind CSS.
- **Privacy First:** Your images never leave your device.
- **No Install Needed:** Just open the web page and go.

## 🚀 Try It Out

Check it out live on [GitHub Pages](https://lazyseahorse.github.io/JustDePic-JS/)  
*(Requires internet to load Tailwind CSS, but all image processing is done on your device.)*

## 🖼️ How to Use

1. **Open the app** in your browser.
2. **Import an image** drag n' drop, or click to browse.
3. **Review and edit** metadata for each image, or process in batch.
4. **Download** your cleaned images (or a ZIP for batch mode).

## Limitations

- Supported file formats: JPEG, PNG, HEIC, WEBP
- You can only edit _some_ metadata
- Only EXIF data is removed for JPEG files

## 🛠️ Tech Stack

- **HTML + JavaScript** (no frameworks)
- [Tailwind CSS](https://tailwindcss.com/) (via CDN)
- [piexifjs](https://github.com/hMatoba/piexifjs) for EXIF manipulation
- [exifr](https://github.com/MikeKovarik/exifr) for metadata reading
- [JSZip](https://stuk.github.io/jszip/) for batch ZIP downloads

## ⚡ Credits

- Built with help from [Cursor](https://www.cursor.so/) and [Context7](https://context7.com/)
- UI inspired by [shadcn/ui](https://ui.shadcn.com/)
