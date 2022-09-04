# Hugo Multiverse Theme (tuned)

**Hugo Multiverse** *tuned* is a theme based on [aerohub's](https://github.com/aerohub)
port of [HTML5 UP's theme](https://html5up.net/multiverse) of the same name.

We wanted to adjust the theme to allow control of image files via a data "images.toml" to provide 
additional descriptions of the images and define an order of images displayed.

## Installation

Create a new hugo site

```
hugo new site mytest
```

Now, clone the theme to your hugo site:

```
git clone https://github.com/rebelmc/hugo-multiverse-tuned themes/hugo-multiverse-tuned
```

Finally, copy the contents of the exampleSite directory to the root directory of your hugo site.

Please take also care, that the template is set in config.toml (maybe yo had to overwrite the existing file).

```
theme = "hugo-multiverse-tuned"
```
