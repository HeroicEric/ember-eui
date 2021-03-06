# Ember Eui Changelog

### Master

### 0.0.33
🏠 Internal
- Locks @elastic/eui version to 31.0.0
- Updates icon mappings

### 0.0.32
🚀 Enhancements
- Docfy docs
- EuiCollapsibleNav

### 0.0.31
🚀 Enhancements
- Customize focusTrapOptions for `focus-trap` helper inside <EuiModal /> 

### 0.0.30
🏠 Internal
- Bump ember-svg-jar

### 0.0.29
- Fix inline-styles and <EuiModal /> type with restrictWidth, should be maxWidth 

### 0.0.28
- Add ember-in-element-polyfill

### 0.0.27
- Move `ember-keyboard` and `ember-focus-trap` from devDependencies to dependencies

### 0.0.26
- Rename <Text /> component to <TextBlock>

### 0.0.25
- Updates to elastic ui to 31.0.0

### 0.0.24
🚀 Enhancements
- EuiModal

### 0.0.23
🚀 Enhancements
- EuiCallOut may now receive named blocks <:title> </:title> <:body> <:/body>

🏠 Internal
- Installed ember-named-blocks-polyfill

### 0.0.22
🐛 Bug / Fixes
- Renames EuiCallout to EuiCallOut

### 0.0.21
🐛 Bug / Fixes
- Fixes a few missing props for EuiPage, EuiPageBody, EuiPanel and EuiCard
- Fixes EuiHorizontalRule not receiving splattributes

### 0.0.20
🚀 Enhancements
- EuiHr

🐛 Bug / Fixes
- Fix EuiImage close Icon

### 0.0.19
🚀 Enhancements
- Performance for EuiText, EuiColor, EuiCallout, EuiPage, EuiFlexItem and more, reducing usage of element helper
- Text hack to avoid using element helper for simple text dom nodes
- EuiCard

🏠 Internal
- Update ember-svg-jar fork
- Update @elastic/eui to 30.3.0

### 0.0.18
🚀 Enhancements
- EuiFlexGroup
- EuiFlexGrid
- EuiFlexItem

### 0.0.17
🏠 Internal
- Fixes netlify redirects

### 0.0.16
🚀 Enhancements
- EuiBadge
- Use empty icon svg as placeholder while downloading the desired one 
- Adds @victor-aguilars to contributors

🏠 Internal
- Update ember-svg-jar fork

🐛 Bug / Fixes
- Add accordion to demo

### 0.0.15
🚀 Enhancements
- EuiSideNav
- EuiAvatar

### 0.0.14
🚀 Enhancements
- EuiCallout

### 0.0.13
🚀 Enhancements
- Updates ember-svg-jar dependency and loads all svgs on demand.

### 0.0.12

🏠 Internal
- Let apps define svgPath in environment.js
  ```ts
    `ember-eui`: {
      svgPath: 'svg/assets'
    }
  ```
  This assumes that you setup ember-svg-jar with the prefix `svg/` (which is the default one)

🐛 Bug / Fixes
- Fixed EuiIcon camelCase svgs

### 0.0.11

🚀 Enhancements
- EuiIcon
- EuiAccordion
- EuiPage
- EuiTitle
- EuiText
- EuiImage
- EuiSpinner
- EuiOverlayMask

🏠 Internal
- Update class-names helper to always concat

### 0.0.7

Update license and add a short description to the readme

### 0.0.6

Support importing only compiled css

```ts
  "ember-eui": {
        "theme": "amsterdam_dark",
        "useCompiledCss": true
    }
```

### 0.0.5

Add ember-cli-sass and app.scss blueprint

### 0.0.4

Expose scss files so you can now use eui sass variables

### 0.0.3

Delete blueprint for now

### 0.0.2

Fix changelog location

### 0.0.1

Support importing custom themes

```ts
  "ember-eui": {
        "theme": "light"
    }

```
