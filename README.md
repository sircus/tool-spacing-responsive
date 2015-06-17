# sircus-tools-space-responsive

[![npm version](https://img.shields.io/npm/v/sircus-tools-space-responsive.svg?style=flat)](https://www.npmjs.com/package/sircus-tools-space-responsive)

> A responsive space tools Module of Sircus.

## Dependencies
- [sircus-global-property](https://github.com/sircus/global-property)


## Installation

> npm:

```bash
$ npm install sircus-tools-space-responsive sircus-global-property
```

## Usage

> cssnext:

input.css
```css
@import "sircus-tools-space-responsive";
/*
@import "sircus-tools-space-responsive/lib/sm";
@import "sircus-tools-space-responsive/lib/md";
@import "sircus-tools-space-responsive/lib/lg";
*/
@import "sircus-global-property";
```

> sass:

input.scss
```scss
@import "./node_modules/sircus-global-property/converted";
@import "./node_modules/sircus-tools-space-responsive/converted";
// @import "./node_modules/sircus-tools-space-responsive/scss/sm";
// @import "./node_modules/sircus-tools-space-responsive/scss/md";
// @import "./node_modules/sircus-tools-space-responsive/scss/lg";
```


> html

```html
<div class="t-sm-ma0"></div>
<div class="t-sm-maMi"></div>
<div class="t-sm-maTn"></div>
<div class="t-sm-maXs"></div>
<div class="t-sm-maSm"></div>
<div class="t-sm-maMd"></div>
<div class="t-sm-maLg"></div>
<div class="t-sm-maXl"></div>
<div class="t-sm-maHg"></div>
<div class="t-sm-maGt"></div>
<div class="t-sm-mt0"></div>
<div class="t-sm-mtMi"></div>
<div class="t-sm-mtTn"></div>
<div class="t-sm-mtXs"></div>
<div class="t-sm-mtSm"></div>
<div class="t-sm-mtMd"></div>
<div class="t-sm-mtLg"></div>
<div class="t-sm-mtXl"></div>
<div class="t-sm-mtHg"></div>
<div class="t-sm-mtGt"></div>
<div class="t-sm-mb0"></div>
<div class="t-sm-mbMi"></div>
<div class="t-sm-mbTn"></div>
<div class="t-sm-mbXs"></div>
<div class="t-sm-mbSm"></div>
<div class="t-sm-mbMd"></div>
<div class="t-sm-mbLg"></div>
<div class="t-sm-mbXl"></div>
<div class="t-sm-mbHg"></div>
<div class="t-sm-mbGt"></div>
<div class="t-sm-pa0"></div>
<div class="t-sm-paMi"></div>
<div class="t-sm-paTn"></div>
<div class="t-sm-paXs"></div>
<div class="t-sm-paSm"></div>
<div class="t-sm-paMd"></div>
<div class="t-sm-paLg"></div>
<div class="t-sm-paXl"></div>
<div class="t-sm-paHg"></div>
<div class="t-sm-paGt"></div>
<div class="t-sm-pt0"></div>
<div class="t-sm-ptMi"></div>
<div class="t-sm-ptTn"></div>
<div class="t-sm-ptXs"></div>
<div class="t-sm-ptSm"></div>
<div class="t-sm-ptMd"></div>
<div class="t-sm-ptLg"></div>
<div class="t-sm-ptXl"></div>
<div class="t-sm-ptHg"></div>
<div class="t-sm-ptGt"></div>
<div class="t-sm-pb0"></div>
<div class="t-sm-pbMi"></div>
<div class="t-sm-pbTn"></div>
<div class="t-sm-pbXs"></div>
<div class="t-sm-pbSm"></div>
<div class="t-sm-pbMd"></div>
<div class="t-sm-pbLg"></div>
<div class="t-sm-pbXl"></div>
<div class="t-sm-pbHg"></div>
<div class="t-sm-pbGt"></div>


<div class="t-md-ma0"></div>
<div class="t-md-maMi"></div>
<div class="t-md-maTn"></div>
<div class="t-md-maXs"></div>
<div class="t-md-maSm"></div>
<div class="t-md-maMd"></div>
<div class="t-md-maLg"></div>
<div class="t-md-maXl"></div>
<div class="t-md-maHg"></div>
<div class="t-md-maGt"></div>
<div class="t-md-mt0"></div>
<div class="t-md-mtMi"></div>
<div class="t-md-mtTn"></div>
<div class="t-md-mtXs"></div>
<div class="t-md-mtSm"></div>
<div class="t-md-mtMd"></div>
<div class="t-md-mtLg"></div>
<div class="t-md-mtXl"></div>
<div class="t-md-mtHg"></div>
<div class="t-md-mtGt"></div>
<div class="t-md-mb0"></div>
<div class="t-md-mbMi"></div>
<div class="t-md-mbTn"></div>
<div class="t-md-mbXs"></div>
<div class="t-md-mbSm"></div>
<div class="t-md-mbMd"></div>
<div class="t-md-mbLg"></div>
<div class="t-md-mbXl"></div>
<div class="t-md-mbHg"></div>
<div class="t-md-mbGt"></div>
<div class="t-md-pa0"></div>
<div class="t-md-paMi"></div>
<div class="t-md-paTn"></div>
<div class="t-md-paXs"></div>
<div class="t-md-paSm"></div>
<div class="t-md-paMd"></div>
<div class="t-md-paLg"></div>
<div class="t-md-paXl"></div>
<div class="t-md-paHg"></div>
<div class="t-md-paGt"></div>
<div class="t-md-pt0"></div>
<div class="t-md-ptMi"></div>
<div class="t-md-ptTn"></div>
<div class="t-md-ptXs"></div>
<div class="t-md-ptSm"></div>
<div class="t-md-ptMd"></div>
<div class="t-md-ptLg"></div>
<div class="t-md-ptXl"></div>
<div class="t-md-ptHg"></div>
<div class="t-md-ptGt"></div>
<div class="t-md-pb0"></div>
<div class="t-md-pbMi"></div>
<div class="t-md-pbTn"></div>
<div class="t-md-pbXs"></div>
<div class="t-md-pbSm"></div>
<div class="t-md-pbMd"></div>
<div class="t-md-pbLg"></div>
<div class="t-md-pbXl"></div>
<div class="t-md-pbHg"></div>
<div class="t-md-pbGt"></div>


<div class="t-lg-ma0"></div>
<div class="t-lg-maMi"></div>
<div class="t-lg-maTn"></div>
<div class="t-lg-maXs"></div>
<div class="t-lg-maSm"></div>
<div class="t-lg-maMd"></div>
<div class="t-lg-maLg"></div>
<div class="t-lg-maXl"></div>
<div class="t-lg-maHg"></div>
<div class="t-lg-maGt"></div>
<div class="t-lg-mt0"></div>
<div class="t-lg-mtMi"></div>
<div class="t-lg-mtTn"></div>
<div class="t-lg-mtXs"></div>
<div class="t-lg-mtSm"></div>
<div class="t-lg-mtMd"></div>
<div class="t-lg-mtLg"></div>
<div class="t-lg-mtXl"></div>
<div class="t-lg-mtHg"></div>
<div class="t-lg-mtGt"></div>
<div class="t-lg-mb0"></div>
<div class="t-lg-mbMi"></div>
<div class="t-lg-mbTn"></div>
<div class="t-lg-mbXs"></div>
<div class="t-lg-mbSm"></div>
<div class="t-lg-mbMd"></div>
<div class="t-lg-mbLg"></div>
<div class="t-lg-mbXl"></div>
<div class="t-lg-mbHg"></div>
<div class="t-lg-mbGt"></div>
<div class="t-lg-pa0"></div>
<div class="t-lg-paMi"></div>
<div class="t-lg-paTn"></div>
<div class="t-lg-paXs"></div>
<div class="t-lg-paSm"></div>
<div class="t-lg-paMd"></div>
<div class="t-lg-paLg"></div>
<div class="t-lg-paXl"></div>
<div class="t-lg-paHg"></div>
<div class="t-lg-paGt"></div>
<div class="t-lg-pt0"></div>
<div class="t-lg-ptMi"></div>
<div class="t-lg-ptTn"></div>
<div class="t-lg-ptXs"></div>
<div class="t-lg-ptSm"></div>
<div class="t-lg-ptMd"></div>
<div class="t-lg-ptLg"></div>
<div class="t-lg-ptXl"></div>
<div class="t-lg-ptHg"></div>
<div class="t-lg-ptGt"></div>
<div class="t-lg-pb0"></div>
<div class="t-lg-pbMi"></div>
<div class="t-lg-pbTn"></div>
<div class="t-lg-pbXs"></div>
<div class="t-lg-pbSm"></div>
<div class="t-lg-pbMd"></div>
<div class="t-lg-pbLg"></div>
<div class="t-lg-pbXl"></div>
<div class="t-lg-pbHg"></div>
<div class="t-lg-pbGt"></div>
```


## Contributing

We Need Your Help!


## License
Released under the [MIT](https://github.com/sircus/license/blob/master/LICENSE) license.
