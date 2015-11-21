# Social Meta Plugin for [Morfy CMS](http://morfy.org/)

![version](https://img.shields.io/badge/version-1.0.0-brightgreen.svg?style=flat-square "Version")
![DLE](https://img.shields.io/badge/Morfy-2.x-green.svg?style=flat-square "Morfy Version")
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://github.com/pafnuty/morfy-plugin-socialmeta/blob/master/LICENSE)

The plugin to automatically generate social metatags.



## Advantages
- Easy use.
- Automatic generation resized images for twitter and facebook.
- Automatic generation and truncate of the description page.


## Install
Copy the content of folder `upload` in the root of the site.

## Configuration
- See step 2 and 3 in [this instruction](http://morfy.org/documentation/plugins/plugins-installation)
- Open `base.tpl` and modify `<head>` tag:
```html
<head prefix="og: http://ogp.me/ns#" xmlns:fb="http://ogp.me/ns/fb#">
```
- Open `/plugins/socialmeta/socialmeta.yml` and configure the settings.

### Custom images in pages
If you want to specify a particular page to image, use variables `og_image` and `twitter_image` in `.md` files.
```markdown
og_image: /my_folder/my_super_nice_image_for_facebook.png
twitter_image: /my_folder/my_super_nice_image_for_facebook.png
```



## Use
- Chek the page in [Twitter Card Validator](https://cards-dev.twitter.com/validator)
- Chek the page in [Facebook OG Debugger](https://developers.facebook.com/tools/debug/og/object/)


## License 
[MIT](https://github.com/pafnuty/morfy-less/blob/master/LICENSE)