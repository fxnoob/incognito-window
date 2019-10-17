# Mark Incognito.

## Basic Usage

``` 
    yarn
    yarn dev
```

## features: 
> 1. Support for  ES7 ( with Babel and polyfill)
> 2. popup page with reactjs and material ui framework
> 3. Content script with reactjs and material ui framework
> 4. Bundling (webpack)

## directory structure
> *    `src/` is root directory for a chrome extension. it includes `manifest.json` file and other static stuff.

> *    `src/background.js`  is main background js  file for the chrome extension.
 
 > *  `popup-page` is the directory which includes react js setup for popup page.
 
 > *  `content-scripts` is the directory  directory which includes react js setup for content script.
 
 > *  `src/utils` is the directory for utilities that can be written in es6,es7 or es8...
 
## How to extend ? 

>   *  Write chrome extension's background scripts code in `src/background.js`

>  * Write chrome extension's popup page codes in `popup-page` Reactjs directory system. 
 
 >  *  Write chrome extension's content scripts codes in `content-scripts` Reactjs directory system. 


## Inspiration ? 

The inspiration for this came from a twitter thread, started by @getify which was regarding a browser functionality which will allow you to mark websites to always open incognito mode.

## Current Proposal ?

Creating a chrome and firefox extension which will all users to quickly mark a domain as `always incognito` meaning that all links form that domain, all its subdomains will always be opened in a new incognito tab.

## Current Feature Set ?

- Mark as incognito will be an option in the right click menu on links as well as can be done for the current domain from the extension icon in the brower menu tab.

- Browser extension will have a list of all marked domains, with easy remove list option.

- It will also give you a BIG button to mark and remove the current visited domain.
