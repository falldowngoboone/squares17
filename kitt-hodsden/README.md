# Responsive Images: Beyond Resizing
Kitt Hodsden

[All slides](https://kitt.hodsden.org/talks/squares-conference-2017)

First, understand how much content you have

Then, understand how fast the site currently is

* Web Dev Tools
* [www.webpagetest.org](https://www.webpagetest.org)
* [www.sitespeed.io](https://www.sitespeed.io)

**Look at time to first render**

Performance Budget

## How to improve performance
* Deliver less content
* Deliver content faster
* Render content faster

Images are a big portion (2/3 on average) of the size of websites

JPEG - least understood image format
Dave Newton Smashing Magazine article with ImageMagik (photo roll)
Google reduces JPEG file size by 35% article

photo: use JPEG and WEBP
vector format: use SVG
animated: use SVG, MP4, WEBM
PNG for everything else

*smallest file size wins

Responsive image techniques
* picture element
* srcset
* Picturefill
* image-set - srcset for CSS

## Let's do it!
ImageMagick
ImageOptim on Mac

## Infrastructure!
CDN

Don't do redirects

Make the entire site SSL

Cache images
* Last-Modified
* Etag
* Expires
* Max-Age

Domain Sharding

HTTP/2

## Rendering
Check slides

## Easy Wins

### Above the fold
* Embed images directly, don't put them in the CSS, e.g. background-image (um, I need to go check a few sites...)
* Load a tiny embedded image first, then replace with JS after the page has fully loaded

### Below the fold
* Lazy loading

## Conclusion
Always look at your site's data. Images may not be the largest portion of your site (the majority of cnn.com is JS, only a 10% savings if all images were optimized).