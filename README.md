# Source Code Pro

Source Code Pro is a set of OpenType fonts that have been designed to work well
in user interface (UI) environments. In addition to a functional OpenType font, this open
source project provides all of the source files that were used to build this OpenType font
by using the AFDKO makeotf tool.

## Font installation instructions

### Clone with git

```sh
cd styles/fonts
git clone https://github.com/barberboy/source-code-pro
```

```html
<link rel="stylesheet" href="/styles/fonts/source-code-pro/source-code-pro.css">
```


### Download

Download and unpack the [.zip archive](https://github.com/barberboy/source-code-pro/archive/master.zip):

```sh
cd styles/fonts
wget https://github.com/barberboy/source-code-pro/archive/master.zip
unzip master.zip
mv source-code-pro-master source-code-pro
rm master.zip
```

```html
<link rel="stylesheet" href="/styles/fonts/source-code-pro/source-code-pro.css">
```


### Bower

```sh
bower install barberboy/source-code-pro
```

```html
<link rel="stylesheet" href="/bower_components/source-code-pro/source-code-pro.css">
```

If you’d like bower to put it in a different directory, just create a
[`.bowerrc`](http://bower.io/docs/config/) file and specify the
[`directory`](http://bower.io/docs/config/#directory) location:

```json
{
  "directory": "app/public",
  "analytics": false
}
```

### CDN

Quickly test Source Code Pro on your site by using the CDN hosted by [RawGit].
Feel free to use it in production as well:

```html
<link rel="stylesheet" href="https://cdn.rawgit.com/barberboy/source-code-pro/1.016/source-code-pro.css">
```

## Getting Involved

Send suggestions for changes to the Source Code OpenType font project maintainer, [Paul D. Hunt](mailto:opensourcefonts@adobe.com?subject=[GitHub] Source Code Pro), for consideration.

## Further information

For information about the design and background of Source Code, please refer to the [official font readme file](http://htmlpreview.github.io/?https://github.com/adobe-fonts/source-code-pro/blob/master/SourceCodeProReadMe.html).

[RawGit]: https://rawgit.com/
