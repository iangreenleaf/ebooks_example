# ian_ebooks

It's a bot that looks like me.

## Setup

```bash
bundle install
ebooks archive username corpus/username.json
ebooks consume corpus/username.json
```

## Deployment ##

```
heroku create
heroku config:push
git push heroku master
heroku ps:scale worker=1
```
