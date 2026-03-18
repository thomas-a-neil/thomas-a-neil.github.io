Neil Thomas's personal website. Built off of https://github.com/leonidk/leonidk.github.io.


Install ruby and jekyll ([macOS instructions](https://jekyllrb.com/docs/installation/macos/))


Set up Jekyll with these [local development instructions](https://github.com/barryclark/jekyll-now?tab=readme-ov-file#local-development)

Then install the necessary dependencies

```
gem install github-pages
```

Initialize the gemfiles:
```
bundle init
bundle add jekyll jekyll-sitemap
```

Then run

```
bundle exec jekyll serve
```

To deploy locally. Then point your browser at http://127.0.0.1:4000/ 
