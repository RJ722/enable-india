## Setup
- [Install Jekyll](https://jekyllrb.com/)
- Clone this repository.
- `cd enable-india`
- `bundle exec jekyll serve`. 
- You can now access your new Jekyll site from [http://127.0.0.1:4000/](http://127.0.0.1:4000/).

### Auto-Generating Sitemap
The sitemap is auto generated! Just simply change the sitemap variable in front matter of each page. It looks like so...
```
sitemap:
    priority: 0.7
    lastmod: 2017-11-02
    changefreq: weekly
```

### Formspring.io Integration
Formspring is supported out of the box! Just add your email to ```_config.yml```
