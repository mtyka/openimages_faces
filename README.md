# OpenImages: Faces

[OpenImages](https://github.com/mtyka/openimages_faces) is a large database of [CC 2.0](https://creativecommons.org/licenses/by/2.0/) Images hosted by Flickr.
This repository is home to some subsets that specifically show faces. 


  * openimages_faces_raw_urls.list is the raw list based on the OpenImages "[face](http://openimages.oldjpg.com/word_id/6906)" label (label 6906).
  * openimages_faces.cropped_narrow.csv is processed using a Haar cascade to detect (relatively) frontally oriented faces. The columns indicate the image url, the x, y coordinates of the crop box and its size in x,y. Only crop boxes are included that have at least an additional  5% boudary (i.e. not too close to the image border).
  * openimages_faces.cropped_wide.csv likewise, but boundary must be 25% in y and 15% in x, and thus contains fewer images.

This was done pretty roughly and can undoubtedly be improved opon. If you generate other filterings please feel free to send a pull request and add them here. Many of the images are for example non-photographic, i.e. depict drawings or cartoons.


DISCLAIMER: Like OpenImages, I don't make any guarantees about the license of the images themselves.
