# Welcome to the Anythink Market repo (powered by [Wilco](https://www.trywilco.com))

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

install docker before starting: 
1. clone the repo 
2. open folder root dir 
3. open bash and run `./start_quest.sh` 
4. run: 
    `docker -v`
    `docker-compose -v`
    `docker-compose up`
 Possible errors and thier solution: 
    1. docker postsql error - change the port number in the docker-composer.yml file 
    2. docker error start up - run the docker from desktop and then retry command 
