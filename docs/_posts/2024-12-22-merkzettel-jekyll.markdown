---
layout: post
title:  "Merkzettel Jekyll"
date:   2024-12-22 11:15:00 +0100
categories: know how
---
# Preparation

* Install ruby
``` bash
brew install ruby
```

* Add ruby path to `PATH` variable
   ``` bash
PATH=/opt/homebrew/opt/ruby/bin:$PATH
   ```

# The magic

{% highlight bash %}
bundle exec jekyll serve
Configuration file: /Users/ja/git/navgatt.github.io/docs/_config.yml
To use retry middleware with Faraday v2.0+, install `faraday-retry` gem
            Source: /Users/ja/git/navgatt.github.io/docs
       Destination: /Users/ja/git/navgatt.github.io/docs/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
       Jekyll Feed: Generating feed for posts
                    done in 0.18 seconds.
 Auto-regeneration: enabled for '/Users/ja/git/navgatt.github.io/docs'
    Server address: http://127.0.0.1:4000/
  Server running... press ctrl-c to stop.
^C
{% endhighlight %}
