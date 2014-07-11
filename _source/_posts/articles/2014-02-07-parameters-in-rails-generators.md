---
layout: article
title: "Let your Rails Generator accept boolean parameters"
excerpt: "How to permit options like --skip-stylesheets on your generators"
image:
  feature: command-line-feature.jpg
  teaser: command-line-teaser.jpg
  thumb: command-line-thumb.jpg
category: articles
tags: [rails, snippets, quick tip]
comments: false
---

~~~ ruby
class_option :stylesheet, :type => :boolean, :default => true, :description => "Include stylesheet file"
~~~

so you can pass `--stylesheet` on command line.

to check this value on your generator class, use `options.stylesheet?`

if you want to use something like `--two-words`, do:

~~~ ruby
class_option :'no-coffeescript', :type => :boolean, :default => false, :desc => 'Skips coffeescript replacement into app generators'
~~~

and to check

~~~ruby
options[:'no-coffeescript']
~~~

as seen on [RailsCasts](http://railscasts.com/episodes/218-making-generators-in-rails-3?view=asciicast).
