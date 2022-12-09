# 👋 Hi~ Kelvin's Speaking 📣

I love coding 🧑‍💻. It's an enlightening✨ process to me. No matter frontend, backend, mobile apps, task automation, data mining, machine learning, algo trading... I like them all.

I make my living mainly by creating [iOS apps][ios-apps], and occasionally take some freelance web / mobile dev jobs. However, I spend quite a considerable amount of time(if not the most 😆) trying out new tech / methodology / frameworks. It's quite a hobby of mine, but I normally did it in private without mentioning it, no matter whether that piece of tech is interesting or not.

One day, I saw my beloved Taiwan IT minister [Audrey Tang](https://zh.wikipedia.org/zh-tw/%E5%94%90%E9%B3%B3) recommended a [work out loud](https://youtu.be/XpjNl3Z10uc) methodology. I'm convinced.

So here I listed some of my works and projects and open-sourced them on [github](https://github.com/hoishing). May the universe connect us 😉

## Mobile Apps

- see all recent published iOS / macOS app [here][ios-apps]

| app                                  |    lang    | os          | category  |       source code       |
|:------------------------------------ |:----------:| ----------- | --------- |:-----------------------:|
| [Video Compressor][Video Compressor] | ![][swift] | iOS         | utility   |                         | 
| [Easy Dictionary][Easy Dictionary]   | ![][swift] | iOS + macOS | education |                         |
| [英漢字典][英漢字典]                 | ![][swift] | iOS         | education |                         |
| [同音字典][同音字典]                 | ![][swift] | iOS + macOS | education |                         |
| [ZERO][ZERO] Turn-Base-Strategy      | ![][swift] | iOS + macOS | game      |   [github][zero-game]   |
| [認識佛教][認識佛教]                 |   obj-c    | iOS < v10   | education | [github][buddhism-objc] |

## Open Source Projects

### web app

| app                              |                                        dev stack                                         | description                                                     |
|:-------------------------------- |:----------------------------------------------------------------------------------------:|:--------------------------------------------------------------- |
| [Voice Recognition][voice-recog] | [![pwa][pwa-logo]][pwa] + [![alpine.js][alpine-logo]][alpine] + [![unocss][uno-logo]][uno] | quick and easy speech synthesis [PWA][pwa] in multiple language |


  ### Chrome Extensions

| extension                                    |  lang   | description                                                                    |
|:-------------------------------------------- |:-------:|:------------------------------------------------------------------------------ |
| [mini authenticator][mini-auth]              | ![][ts] | minimal 2FA authenticator that never store your secret keys                    |
| multilingual search                          | ![][ts] | instance language change for google voice search                               |
| [Chrome ext creation template][crx-template] | ![][ts] | chrome ext template packed w/ vite, CRXJS, react, tailwind, iconify and more.. | 

### Utilities

| app                                        |          lang / run          | description                                                                 |
|:------------------------------------------ |:----------------------------:|:--------------------------------------------------------------------------- |
| [Icon Resize CLI][icon-reisze]             |           ![][py]            | CLI to create lossless icons in multiple sizes                              |
| [Personalize CangJie IME][cangjie]         | [![][binder]][cangjie-ipynb] | generate custom char set for 倉頡 IME in Windows                            |
| selenium web crawler                       |           ![][py]            | crawl a web page with Selenium                                              |
| [Google Playbook Annotations to MD][pb2md] |   [![][binder]][pb-ipynb]    | convert playbook annotations(highlights and custom notes) to markdown files |
| [Markdown to Dash Docset][md2dash]         |           ![][py]            | convert md to HTML files that can be used for generating Dash docset        |

### NPM Packages

| packages                    |  lang   | description                            |
|:--------------------------- |:-------:|:-------------------------------------- |
| [TOTP Generator][totp-auth] | ![][ts] | time-based one-time-password generator |

### legacy projects

| project                                  |          lang           | description                                                     |
|:---------------------------------------- |:-----------------------:|:--------------------------------------------------------------- |
| [Atom Cell Navigation][cell-nav]         | ![coffeescript][coffee] | Atom editor extension for fast navigating between jupyter cells |
| [Google GData iOS static lib][gdata-lib] |          obj-c          | iOS static library of Google Data APIs                          |
| [Ruby Static Site Generator][ruby-ssg]   |      ![ruby][ruby]      | a simple SSG for [認識佛教 website][buddhism-site]              | 

## More...

- [![][twitter] - twitter][tw-shing]
- [![][docusaurus] - blog][blog-shing]

[py]: https://api.iconify.design/logos/python.svg?width=20
[js]: https://api.iconify.design/logos/javascript.svg?width=20
[ts]: https://api.iconify.design/logos/typescript-icon.svg?width=20
[swift]: https://api.iconify.design/logos/swift.svg?width=20
[ruby]: https://api.iconify.design/logos/ruby.svg?width=20
[coffee]: https://api.iconify.design/cib/coffeescript.svg?color=%235999FF&width=20
[twitter]: https://api.iconify.design/logos/twitter.svg?width=20
[docusaurus]: https://api.iconify.design/logos/docusaurus.svg?width=20
[gh]: https://api.iconify.design/ri/github-fill.svg?color=%23e950c1&width=26
[binder]: https://mybinder.org/badge_logo.svg
[Video Compressor]: https://apps.apple.com/hk/app/video-compressor/id482465886
[Easy Dictionary]: https://apps.apple.com/hk/app/%E8%8B%B1%E6%BC%A2%E5%AD%97%E5%85%B8-easy-dictionary/id684273271
[英漢字典]: https://apps.apple.com/hk/app/%E8%8B%B1%E6%BC%A2%E5%AD%97%E5%85%B8-ec-dict/id371152394
[同音字典]: https://apps.apple.com/hk/app/%E5%90%8C%E9%9F%B3%E5%AD%97%E5%85%B8/id956045098
[ZERO]: https://apps.apple.com/hk/app/zero-tbs/id1399856976
[認識佛教]: https://apps.apple.com/hk/app/%E8%AA%8D%E8%AD%98%E4%BD%9B%E6%95%99-%E6%9C%89%E8%81%B2%E6%9B%B8/id389971161
[ios-apps]: https://apps.apple.com/hk/developer/fbm/id371152397
[mac-easy-dict]: https://apps.apple.com/hk/app/%E8%8B%B1%E6%BC%A2%E5%AD%97%E5%85%B8-easy-dictionary/id1242356475
[mac-homophone]: https://apps.apple.com/hk/app/%E5%90%8C%E9%9F%B3%E5%AD%97%E5%85%B8-chinese-helper/id946346429
[cangjie-ipynb]: https://mybinder.org/v2/gh/hoishing/cangjie/HEAD?labpath=create_code.ipynb
[pb-ipynb]: https://mybinder.org/v2/gh/hoishing/playbook2md/HEAD?labpath=playbook.ipynb
[cangjie]: https://github.com/hoishing/cangjie
[md2dash]: https://github.com/hoishing/markdown-to-dash-docset
[mini-auth]: https://github.com/hoishing/mini-authenticator
[crx-template]: https://github.com/hoishing/template-chrome-ext
[cell-nav]: https://github.com/hoishing/cell-navigation
[totp-auth]: https://github.com/hoishing/totp-auth
[pb2md]: https://github.com/hoishing/playbook2md
[gdata-lib]: https://github.com/hoishing/GData-iOS-Static-Library-1.12
[ruby-ssg]: https://github.com/hoishing/ruby-SSG
[tw-shing]: https://twitter.com/hoishing
[blog-shing]: https://hoishing.github.io
[voice-recog]: https://github.com/hoishing/voice-recog
[zero-game]: https://github.com/hoishing/zero-game
[buddhism-objc]: https://github.com/hoishing/buddhism-objc
[icon-resize]: https://github.com/hoishing/icon-resize-cli
[buddhism-site]: https://hoishing.github.io/ruby-SSG/index_zh.htm
[uno]: https://github.com/unocss/unocss
[uno-logo]: https://api.iconify.design/logos/unocss.svg?height=20
[alpine]: https://alpinejs.dev
[alpine-logo]: https://api.iconify.design/logos/alpinejs.svg?height=20
[pwa]: https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps
[pwa-logo]: https://api.iconify.design/logos/pwa.svg?height=20