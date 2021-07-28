# VBTC
Official blog of the VBTC exchange
title: The VBTC Blog

author: THONG NGO

email: quangthong1011@gmail.com

description: News and announcements regarding VBTC, the first Bitcoin live exchange in Vietnam

baseurl: https://vbtc.exvchange

url: "https://vbtc.github.io"

show_excerpts: true

twitter_username: vbtc_vietnam

facebook_username: VBTC.vn

github_username: vbtc

rss: feed.xml

markdown: kramdown

theme: minima "~> 2.0"

plugins:
  <!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="//www.googletagmanager.com/gtag/js?id=UA-134715319-1"></script>
<script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());

    gtag('config', 'UA-134715319-1');
</script>

  - jekyll-feed: "~> 0.6"

exclude:

  - .idea/90800003

  - Gemfile

  - Gemfile.lock

  - node_modules

  - vendor/bundle/

  - vendor/cache/

  - vendor/gems/

  - vendor/ruby/
