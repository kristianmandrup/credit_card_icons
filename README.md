# Credit Card icons

Credit Card icons for Rails 3.

This gem is a Rails 3 engine and includes a host of asset files including standalone image sets (icons), CSS sprites and stylesheets for the CSS sprites.

## Usage

In `Gemfile`.

`gem 'credit_card_icons'`

Install via bundler:

`bundle`

Include the stylesheet(s) of choice in your Rails 3 stylesheets application manifest file, fx `application.css` or similar:

```css
/*
 *= require credit_cards_default
*/
```

Using *Compass*, include stylesheet(s) via `@import 'credit_cards_default';` instead.

Use the cards via CSS classes like this:

## Stylesheets available

* credit_cards_default (24x24)
* credit_cards_24 (24x24)
* credit_cards_32 (32x32)

* straight_cards_32 (51x32)
* straight_cards_64 (102x64)
* straight_cards_128 (204x128)

* curved_cards_32 (51x32)
* curved_cards_64 (102x64)
* curved_cards_128 (204x128)

### Default

```haml
%ul.cc
	%li.card.mastercard
```

Also sizes 32 and 64 and 128px wide, use: `cc_24` and `cc_32`

### Straight

Sizes 32, 64 and 128px wide, use: `cc_32`, `cc_64` or `cc_128`.

```haml
%ul.cc_64
  %li.straight_card.mastercard
```

### Curved

Sizes 32, 64 and 128px wide.

```haml
%ul.cc_64
  %li.curved_card.mastercard
```

Not that here the HTML structure is defined using *HAML* syntax.

Please see the asset directory css files for how to use your stylesheet of choice.
Feel free to improve this gem by modifying the css rules and/or include view helpers etc.

## Contributing to credit_card_icons
 
* Check out the latest master to make sure the feature hasn't been implemented or the bug hasn't been fixed yet.
* Check out the issue tracker to make sure someone already hasn't requested it and/or contributed it.
* Fork the project.
* Start a feature/bugfix branch.
* Commit and push until you are happy with your contribution.
* Make sure to add tests for it. This is important so I don't break it in a future version unintentionally.
* Please try not to mess with the Rakefile, version, or history. If you want to have your own version, or is otherwise necessary, that is fine, but please isolate to its own commit so I can cherry-pick around it.

## Copyright

Copyright (c) 2012 Kristian Mandrup. See LICENSE.txt for
further details.

