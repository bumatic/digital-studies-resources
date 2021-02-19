---
title: 'Platform Studies'
type: resources
date: 2020-10-08 15:05
draft: false
weight: 40
summary: dm.
---

## (Historical) Data on Platforms

APIs (Application Programming Interfaces) are great for accessing and gathering current platform data. A number of projects are dedicated to archiving and publishing historical platform data. 


### Reddit

- Pushshift is archiving comment data from the social news aggregator Reddit since 2005. 
	- The data can be downloaded at: [Reddit Archive @ Pushhift](http://files.pushshift.io/reddit/comments/)
	- The archive can be queried with [Google Big Query](https://bigquery.cloud.google.com/dataset/fh-bigquery:reddit_comments?pli=1).
- Nathan Yau created an impressive visualization based on the data analyzing the [*Growth of Subreddits* \| FlowingData](https://flowingdata.com/2018/10/30/subreddit-comments/)


### Wikipedia

Being not a platform in the srtict sense of the concept Wikipedia nevertheless constitutes a vivid project and community with a build in "history" because MediaWiki – the software Wikipedia runs on – tracks all changes to any page on Wikipedia. The Wikimedia foundation provides various data dumps (mostly on a monthly basis) to all language editions of Wikipedia. The [Wikimedia Downloads](https://dumps.wikimedia.org/) page provides links to the most recent data dumps of active Wikis as well as to data dumps to discontintued Wikis.

### Telegram

The messenger service Telegram allows the creation of groups with up to 200.000 members interacting with each other and of channels with unlimited members for broadcasting messages to potentially very large audiences. This capability gave rise to Telegram's growing popularity as a social media platform. As a consequence, new patterns and dynamics of communication emerge that amend one-to-one and few-to-few communication by modes of many-to-many and one-to-many communication. The resulting publics of Telegram are situated in a grey zone of public*ness*: they typically accessible without restriction, yet at the same time remain hidden to a certain extend and thus might appear closed off. 

Due to its [broad understanding and enforcement of freedom of speech](https://telegram.org/faq#q-wait-0-o-do-you-process-take-down-requests-from-third-parties) Telegram has become popular among actors deplatformed from other social media. However, in January 2021 [Telegram confirmed](https://techcrunch.com/2021/01/13/telegram-channels-banned-violent-threats-capitol/) that it removed a number of channels because of threats of violence. 

A number of resources, meta-services and tools exist that allow (media) scholars to engage with Telegram as a platform to study. One of the challenges is to find groups and channels of interest. There are a number of pages dedicated to this:
- https://telegramcatalog.com/en/channels
- https://telegramchannels.me/
- https://tgstat.com/
- https://telemetr.io/

For retrieving data from relevant groups and channels one make use of the Telegram API. Once a free API key is acquired one can interact with Telegram programmatically:
- The Open Source tool 4cat (https://4cat.oilab.nl | https://github.com/digitalmethodsinitiative/4cat) provides an browser-based interface for capturing data from Telegram and for analyzing it. 
- Similar to and based on the code of the 4cat Telegram data retrieval tool this [Google Colaboratory notebook](https://colab.research.google.com/drive/1yujclW3HJPa1muxT-6GTCmFuV0E5W4Ch?usp=sharing) allows to retrieving channel data using the Telegram API. In addition to retrieving the messages from a channel it resolves the user names for forwarded messages. 

### Github

/TO DO: Resources need to be added/