# JPEGView-Static - Statically Linked Image Viewer and Editor In Exactly One Executable

> Updated Jul 13 2023. Added file list for the latest release archive.

**[Download](https://github.com/annh9b/JPEGView-Static/releases/download/v1.2.45.0/JPEGView-Static-x64-v1.2.45.0.zip) the latest release right now!**

```
Archive:  JPEGView-Static-x64-v1.2.45.0.zip
  Length      Date    Time    Name
---------  ---------- -----   ----
        0  2023-06-17 02:36   JPEGView-Static-x64-v1.2.45.0/
  3418112  2023-06-17 02:36   JPEGView-Static-x64-v1.2.45.0/JPEGView-Static.exe
    31896  2023-06-14 03:40   JPEGView-Static-x64-v1.2.45.0/JPEGView.ini
    30531  2023-06-14 03:40   JPEGView-Static-x64-v1.2.45.0/JPEGView.ini.tpl
     3698  2023-06-14 03:40   JPEGView-Static-x64-v1.2.45.0/KeyMap.txt.default
     3995  2023-06-14 03:40   JPEGView-Static-x64-v1.2.45.0/symbols.km
---------                     -------
  3488232                     6 files
```

Second life for famous [JPEGView from SourceForge.net (last updated 2018-03-10, currently abandoned)](https://sourceforge.net/projects/jpegview/).

JPEGView-Static is a fast and tiny statically linked viewer for PC/Web Images and Camera Raw Formats with a minimalist GUI and base image editing
capabilities. The best replacement for default OS application to show pictures in various formats. Modified and compiled to fit
exactly in one executable. No installer, no collateral files, just copy-paste and run.

This fork incorporates changes not only from original [JPEGView from SourceForge.net](https://sourceforge.net/projects/jpegview/),
but also from [JPEGView at GitHub user sylikc](https://github.com/sylikc/jpegview).

![JPEGView-Static icon](favicon_large.png?raw=true)

> Updated Jun 16 2023. JPEGView-Static is the new project name and purpose: all the image viewing stuff needed
in exactly one statically linked executable.

## Full list of supported formats

### PC/Web Images

* Popular: JPEG, GIF
* Lossless: BMP, PNG, TIFF
* Web: WEBP

### Camera RAW formats

* Adobe (DNG)
* Canon (CRW, CR2)
* Nikon (NEF, NRW)
* Sony (ARW, SR2)
* Olympus (ORF)
* Panasonic (RW2)
* Fujifilm (RAF)
* Sigma (X3F)
* Pentax (PEF)
* Minolta (MRW)
* Kodak (KDC, DCR)

###  Windows Imaging Component (WIC)

Many additional formats are supported via Windows Imaging Component (WIC) that is statically linked into viewer executable as well.

### Temporarily disabled formats

* XL, HEIF/HEIC, AVIF
* TGA, WDP, HDP, JXR

## Basic Image Editor

Basic on-the-fly image processing is provided - allowing adjusting typical parameters:

* Sharpness
* Color Balance
* Rotation
* Perspective
* Brightness/Contrast
* Local Under-Exposure/Over-Exposure

## Other Features

* Small and fast, uses AVX2/SSE2 and up to 4 CPU cores
* High quality resampling filter, preserving sharpness of images
* Basic image processing tools can be applied realtime during viewing
* Movie/Slideshow mode - to play folder of JPEGs as movie

### New Features

* Added support for ICC Color Profiles embedded in WebP, JPEG XL images.

## Localization

* DISABLED. We consider JPEGView-Static as a professional app, so English only.

Also this approach makes all the GUI/Help terms to be named in an unified way.

## System Requirements

* Only 64-bit version is supported to avoid legacy garbage: Windows 7/8/10/11 64-bit or later

## Collaboration with [Second Life Metaverse](https://en.wikipedia.org/wiki/Second_Life)

JPEGView-Static appears to be extremely useful in converting [WebP](https://en.wikipedia.org/wiki/WebP) files to jpg images
since JPEGView-Static incorporates a [Google's WebP library](https://chromium.googlesource.com/webm/libwebp).
By default, JPEGView-Static saves high quality yet relatively small jpg images, using [Turbo JPEG library](https://libjpeg-turbo.org).

JPEGView-Static was [used](https://secondlife.com/destination/metaverse-city) to convert Second Life Metaverse
[avatars](https://www.pcgamer.com/second-life-metaverse-interview/) and [screenshots](https://mitsloan.mit.edu/ideas-made-to-matter/what-second-life-and-roblox-can-teach-us-about-metaverse)
into jpg file format. Below are few examples of how easily that can be achieved.

* JPEGView-Static: Metaverse City is a welcoming roleplay community aimed towards newcomers and veterans alike

![JPEGView-Static: Metaverse City is a welcoming roleplay community aimed towards newcomers and veterans alike](screenshots/JpegView-SL-1.jpg?raw=true)
