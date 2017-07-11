# Technical Blog

## Welcome to My Blog

## Jekyll Theme

This blog theme is forked from [Gaohaoyang](https://github.com/Gaohaoyang/gaohaoyang.github.io).

## Usage

It is easy to use it by using docker.

1. Pull official docker image

    ```bash
    $ docker pull jekyll/jekyll:latest
    ```

2. Build or run container with docker

    ```bash
    $ docker run --rm --volume=$PWD:/srv/jekyll -p 4000:4000 -it jekyll/jekyll:latest jekyll serve
    ```

3. Webhook in github

## License

[MIT License](https://github.com/chengui/chengui.github.io/blob/master/LICENSE.md)
