# alertify-rails

This gem provides [alertify.js](http://fabien-d.github.com/alertify.js) (v0.3.11) for Rails.


## Installation

In your Gemfile:

```ruby
gem 'alertify-rails'
```

or system wide:

```console
$ gem install alertify-rails
```


## Usage

The alertify files will be added to the asset pipeline and available for you to use. Add the following line to `app/assets/javascripts/application.js`

```javascript
//= require alertify
```

In order to get the CSS, add the following line to `app/assets/stylesheets/application.css.scss`

```css
/*
 *= require alertify
 */
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

Copyright &copy; 2012 Rudolf Schmidt, released under the MIT license

