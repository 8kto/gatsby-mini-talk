# Adding TypeScript

---
# Adding TypeScript

Install `gatsby-plugin-typescript` and some optional packages (`typescript` is required)

```bash
# Basic support
yarn add typescript gatsby-plugin-typescript

# Additional tools
yarn add --dev gatsby-plugin-tslint tslint tslint-loader
```

---
## Adding TypeScript: create first ts-component
<video controls autoplay>
  <source src="R-gatsby-talk-10-add-ts.mkv" type="video/mp4">
Your browser does not support the video tag.
</video>

---
## Adding TypeScript: install packages
<video controls autoplay>
  <source src="R-gatsby-talk-11-install-packages.mkv" type="video/mp4">
Your browser does not support the video tag.
</video>

---
# Tip 
## Rename all `*.js` files to `*.tsx`
```bash
find src/ -name "*.js" -exec rename 's/.js/.tsx/' {} \;
```

--- 
# Nice articles about TypeScript integration
+ https://medium.com/maxime-heckel/getting-started-with-typescript-on-gatsby-8544b47c1d27
+ https://medium.com/@thetrevorharmon/how-to-make-a-super-fast-static-site-with-gatsby-typescript-and-sass-3742c00d4524

