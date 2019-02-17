# Goldabj.github.io

# About Jekyll
---
####Font Matter
Font matter is just varible for your page. There are some built in varible to set such as layout, permalink, date, categories, and tags. 
All font matter varible can be found under the page.'var' object (ex: page.title). 

####Static Data
You can create static yml data files under the /data directory. These collection will then be avaliable under the sit.data.'fileName' varibale. 

####Posts
You can specify markdown posts in the _posts/ directory. Each post must have a file name of YYYY-MM-DD-title.md . 

####Post Excerpts
By default a post's excerpt is the first paragraph of the post. But this can be customized by adding a custom seperator in the font matter. 
EX> 
```
---
excerpt_separator: <!--more-->
---

Excerpt with multiple paragraphs

Here's another paragraph in the excerpt.
<!--more-->
Out-of-excerpt
```

####Liquid
Liquid is a templating language allowing the use of variables and programming language constrcturs. 
Ex. variables: {{ varible }}
Ex. tags : {% if 'expresion' %}


[Offical Liquid Docs](https://shopify.github.io/liquid/basics/introduction/)

#Development 
---
Start up: 
```bash
bundle exec jekyll serve
```
* you can see you drafts by adding the '--drafts' flag 

