What is RSS-Bridge?
-------------------

This is php project that solves following tasks:

- making RSS feeds to websites that don't have one
- improving existing RSS feeds (for example, making fulltext feeds)

For certain website, bridge is created.
That bridge generates RSS-feed.
List of existing bridges can be found here:: https://github.com/RSS-Bridge/rss-bridge/tree/master/bridges

There a lot of helper functions to write bridge for certain website:

- combining URL with their parts (port of urljoin from python)
- css-selectors
- Markdown to HTML converter (usages https://github.com/RSS-Bridge/rss-bridge/search?q=markdownToHtml)
- backports from PHP8: str_starts_with, str_ends_with, str_contains
- and others https://github.com/RSS-Bridge/rss-bridge/blob/master/lib/html.php

This is free (as freedom) software.
[UNLICENSE](https://github.com/RSS-Bridge/rss-bridge/blob/master/UNLICENSE).

About contributors
------------------

Almost all contributors to this project can be divided into 2 categories:

- Bridge maintainers
- Project maintainers

Bridge maintainers:

- make sure, that their bridge works, when website suddenly changes HTML structure
- improve bridge functionality by adding more options

Project maintainers:

- review issues and pull requests.
Approximately 80% of issues are error reports of existing bridges.

- fix and improve core functionality

- write documentation

- review organizational stuff.
For example, accepting donation links in HTML feed page to motivate bridge maintainers not do abandon their bridges (https://github.com/RSS-Bridge/rss-bridge/discussions/2063)

- sometimes fix abandoned bridges

Who am I?
---------

- From May 2018, I [maintain](https://github.com/RSS-Bridge/rss-bridge/commits/master/bridges/VkBridge.php) bridge for [VK](https://vk.com), Russian social network
- From September 2018, I [maintain](https://github.com/RSS-Bridge/rss-bridge/commits/master/bridges/PikabuBridge.php) bridge for [Pikabu](https://pikabu.ru), another popular Russian website
- From July 2020, I [maintain](https://github.com/RSS-Bridge/rss-bridge/issues/1660) the whole project

As for now, I am defacto the only project maintainer.

Roadmap
-------

- review issues and pull requests. This task will never end

- [improve documentation](https://github.com/RSS-Bridge/rss-bridge/projects/1). For instance:

  - [moving Wiki documentation to repository](https://github.com/RSS-Bridge/rss-bridge/issues/2356).
  As for now it is not convenient to add documentation to new base funcionality.
  After solving this task, new base functionality and it's documentation can be in one pull request.

  - making guides for

    - [instance admin](https://github.com/RSS-Bridge/rss-bridge/issues/2364)

    - [bridge maintainer](https://github.com/RSS-Bridge/rss-bridge/issues/2388)

    - [project maintainer](https://github.com/RSS-Bridge/rss-bridge/issues/2389)

- [improve base functionality](https://github.com/RSS-Bridge/rss-bridge/projects/2). For instance:

  - [make expiring media links permanent](https://github.com/RSS-Bridge/rss-bridge/issues/2365)

  - adding textbox for url and button, that [will redirect to feed, that corresponds to given url](https://github.com/RSS-Bridge/rss-bridge/issues/2360)

- [add automated tasks for better project maintainance](https://github.com/RSS-Bridge/rss-bridge/projects/3):

  - [automatic PR builds](https://github.com/RSS-Bridge/rss-bridge/issues/2362).
  With those builds in pull requests, it will be easy for project maintainer to compare difference between "before changes" and "after changes".

  - [automated checks, which bridge stopped working](https://github.com/RSS-Bridge/rss-bridge/issues/2280).
  This will allow for any contributor to see, which bridge stopped working.

- [integration with other services and tools](https://github.com/RSS-Bridge/rss-bridge/projects/4):

  - [Tiny Tiny RSS](https://github.com/RSS-Bridge/rss-bridge/issues/2361).
  Add site to Tiny Tiny RSS and using RSS-Bridge it will find feed link.

  - [Selenium](https://github.com/RSS-Bridge/rss-bridge/issues/2400).
  Selenium can be used to solve following problems:

    - to make FacebookBridge to [work on public instances](https://github.com/RSS-Bridge/rss-bridge/issues/2047) again. Or at least making it to work on private instances

    - [return back LinkedInBridge](https://github.com/RSS-Bridge/rss-bridge/issues/2400)

What problems appear while following roadmap?
---------------------------------------------

As I already mentioned, I am the only project maintainer and I need to spend time with solving tasks above.
Currently I have some motivation to review issues and pull requests for free.
But that motivation is not enough to deal with other tasks that are equally important.
If I am payed for my work, I will have way more motivation and time to spend those tasks.

What is the plan?
-----------------

- Financial contributors put money to [OpenCollective page](https://opencollective.com/rss-bridge)

- I spend 15 USD per hour to solving tasks above

- While dealing with those tasks I record video and make periodic short text reports

If you have questions and/or suggestions:


Contacts
--------

- IRC: #rssbridge на Libera.Chat (ircs://irc.libera.chat:6697/rssbridge)
- Personal email: eugene.molotov@yandex.ru
- Conversation on Open Collective: https://opencollective.com/rss-bridge/conversations/questions-and-suggestions-0pxeajqy
