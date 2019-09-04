# oculante
A no-nonsense image viewer

I started this as a toy project to make a simple image viewer. Here are the features:

Image format support:
- bmp	
- dxt	
- gif (No animation support)	
- hdr	
- ico	
- jpeg	
- png	
- pnm	
- tga	
- tiff	
- webp	
- DDS (DXT1-5, via dds-rs)

Platform support:
- Linux
- Mac
- Windows

Misc
- Threaded image loading

Planned:
- Custom display for images with unassociated channels
- Image rotation (and read EXIF for that)
- Investigate PVR / ETC support
- SVG support
- Brighness/gamma adjust for HDR
[![Build Status](https://travis-ci.org/woelper/oculante.svg?branch=master)](https://travis-ci.org/woelper/oculante)