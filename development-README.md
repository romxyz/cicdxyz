# Website

Theme based on [landing-page bootstrap theme ](http://startbootstrap.com/templates/landing-page/)

## Prerequisites, TODO: Dockerize
 - Install `Docker` and `docker-compose`
 
## How to use
 - Place a image in `/img/services/`
 - Create posts to display your services. Use the follow as an example:

```txt
---
layout: default
img: ipad.png
category: Services
title: The service title
description: The description of the service
---
```

## How test localy
 - Place a image in `/img/services/`
 - Create posts to display your services. Use the follow as an example:
 
```bash
docker-compose build
docker-compose up -d
docker-compose exec web bundle exec jekyll deploy
```

## Demo
View this jekyll theme in action [here](https://swcool.github.io/landing-page-theme)

## Screenshot
![screenshot](https://raw.githubusercontent.com/swcool/landing-page-theme/master/img/screenshot.png)

===

For more Jekyll details, read [documentation](http://jekyllrb.com/).
This Jekyll theme used [Freelancer Jekyll theme](https://github.com/jeromelachaud/freelancer-theme/) as reference.

## License
The contents of this repository are licensed under the [Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)

## Version
1.0.1
