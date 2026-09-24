<p align="center">
  <a href="https://focale-editor.app">
    <img
      src="https://raw.githubusercontent.com/focale-editor/website/main/public/images/social/og-image.png"
      alt="Focale — an advanced image editor that runs entirely on your machine"
      width="100%"
    >
  </a>
</p>

<p align="center">
  <a href="https://focale-editor.app">
    <img src="https://img.shields.io/badge/Website-focale--editor.app-007cf9?style=flat-square" alt="Focale website">
  </a>
  <a href="https://focale-editor.app/#newsletter">
    <img src="https://img.shields.io/badge/Status-alpha_coming_soon-181f33?style=flat-square" alt="Alpha coming soon">
  </a>
  <a href="https://pub.dev/publishers/focale-editor.app/packages">
    <img src="https://img.shields.io/badge/Packages-pub.dev-007cf9?style=flat-square&amp;logo=dart&amp;logoColor=white" alt="Focale packages on pub.dev">
  </a>
</p>

<p align="center">
  <strong>A modern, local-first raster image editor for Linux, Windows and macOS.</strong>
  <br>
  Layers, masks, non-destructive adjustments, filters and layer effects — without sending your work anywhere.
</p>

## A serious editor, without the cloud

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>Local by design</h3>
      <p>Your documents stay on your disk. Focale opens, edits and saves them locally — no upload required.</p>
    </td>
    <td width="33%" valign="top">
      <h3>Built for real work</h3>
      <p>Layers and groups, masks, blend modes, re-editable adjustments, filters and a complete layer-effects stack.</p>
    </td>
    <td width="33%" valign="top">
      <h3>At home everywhere</h3>
      <p>One editor across Linux, Windows and macOS, with support for the Photoshop files and presets you already own.</p>
    </td>
  </tr>
</table>

## Familiar where it matters

Focale keeps the workspace experienced editors already know — document tabs, a full tool rail, a precise canvas, and dockable panels for layers, channels, paths, history and swatches.

<p align="center">
  <a href="https://focale-editor.app/#preview">
    <img
      src="https://raw.githubusercontent.com/focale-editor/website/main/public/images/screenshot.webp"
      alt="A development build of Focale showing an aurora photograph on the canvas"
      width="100%"
    >
  </a>
  <br>
  <sub>Preview from a development build — the interface is still evolving.</sub>
</p>

## The open-source foundation

The editor is still in active development. Meanwhile, the focused libraries that power its formats, color management, imaging algorithms, creative input and platform integration are already developed in the open.

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><code>01</code>&nbsp; Formats &amp; codecs</h3>
      <p>
        <a href="https://github.com/focale-editor/imcodec"><strong>imcodec</strong></a><br>
        <sub>Focused codecs for BMP, GIF, JPEG, JPEG XL, OpenEXR, PNG, QOI, TGA, TIFF and WebP.</sub>
      </p>
      <p>
        <a href="https://github.com/focale-editor/imcodec-native"><strong>imcodec-native</strong></a><br>
        <sub>Optional AVIF, HEIF/HEIC, JPEG XL and WebP codecs backed by bundled native and WebAssembly engines.</sub>
      </p>
      <p>
        <a href="https://github.com/focale-editor/animcodec"><strong>animcodec</strong></a><br>
        <sub>Animated raster codecs built on imcodec for editable frame sequences.</sub>
      </p>
      <p>
        <a href="https://github.com/focale-editor/rawkit"><strong>rawkit</strong></a><br>
        <sub>A reusable Dart SDK for importing and developing camera RAW images.</sub>
      </p>
      <p>
        <a href="https://github.com/focale-editor/zcodec"><strong>zcodec</strong></a><br>
        <sub>Dependency-free DEFLATE, zlib, GZIP, TAR and ZIP codecs in pure Dart.</sub>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3><code>02</code>&nbsp; Photoshop ecosystem</h3>
      <p>
        <a href="https://github.com/focale-editor/psdkit"><strong>psdkit</strong></a><br>
        <sub>A pure Dart PSD and PSB reader and writer.</sub>
      </p>
      <p>
        <a href="https://github.com/focale-editor/pscore"><strong>pscore</strong></a><br>
        <sub>Shared binary, descriptor, PackBits and pattern codecs.</sub>
      </p>
      <p>
        <a href="https://github.com/focale-editor/abrkit"><strong>abrkit</strong></a>
        · <a href="https://github.com/focale-editor/cshkit"><strong>cshkit</strong></a>
        · <a href="https://github.com/focale-editor/patkit"><strong>patkit</strong></a>
        · <a href="https://github.com/focale-editor/acvkit"><strong>acvkit</strong></a>
        · <a href="https://github.com/focale-editor/aslkit"><strong>aslkit</strong></a>
        · <a href="https://github.com/focale-editor/atnkit"><strong>atnkit</strong></a><br>
        <sub>Codecs for Photoshop brush, custom-shape, pattern, curve, layer-style and action-set files.</sub>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><code>03</code>&nbsp; Imaging tools</h3>
      <p>
        <a href="https://github.com/focale-editor/panoramerge"><strong>panoramerge</strong></a><br>
        <sub>Pure Dart panorama registration, seam finding and multiband blending for RGB and CMYK rasters.</sub>
      </p>
      <p>
        <a href="https://github.com/focale-editor/dartface"><strong>dartface</strong></a><br>
        <sub>Offline frontal-face detection with image decoding and no machine-learning runtime.</sub>
      </p>
      <p>
        <a href="https://github.com/focale-editor/chromalib"><strong>chromalib</strong></a><br>
        <sub>Fast, typed ICC color transforms for Dart, powered by Little CMS.</sub>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3><code>04</code>&nbsp; Creative input &amp; platform</h3>
      <p>
        <a href="https://github.com/focale-editor/stylet"><strong>stylet</strong></a><br>
        <sub>Cross-platform Flutter stylus input with pressure, tilt, barrel rotation, hover, buttons, double-tap and squeeze.</sub>
      </p>
      <p>
        <a href="https://github.com/focale-editor/imclipboard"><strong>imclipboard</strong></a><br>
        <sub>Read and write PNG images through the system clipboard across Flutter desktop, mobile and web.</sub>
      </p>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://pub.dev/publishers/focale-editor.app/packages"><strong>Explore every package on pub.dev&nbsp; →</strong></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/focale-editor/website"><strong>View the website source&nbsp; →</strong></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/orgs/focale-editor/repositories"><strong>Browse all repositories&nbsp; →</strong></a>
</p>

---

<p align="center">
  <strong>Be there for the first alpha.</strong><br>
  <sub>One email when the first downloadable build is ready — nothing in between.</sub><br><br>
  <a href="https://focale-editor.app/#newsletter">Get notified</a>
  &nbsp;·&nbsp;
  <a href="https://focale-editor.app/#roadmap">See the roadmap</a>
  &nbsp;·&nbsp;
  <a href="mailto:contact@focale-editor.app">Contact us</a>
</p>

<p align="center">
  <sub>Made in Europe · Built for Linux, Windows and macOS</sub>
</p>
