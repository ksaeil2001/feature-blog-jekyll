# ksaeil2001 [![Code Climate](https://codeclimate.com/github/lavkumarv/feature-blog-jekyll/badges/gpa.svg)](https://codeclimate.com/github/lavkumarv/feature-blog-jekyll) <a href="https://codeclimate.com/github/lavkumarv/feature-blog-jekyll"><img src="https://codeclimate.com/github/lavkumarv/feature-blog-jekyll/badges/issue_count.svg" /></a>

평생의 동방견, 하나를 소개합니다

Home Page:

![hana](/images/하나.jpg)

## 하나와의 추억

 - 하나를 만나게 된 사연 
 - 하나의 첫 산책 
 - 하나를 잃어버린 날 
 - 하나의 우울증 
 - 하나의 첫 병원 -
## 하나와의 추억을 저장하는 곳

 - 아직은 잘 다루질 못하지만 자주 이 사이트에 들려 다양한 하나와의 추억들을 저장해야겠다.

---

## Setup for an Existing Jekyll site

`_config.yml` file:

``` yaml
# Basic settings
description:  This is personal blog.
baseurl: "/"
url: "https://lavkumarv.github.io"
twitter_username: LAV_K_V
github_username:  lavkumarv
include: ['_pages']

# Build settings
markdown:    kramdown
highlighter: pygments
lsi:         false
excerpt_separator: "\n\n"
gems:
  - jekyll-feed
  - jekyll-paginate
exclude:
  - Gemfile
  - Gemfile.lock

# pagination
gems: [jekyll-paginate]
paginate: 5
paginate_path: "/page:num/"

# Enable comments
comments: true

# Markdown settings
kramdown:
  auto_ids:       true
  footnote_nr:    1
  entity_output:  as_char
  toc_levels:     1..6
  smart_quotes:   lsquo,rsquo,ldquo,rdquo
  enable_coderay: false

  coderay:
    coderay_wrap:              div
    coderay_line_numbers:      inline
    coderay_line_number_start: 1
    coderay_tab_width:         4
    coderay_bold_every:        10
    coderay_css:               style
---
```
---
Global Configuration( global.yml):
``` yaml
# Site Settings
title: 'Lav Vishwakarma'
description: 'My personal Blog'
url: 'https://lavkumarv.github.io'

# Admin Settings
admin_name: 'Lav Vishwakarma'
admin_email: 'lav.kumar.dev@gmail.com'

#####################################################################
#About Page
author_name: 'Lav Kumar Vishwakarma'
author_profession: 'Full Stack Developer'
author_description: 'A computer science graduate student at University Institute of Technology,
RGPV with great interest in Software development and coding efficient software.</br></br>
My 3+ years of experience in web technologies like J2EE/Jersey, Node.js, Angular.js, c#, MongoDB, MySQL,
Linux with Appointy and TechShanty provides me with a rich experience in coding and maintaining
 large scalable applications.</br></br>
Working at Appointy as Software Developer Intern, I was involved in Full stack development of a SAAS
application which is used by 65,000+ business worldwide. '
author_image: '/images/author.jpg'

# social proiles
facebook: 'https://www.facebook.com/lavkumarv'
twitter: 'https://twitter.com/LAV_K_V'
linkedin: 'https://www.linkedin.com/in/lav-vishwakarma/'
instagram: 'https://www.instagram.com/vishwakarmalav/'
github: 'https://github.com/lavkumarv'
google-plus: 'https://plus.google.com/+LAVKUMARVISHWAKARMAdev'
stackoverflow: 'http://stackoverflow.com/users/4703818/lav-kumar-vishwakarma'
#####################################################################
---
```
Navigation Bar(nav.yml):
``` yaml
main:
    - { url: '/about', text: 'About' }
---
```

## Post Formate:

Image Post:
``` json
layout: blog
title: 'Sample post to check the functionality'
date: 2017-01-24 12:11:34
categories: blog
tags: code
image: '/images/default.jpg'
lead_text: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit.'
```
Video Post:
``` json
layout: blog
title: 'Sample post to check the functionality'
date: 2017-01-24 12:11:34
categories: blog
tags: code
image: '/images/default.jpg'
lead_text: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit.'
```
## Built With

* [Bootstrap](http://getbootstrap.com/) - The css framework used

## Contributing

Contributions are welcome!. Feel free to add a new feature or fix a bug.

## Authors

* **Lav Kumar Vishwakarma** - *Initial work* - [lavkumarv](https://github.com/lavkumarv)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
