[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)

# Simple CSS Architecture

A simple css architecture for happy and maintainable stylesheets.

It's basically a mashup of the [7-1 architecture pattern](https://sass-guidelin.es/#the-7-1-pattern) and the component-driven approach from [RSCSS](http://rscss.io/) by Rico Sta Cruz.

Each folder of this project has its own `README.md` file to explain the purpose and add extra information. Be sure to browse the repository to see how it works.

This boilerplate uses the \*.scss syntax.

## Structure

```
scss/
|
|– abstract/
|   |– _reset.scss        # Reset/Normalize
|   |– _variables.scss    # Sass Variables
|   |– _functions.scss    # Sass Functions
|   |– _mixins.scss       # Sass Mixins
|
|– components/
|   …                     # RSCSS Components
|
|– layout/
|   |– _header.scss       # Header
|   |– _footer.scss       # Footer
|   |– _sidebar.scss      # Sidebar
|   …                     # Etc.
|
|– modules/
|   |– _animation.scss    # Animation Styles
|   |– _base.scss         # Footer
|   |– _buttons.scss      # Buttons
|   |– _typography.scss   # Typography
|   |– _forms.scss        # Forms
|   |– _helper.scss       # Helpers
|   |– _mediaqueries.scss # Media Queries
|   |– _print.scss        # Print
|   …                     # Etc.
|
|– pages/
|   |– front.scss         # Home specific styles
|   …                     # Etc.
|
|– vendor/
|   |– _bootstrap.scss    # Bootstrap
|   |– _slick.min.scss    # Slick Slider
|   …                     # Etc.
|
|– vendor-extension/ 
|   |– _bootstrap.scss    # Overwritten Bootstrap
|   …                     # Etc.
|
`– main.scss              # Main Sass file
```

## License

The code is available under the [MIT license](LICENSE.txt).
