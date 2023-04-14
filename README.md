# ai-club-night
List of links to data, checkpoints and outputs contributing to the AI-Club-Night

## How to post new links

### pre-requisites

- if you haven't signed up to github already, do so.
- contact us on [discord in #ai-club-night](https://discord.gg/9FMz2CHE48) so that we can invite you to push changes on this repo
- install `git` to your system if it isn't installed already.
- now open a terminal and clone this repo where you want to keep it on your filesystem with
```shell script
git clone git@github.com:ktonal/ai-club-night.git
```

### add links

1. cd to your folder and pull the latest repo's version *before* making any changes

```shell script
cd ai-club-night/
git checkout main
git pull
```

2. create a branch for your changes

```shell script
git checkout -b bob/new-mixtape
```

3. make your changes to `data.txt`, `checkpoints.txt` or `outputs.txt`

> Please, remember, that 
>- your links must be publicly available for download
>- each link must be on a new line 
>- Please link to a folder. This make it faster for everyone to download all the links and for you to add new data (simply add it to your folder, without having to push changes to this repo).

4. commit and push your changes

```shell script
git add . && git commit -m 'add new awesome mixtape to data.txt'
git push
```

5. got to the repo on github and [create a pull request](https://github.com/ktonal/ai-club-night/pulls) 