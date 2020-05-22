Shopify Temb Template Development
=====================

Temb is a theme framework for Shopify that helps you get your store up and running quickly. It provides all required theme templates, a starter set of liquid tags, and some basic styles and modules for you to extend on.

Styling and customization is left up to you. Some base styles and helpers are included, but there is **no need to remove any code before you start**. Simply download and get designing.

Designing a store for a client? Earn revenue through our <a href="http://www.shopify.com/partners">Partner program<a/>.

Basic structure
---------------
```
├── assets
│   └── Javascript, CSS, and theme images
├── layout
│   ├── theme.liquid
│   └── optional alternate layouts
├── snippets
│   └── custom code snippets
├── spec
│   └── tests and helpers
├── templates
│   ├── 404.liquid
│   ├── article.liquid
│   ├── blog.liquid
│   ├── cart.liquid
│   ├── collection.liquid
│   ├── collection.list.liquid
│   ├── index.liquid
│   ├── list-collections.liquid
│   ├── page.contact.liquid
│   ├── page.liquid
│   ├── product.liquid
│   ├── search.liquid
│   └── customers
│         └── required templates if customer accounts are enabled
├── config.yml
│   └── if using the theme gem (see link under Additional Resources)
```

i18n testing
---------------------
Tests make sure there are no missing or extra i18n strings or invalid html in your locale liquid files.

All PRs must pass the tests before being merged. Check the test status when you open a new PR on GitHub, or locally with the following.

- `bundle install` to install all the dependecies
- `rspec spec` to run all the tests


Additional resources
---------------------
- [Themes Documentation][1]: Learn more about Liquid and theme templates.
- [Shopify Theme Kit][2]: A cross-platform command line tool for building Shopify Themes.
- [Liquid Cheat Sheet][3]
- [Retail Tours][4]: Sign up for a workshop in a city near you to learn all things Shopify.
- Need more help? Ask a question in our [Design Forums][5].

License
---------------------
Timber is released under the [MIT License](LICENSE).

[1]: http://help.shopify.com/themes
[2]: ttps://github.com/Shopify/themekit
[3]: https://www.shopify.ca/partners/shopify-cheat-sheet
[4]: https://www.shopify.com/retailtour
[5]: http://ecommerce.shopify.com/c/ecommerce-design
