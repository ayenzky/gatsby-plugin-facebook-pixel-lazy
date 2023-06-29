# gatsby-plugin-facebook-pixel-lazy

Easily add Facebook Pixel to your Gatsby site. At this time, 'ViewContent' event is triggered via onRouteUpdate.

## Install

`npm install --save gatsby-plugin-facebook-pixel-lazy`

## How to use

```javascript
// In your gatsby-config.js
plugins: [
  {
    resolve: `gatsby-plugin-facebook-pixel-lazy`,
    options: {
      pixelId: "pixel id here",
      timeout: 3666, // a duration in ms. Defaults to 500
    },
  },
];
```
