---
title: "How to add new posts"
date: 2019-08-17T16:34:30-04:00
categories:
  - Tutorial
tags:
  - blog
author: Cornelius Fiddlebone
---

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

```ruby
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
```

To add new authors, add a new entry in ```_data/authors.yml``` file, e.g., as follows: 

```yaml
Billy Rick:
  name        : "Billy Rick"
  bio         : "What do you want, jewels? I am a very extravagant man."
  avatar: "/assets/images/bio-photo.jpg"
  links:
    - label: "Email"
      icon: "fas fa-fw fa-envelope-square"
      url: "mailto:billyrick@rick.com"
    - label: "Website"
      icon: "fas fa-fw fa-link"
      url: "https://thewhip.com"
    - label: "Twitter"
      icon: "fab fa-fw fa-twitter-square"
      url: "https://twitter.com/extravagantman"
```

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

