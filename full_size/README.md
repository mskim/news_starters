# How to create book using BookcheeGO?


## Installation

1. download DockerDeskTop

1. download docker image from docker hub, using terminal

```
docker pull minsookim/newsgo:v0.1.0

```
1. download  news_strater_template from Github

```
  git clone github.com/mskim/news_strater

```

1. cd into one of docker_book_strater_template folder
  - lets go into danhangbon folder
  - there should be Rakefile, READMD, sample

```
  cd full_size

  docker run -it -v $(pwd):/usr/src/app minsookim/newsgo:v0.0.1 bash

  rake

```