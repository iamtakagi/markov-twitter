# Markov Chain Tweet Bot

Run `$ docker-compose build && docker-compose up`

## Note
- This program uses [jsvine/markovify](https://github.com/jsvine/markovify) and [MeCab](https://taku910.github.io/mecab/).  
- To know all dependencies, see [requirements](requirements.txt) and [Dockerfile](Dockerfile).
- Based [tweet-generator](https://github.com/cordx56/tweet-generator)

## Features
- Learns from home_timelime and tweets every {n} minutes.
