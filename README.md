# No Agenda Art Resizer

A simple S3 backed JS file uploader.

 * Uploaded file invokes lambda
 * Lambda processes images and converts them
 * Newly resized images available for download in two formats
  - 3000x3000 72dpi JPEG
  - 256x256 72dpi JPEG

Images will be inaccordance with the [Apple RSS tags for Podcasts Connect](http://help.apple.com/itc/podcasts_connect/#/itcb54353390) standards that exceed the standard RSS 2.0 [image tag specifications](https://cyber.harvard.edu/rss/rss.html#ltimagegtSubelementOfLtchannelgt):

 * minimum size of 1400 x 1400 pixels and a maximum size of 3000 x 3000 pixels
 * in JPEG or PNG format
 * 72 dpi
 * with appropriate file extensions (.jpg, .png)
 * in the RGB colorspace
 