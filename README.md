[Deprecated]

see https://github.com/fisker/fis3-plugins


fis3-postprocessor-posthtml-beautify
a css formatter of fis3 based on js-beautify

[![npm](https://img.shields.io/npm/v/fis3-postprocessor-posthtml-beautifyt.svg?style=flat-square)](https://www.npmjs.com/package/fis3-postprocessor-posthtml-beautify) 
[![npm](https://img.shields.io/npm/dt/fis3-postprocessor-posthtml-beautify.svg?style=flat-square)](https://www.npmjs.com/package/fis3-postprocessor-posthtml-beautify) 
[![npm](https://img.shields.io/npm/dm/fis3-postprocessor-posthtml-beautify.svg?style=flat-square)](https://www.npmjs.com/package/fis3-postprocessor-posthtml-beautify)

## usage

    $ npm i -g fis3-postprocessor-posthtml-beautify

```
// fis-conf.js
var config = {
  rules: {
    Indent: 2,
    eol: '\n',
    eof: '\n'
  }
};

fis.match('*.html', {
  postprocessor: fis.plugin('posthtml-beautify', config)
});
```
more rules: 

## links
fis3: [http://fis.baidu.com/]

posthtml-beautify: [https://github.com/gitscrum/posthtml-beautify]
