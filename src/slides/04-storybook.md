# Adding Storybook

---
# Adding Storybook

<img src="https://raw.githubusercontent.com/storybooks/storybook/next/media/storybook-intro.gif" width="100%" />

> [Storybook](https://github.com/storybooks/storybook) is a development environment for UI components. 
> It allows you to browse a component library, view the different states of each component, 
> and interactively develop and test components.

---
# Adding Storybook

Add a couple packages... 😏
```bash
npm install -g @storybook/cli
yarn add --dev @storybook/react @storybook/addon-knobs @storybook/addon-viewport \
    @storybook/addon-options storybook-readme ts-loader  @types/node @types/react \
    @types/react-dom @types/react-helmet @types/react-redux @types/storybook__addon-actions \
    @types/storybook__addon-knobs @types/storybook__addon-options @types/storybook__react
```

---
# Adding Storybook

Init CLI installation wizard and go through a several simple questions
```bash
cd my-awesome-gatsby-project
sb init
```

[Nice tutorial](https://www.gatsbyjs.org/docs/visual-testing-with-storybook/) is available on the gatsby main site.

---
## Adding Storybook
<video controls autoplay>
  <source src="../videos/R-gatsby-talk-12-storybook.mkv" type="video/mp4">
Your browser does not support the video tag.
</video>
