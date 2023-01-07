# Docker (Derailed Self-hosted)

The easiest and fastest way to deploy Derailed.

For any scaling, we recommend separately deploying each module.

## Using

Firstly, you will want to download Docker and Git.
To learn how to download [go here](https://docs.docker.com/get-docker/) and [here](https://git-scm.com/downloads).

Once you have Git, run `git clone https://github.com/derailedapp/docker` to clone this repository.

Then simply run `docker compose up --build` to spin up your own Derailed Server.

### Background Running

The Docker command above will start up the server in an interactive and viewable environment.

But in certain cases, like production environments, this would not be ideal.

So to run in the background, just add the `d` arg. Like so `docker compose up --build -d`.
