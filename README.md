# soeren-helms-de
my personal website, moved to [personal gitlab](https://git.lumos.city/Repronik/DockerImages/Websites/netifypages/soeren-helms-de/)

![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/HSoeren/soeren-helms-de/Publish/master?style=flat-square)  ![Website](https://img.shields.io/website?style=flat-square&url=https%3A%2F%2Fsoeren-helms.de)

This project is based on [Hugo LoveIt Theme](https://github.com/dillonzq/LoveIt) which in turn is based on two other hugo templates.

## automated deployment

We won't be using Github forever, so the deployment exists once as Github and once as Gitlab CI/CD.

In current configuration it will be built at every commit to the master and also refreshed every tuesday morning.

### Github

see the [./github/workflows/main.yml](https://github.com/hackercave/website/blob/master/.github/workflows/main.yml)

### Gitlab

see the [.gitlab-ci.yml](https://github.com/hackercave/website/blob/master/.gitlab-ci.yml)

## see in action

just clone the project and run `$ hugo server --disableFastRender` or go on our website.
