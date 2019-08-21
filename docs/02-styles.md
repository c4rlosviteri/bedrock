---
title: CSS
status: draft
---

These components are using SCSS which is processed and linted with Gulp.

### Breakpoints
Components are using `_mq.scss` mixins for breakpoints, the following settings are configured for breakpoints:
```css
$mq-breakpoints: (
  mobile:  320px,
  tablet:  740px,
  desktop: 980px,
  wide:    1300px
);
```
These can be changed in **`./components/styles/scss`**

For more information on _mq.scss, check out the [documentation](https://github.com/sass-mq/sass-mq#media-queries-with-superpowers-)

### Linting
Components are linted using [`gulp-sass-lint`](https://www.npmjs.com/package/gulp-sass-lint#usage) - the configuration file can be found at **`./.sass-lint.yml`**
