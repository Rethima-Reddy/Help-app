# HELP website
This page will help the client to understand litle code and adjust the changes required futher.

The following are the few examples to where the cilent can understand the code.

## Replacing Images:
In general all the images are included in the ```<img>``` tag which have many attribute to beutify the image. Initially The required image should be added to the image folder, this will allow us to use the image in any place required. Search the location where to re-place the image and see the <img> tag with attribute "src" which we have to set to new image name and let the remaining be unchaged. The tag after changing may appear as following.

```<img src="image/6900_Communicator.jpg">```

## Adding new image:
In the same way as above process we have to add the image to the image folder and then add ```<img>``` tag with the attribute src which is set to the new image.

## Updating CDN Style Links
To update the CDN links we have to change the ```href``` value in the ```link``` tag inside the head tag 
``` <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">```
and then find the appropriate script tag at the bottom of the page.
```<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"> </script>```

## Group-02 Section-02
#### Akhitha Tumula
#### Rohan Bhandari 
#### Rethimareddy Polam
#### Mahender Reddy Surkanti


## References
As we liked the webpage designed by group-01 we took the reference of it to begin our webpage.
