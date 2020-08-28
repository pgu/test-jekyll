# test-jekyll

## remote theme
https://docs.github.com/en/github/working-with-github-pages/adding-a-theme-to-your-github-pages-site-using-jekyll

https://github.com/benbalter/jekyll-remote-theme


## misc


https://docs.github.com/en/github/working-with-github-pages/creating-a-github-pages-site-with-jekyll
This fucker doesn't say that we need to execute:

`gem install github-pages`
before doing
`bundle update github-pages`

BTW, jekyll dependency in GH is currently 3.9.0. it says to use this version but at the end, to use GH page, we remove the line gem jekyll :/

mais quel fucker!
this isn't `bundle update github-pages` we need to do but `bundle update`.


- GH pages public even for private repo?
- access to GH pages? -> it looks like no more. no access, so no download of what is generated (_site).
- use custom theme: yes, with remote-theme