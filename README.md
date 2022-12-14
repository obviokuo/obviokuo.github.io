<div align="center">

  # Obvio Jekyll Theme

  A simple and awesome Jekyll theme based on Chirpy for presenting professional writing.

  <!-- [![Gem Version](https://img.shields.io/gem/v/jekyll-theme-chirpy?color=brightgreen)](https://rubygems.org/gems/jekyll-theme-chirpy)
  [![Build Status](https://github.com/cotes2020/jekyll-theme-chirpy/workflows/build/badge.svg?branch=master&event=push)](https://github.com/cotes2020/jekyll-theme-chirpy/actions?query=branch%3Amaster+event%3Apush)
  [![Codacy Badge](https://app.codacy.com/project/badge/Grade/4e556876a3c54d5e8f2d2857c4f43894)](https://www.codacy.com/gh/cotes2020/jekyll-theme-chirpy/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=cotes2020/jekyll-theme-chirpy&amp;utm_campaign=Badge_Grade)
  [![GitHub license](https://img.shields.io/github/license/cotes2020/jekyll-theme-chirpy.svg)](https://github.com/cotes2020/jekyll-theme-chirpy/blob/master/LICENSE)
  [![996.icu](https://img.shields.io/badge/link-996.icu-%23FF4D5B.svg)](https://996.icu) -->

  [**Live Demo →**](https://obviokuo.github.io/)

  [![Devices Mockup](https://github.com/obviokuo/obviokuo.github.io/blob/main/commons/site_devices.png?raw=true)](https://cotes2020.github.io/chirpy-demo)

</div>

## Features

- Localized Layout
- Dark/Light Theme Mode
- Pinned Posts
- Hierarchical Categories
- Last Modified Date for Posts
- Table of Contents
- Auto-generated Related Posts
- Syntax Highlighting
- Mathematical Expressions
- Mermaid Diagram & Flowchart
- Disqus/Utterances/Giscus Comments
- Search
- Atom Feeds
- Google Analytics
- GA Pageviews Reporting
- SEO & Performance Optimization


## Quick Start

Before starting, please follow the instructions in the [Jekyll Docs](https://jekyllrb.com/docs/installation/) to complete the installation of `Ruby`, `RubyGems`, `Jekyll`, and `Bundler`. In addition, [Git](https://git-scm.com/) is also required to be installed.

### Step 1. Creating a New Site

Create a new repository from the [**Chirpy Starter**](https://github.com/cotes2020/chirpy-starter/generate) and name it `<GH_USERNAME>.github.io`, where `GH_USERNAME` represents your GitHub username.

### Step 2. Installing Dependencies

Before running for the first time, go to the root directory of your site, and install dependencies as follows:

```console
$ bundle
```

### Step 3. Running Local Server

Run the following command in the root directory of the site:

```console
$ bundle exec jekyll s
```

Or run with Docker:

```console
$ docker run -it --rm \
    --volume="$PWD:/srv/jekyll" \
    -p 4000:4000 jekyll/jekyll \
    jekyll serve
```

After a while, navigate to the site at <http://localhost:4000>.

## Documentation

For more details on usage, please refer to the tutorial on the [demo website](https://cotes2020.github.io/chirpy-demo/) / [wiki](https://github.com/cotes2020/jekyll-theme-chirpy/wiki). Note that the tutorial is based on the [latest tag](https://github.com/cotes2020/jekyll-theme-chirpy/tags), and the features of the default branch are usually ahead of the documentation.

## Sponsoring

If you like this theme or find it helpful, please consider sponsoring me, because it will encourage and help me better maintain the project, I will be very grateful!

[![Wechat Pay](https://img.shields.io/badge/-Tip%20Me%20on%20WeChat-brightgreen?logo=wechat&logoColor=white)][cn-donation1]
[![Alipay](https://img.shields.io/badge/-Tip%20Me%20on%20Alipay-blue?logo=alipay&logoColor=white)][cn-donation2]

## License

This work is published under [MIT](https://github.com/cotes2020/jekyll-theme-chirpy/blob/master/LICENSE) License.

<!-- ReadMe links -->

<!-- [jb]: https://www.jetbrains.com/?from=jekyll-theme-chirpy-->
[cn-donation1]: https://github.com/obviokuo/obviokuo.github.io/blob/main/commons/WeChatpay.JPG?raw=true
[cn-donation2]: https://github.com/obviokuo/obviokuo.github.io/blob/main/commons/Alipay.JPG?raw=true
