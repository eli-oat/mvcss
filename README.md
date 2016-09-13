# MVCSS

Minimal Viable CSS (keeps HTML readable and speedy). 

## How to use MVCSS

Simple as simple can be! Include the stylesheet in one of two ways...

With this handy CDN link:

```
<link rel="stylesheet" href="https://unpkg.com/mvcss/mvcss.min.css" type="text/css" media="screen">
```

Or just paste the code into the head of your HTML document between `<style>` ... `</style>` tags.

## See some examples

MVCSS in the wild! 

- [Here is an older version of this README document!](https://ns-jywwwjlmzy.now.sh)
- [*Villette*, by the best of the Brontës (look out for the best sentence in the whole book:"Happiness is not a potato...")](https://smallandnearlysilent.com/villette/)

## Hold your horses... 🐴

What is this all about? 

MVCSS is a snippet of CSS (not a CSS "framework") that makes a bland HTML document a bit more readable and 100% responsive...as in, everything will fit on a device's screen. HTML does a lot of the heavy lifting already, MVCSS just gives it the winning push that it needs to go the distance.  

## Why is this an NPM package? 

Frankly, there isn't a great reason why. It isn't JS, and I almost never write JS, but I hadn't ever made an NPM package and I thought this would be a good, low-stress way to try it out. Using [NPMCDN](https://npmcdn.com) the package can be easily included on the fly, but, really, you oughtn't do that because this is so teeny-tiny (558 bytes, 343 minified) you might as well include the whole kit-and-kaboodle in the head of your HTML and not bother with making an extra call. 

This entire endeavor is an effort in over engineering…

## Pull requests, issues, etc. 

The master repo lives at `https://gogs.eli.li/eli_oat/mvcss.git`, but is mirrored on github: [`https://github.com/eli-oat/mvcss.git`](https://github.com/eli-oat/mvcss.git)

Feel free to make pull requests, file issues and what not on Github.


[![NPM](https://nodei.co/npm/mvcss.png)](https://npmjs.org/package/mvcss)
