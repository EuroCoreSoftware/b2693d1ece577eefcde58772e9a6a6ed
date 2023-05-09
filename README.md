# EuroCore Software - Software That Runs on Real Robots

## What is this?

A directory of robotics software you can use with your robot.

## Contribute

1. Edit `content/software/data.toml` file in any plain text editor or straight through [GitHub's editor](https://help.github.com/articles/editing-files-in-another-user-s-repository/).

2. Create a new entry, following the schema described below.

**All done!** We do greatly appreciate PRs, but if you're not comfortable with this process, you're welcome to open an issue requesting the addition of your project instead.


## How to add a new project?

Add an entry to [data.toml](content/software/data.toml):
```toml
[[items]]

# [Mandatory] Name of the project
name = "Stable-Baselines3"

# [Mandatory] Short description, can be multiline
description = "PyTorch version of Stable Baselines, reliable implementations of reinforcement learning algorithms."

# [Mandatory] The different categories that project belongs to, for now ["learning", "planning", "control", "vision", "ik"]
categories = ["learning", "vision"]

# [Mandatory] Github repository
repository_url = "https://github.com/DLR-RM/stable-baselines3"

# [Optional] Homepage or documentation URL
homepage_url = "https://stable-baselines3.readthedocs.io/en/master/"

# [Optional] YouTube video URL, should respect the format "https://www.youtube.com/watch?v=VIDEO_ID
video_url = "https://www.youtube.com/watch?v=f_FmDFrYkPM"

# [Optional] URL to associated paper (or one of the associated paper)
paper_url = "http://jmlr.org/papers/v22/20-1364.html"

# [Optional] URL to logo image
logo_url = "https://github.com/DLR-RM/stable-baselines3/raw/master/docs/_static/img/logo.png"

# Not used for now, a list of keywords, will be used for search/filter later
tags = []

# [Optional] Name of the python package published on PyPI (`pip install package_name`)
pypi = "stable-baselines3"

```

### Enhance this website

EuroCore uses [bulma](https://bulma.io/), and [zola](https://github.com/getzola/zola) the Rust static site generator.


If you're comfortable with bulma and Zola please reach out to us in the Issues with your enhancement ideas or just to state your willingness to contribute.


### Errors

It's very likely there are mistakes around, if you find one please file an issue.

*Thanks for helping us map the Rust game development ecosystem!*


### Aknowledgement

The template comes from [arewegameyet.rs](https://arewegameyet.rs/).

Inspired by [arewewebyet](https://www.arewewebyet.org) and [arewelearningyet](https://www.arewelearningyet.com))