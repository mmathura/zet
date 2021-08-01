# Home Brew

## install docker on a mac

1. brew install docker
1. docker --version
1. docker run hello-world
1. brew install docker-machine
1. docker-machine create --driver virtualbox default
1. brew search virtualbox
1. brew install virtualbox --cask
1. docker-machine create --driver virtualbox default
1. docker-machine ls

## which docker machine

1. docker-machine env default

## connect to shell

1. eval $(docker-machine env default)
1. docker run hello-world
1. docker-machine stop default
