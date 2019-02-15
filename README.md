# Komposter

Komposter is a wrapper in order to run composer inside a docker container with a specific php version.

It uses the [about:source wordpress](https://quay.io/repository/aboutsource/wordpress) docker image.

## Install

- Clone the repo to your desired path
- Add the following helpers to your `.bashrc` or `.zshrc`
```
# Komposter (composer docker wrapper)
alias komposter5="docker-compose -f $HOME/YOUR/PATH/komposter/5.6/docker-compose.yml run komposter"
alias komposter7="docker-compose -f $HOME/YOUR/PATH/komposter/7.0/docker-compose.yml run komposter"
```

