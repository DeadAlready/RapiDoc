<img alt="MrinDoc logo" src="https://github.com/mrin9/RapiDoc/blob/master/logo.png" width="60px" />


<p align="center">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square"/>
    <img src="https://img.shields.io/github/size/mrin9/rapidoc/dist/rapidoc-min.js.svg?colorB=blue&label=minified&style=flat-square">
    <img src="https://img.shields.io/github/size/mrin9/rapidoc/dist/rapidoc-min.js.gz.svg?colorB=blue&label=zip&style=flat-square">
    <a href="https://www.webcomponents.org/element/rapidoc" alt="published on webcomponents.org">
        <img src="https://img.shields.io/badge/webcomponents.org-rapidoc-blue.svg?style=social"/>
    </a>
</p>        

# RapiDoc
Custom Eelement for Open-API spec viewing

## Features
- Supports Swagger 2.0 and OpenAPI 3.0 
- Works with any framework or with no framework
- Allows to make API calls
- Better Usability, 
  - all Models and Examples are expanded by default, eliminates the need to click and reveal.
  - Request fields are pre-populated with sample data
  - Takes only one click to make an API call
  - Request and response can be placed side-by-side for easy comparision
- Branding and Personalization features makes it easy to follow any style guide
  - Comes with 2 Themes (Dark and Light)
  - Replace default logo with yours
  - Typography, allows changing fonts
  - Allows changing text-color, button-color, header-color and color of other UI elements
- Plenty of customization options 
  - Add external contents at the top and bottom of the document,  you may add images, link, text, forms etc
  - Allows disabling API calling feature
  - Hide the header so the user cant load any other OpenAPI Spec
  - Hide Authentication and provide your own pre-generated api-key 
  - Embed it inside another HTML document
  - Use it inside another framework (react, vue, angular, lit-element)
  - Use JavaScript to change its attributes, and it will react to those changes
  - Style the element with standard css (change padding, position, border, margin )
- Lightweight and fast (under 125 KB gzipped)
- Load local json spec from the disk
- Supported on Chrome, FireFox and Safari. (Not yet tested on Edge)


## Documentation
[Check out the usage and examples](https://mrin9.github.io/RapiDoc/)


## Build Process
We recommend `yarn` over `npm` as we use yarn [resolutions](https://yarnpkg.com/lang/en/docs/selective-version-resolutions/) to keep the bundle size smaller. As of this writing this feature is not supported in npm natively 
```bash
# Clone / Download the project then
yarn install

# build will generate rapidoc-min.js, this is the only file you will need.
# use it in the script tag of your html <script type="text/javascript" src="rapidoc-min.js"></script></body>
yarn build 

# for developement use yarn serve (this will start an webserver at port 8080, then navigate to localhost:8080) 
yarn serve
```


## Help RapiDoc grow
If you like this project, and would like to help us raise awareness of RapiDoc, 
I am looking for adding links to your design of RapiDoc. 

I often find it's helpful to see use-cases "in the wild". Be it a new style, an integration project with another framework such as vue, or be it just a Logo of your organization which would validate our commitment to quality.

You can suggest your RapiDoc's Design by creating an issue and we will take it from there.
