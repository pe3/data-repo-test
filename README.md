
## data-repo-test

- data displayed at [pe3.github.io/data-repo-test](http://pe3.github.io/data-repo-test/)



- commits to [YAML file](https://github.com/pe3/data-repo-test/blob/gh-pages/_data/members.yml) automatically render to JSON on GitHub
- this concept might be usefull in data curation 
  - accept commits through pull requests
  - full commit history in database independent format
- link to [generated json file](http://pe3.github.io/data-repo-test/api/members.json) a.k.a the API
- link to content tailored [data browser](http://pe3.github.io/data-repo-test/)

## development

```
git clone [repo]
cd [repo]
gem install jekyll
jekyll serve --watch
```

## documentation

Jekyll uses the [Liquid](https://github.com/Shopify/liquid/wiki) templating language to process templates. [Data To JSON](http://jekyllrb.com/docs/templates/) is a default feature.

