Adding Gumby Addons
===================

Here's what we did in order to add the addon called **gumby-parallax**:

Install the addon via Bower
---------------------------

```sh
bower install gumby-parallax
```

Add the addon to gumby.json
---------------------------

In `gumby.json`, we added:

```json
"addons": [
  "bower_components/gumby-parallax/gumby.parallax.js"
]
```

Build using Claymate
--------------------

Run:

```sh
claymate build
```
