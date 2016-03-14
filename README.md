# KISS, a simple [hugo](https://gohugo.io/) theme

I'm using this for [my own blog](http://malumdiscordi.ae) and only implemented the few features I needed.
Haters gonna hate and contributors gonna contribute - fork the repo, open a PR, you know the drill.

### Installing

Go to your hugo-site folder and issue:

```
$ git clone https://github.com/ephe-meral/kiss.git ./themes/kiss
$ hugo server -w --theme=kiss
```

### Configuring

These options can be defined in your page-global config:

``` yaml
params:
  Description:     # add the general blog description
  Email:           # add your personal email (footer)
  TwitterUsername: # as it says (footer)
  GitHubUsername:  # dito (footer)
  Comments:        # true/false
  DisqusShortName: # see the disqus docs
```

### Contributing

* understand that changes to this repo will occur under the provided LICENSE
* wanna work on the styling? install [sass](http://sass-lang.com/), and `make` it happen
* wanna work on anything else? go ahead, only hugo support is needed

### License

The WTFPL. See the LICENSE file.
