# NAF4 Images (Raster versions)

This site contains raster versions of all images currently in use in NAF4.

As almost all images are originally vector versions, we should try avoid using raster images in NAF for a number of reasons

* They do not scale very well - when you zoom in the result is usually terrible.
* The size of the raster version are very large resulting in a bad user
  experience and a significant performance hit.
* We do not not want raster images in the main NAF4 Git repository (or as few as
  possible), since Git in general are not fond of binary files. A solution could
  be to use Git LFS.

So for now we keep the raster version of of the main NAF4 and gradually replace
them with SVG version, which we want to add to the repository. Hopefully we
will all be able to use SVG images for chapter 4 (The meta-model chapter), when
Enterprise Architect support export of models in SVG.


If we create a gh-pages branch and let it point to the master branch, this repository will automatically function as a website with images.

We we be able to refer to the images using the baseurl

http://stavnstrup.github.io/naf4-raster/introduction/

for images from chapter 1.
