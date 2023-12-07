# README

## Setup

This repo uses devcontainer to provide jekyll and all needed libs and frameworks.  

I'm developing this with

* [VS Code Dev Container](https://code.visualstudio.com/docs/devcontainers/containers) 
* [DevPod](https://devpod.sh/)


## Jekyll

In the container navigate to correct path `workspaces` inside `my-site`

I need to call `bundle` to pull in dependencies

```bash
bundle
```

### Commands 

```bash
bundle exec jekyll serve
```

```bash
jekyll build
```

```bash
jekyll serve
```

## Deploy

Right now I just pulled into the root my site.  Not great, but good enough for first pass.