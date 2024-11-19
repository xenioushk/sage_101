## Required composer packages

### Sage directives

Sage Directives adds a variety of useful Blade directives for use with Sage 10 including directives for WordPress, ACF, and various miscellaneous helpers.

:hand: Go to the theme folder and run the following command.

```bash
composer require log1x/sage-directives
```

**Read more**
https://github.com/log1x/sage-directives

**Documentation**
https://log1x.github.io/sage-directives-docs/usage/wordpress.html#query

### Sage SVG

Sage SVG is a simple package for using inline SVGs in your Sage 10 projects.

:hand: Go to the theme folder and run the following command.

```bash
composer require log1x/sage-svg
```

**Read more**
https://github.com/Log1x/sage-svg

## Convert css => scss

1. Create a file inside the resources/styles/custom-style.scss

2. Open the `app.scss` file and add this code.

```sass
@import 'custom-style'
```

3. To add support for the scss file compilation, we need to install the `bud-sas` package. Navigate to the theme folder and run the following command.

```bash
npm install @roots/bud-sass --save-dev
```

You need to re-run the `yarn run dev` command.

### Include TailWindCSS properties to custom-style.scss

```scss
.service-block {
  @apply bg-yellow-100 text-purple-500;
}
```
