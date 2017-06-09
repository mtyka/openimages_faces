# OpenImages: Faces

[OpenImages](https://github.com/mtyka/openimages_faces) is a large database of [CC 2.0](https://creativecommons.org/licenses/by/2.0/) Images hosted by Flickr.
This repository is home to some subsets that specifically show faces. 


  * openimages_faces_raw_urls.list is the raw list based on the OpenImages "[face](http://openimages.oldjpg.com/word_id/6906)" label (label 6906).
  * openimages_faces.cropped_wide.csv is processed using a Haar cascade to detect (relatively) frontally oriented faces with some minimal margin around (to include hair and neck). The columns indicate the image url, the x, y coordinates of the crop box and its size in x,y.


This was done pretty roughly and can undoubtedly be improved opon. If you generate other filterings please feel free to send a pull request and add them here. Many of the images are for example non-photographic, i.e. depict drawings or cartoons.


DISCLAIMER: Like OpenImages, I don't make any guarantees about the license of the images themselves.
