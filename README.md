# Tim

> A Minimal Hugo Theme Based On [Tim Holman's Site](https://github.com/tholman/tholman.com)

## Installation

This is best installed as a submodule.
This will make `tim` a dependency repo to the original project.

In the root of your Hugo site, run:

```shell
$ git submodule add https://github.com/adamisntdead/tim.git themes/tim
```

Now initialize the submodule for the parent repo:

```shell
$ git submodule init
$ git submodule update
```

## Usage

To use the theme, change/add this line in `config.toml`

```toml
theme = "tim"
```

You now need to use a few parameters:

```toml
[params]
  description = "THIS IS YOUR META DESCRIPTION"
  subtitle = "Projects and Writings Of"
  author = "Adam Kelly"
  bio = "My Bio Here."
  twitter = "adamisntdead"
  github = "adamisntdead"
  email = "adam.kelly2201@gmail.com"
  linkedin = "adamkelly"
  cv = "/CV.pdf"
```

This will give the site:

![screenshot](https://i.imgur.com/gS9DpXwl.png)

You can leave out `twitter`, `github`, `email`, `linkedin` or `cv`, and it won't be included.

## Credits

Original site design and code © Tim Holman. Hugo specific code © Adam Kelly. MIT License.