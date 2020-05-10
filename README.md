# StackOfTheFuture.com based on gatsby-casper

## Contributing
Add folder to series and configure it like other series

## Add a serie

This is the graymatter data that is needed to construct series

```
---
layout: series
title: TITLE_OF_SERIES
image: IMAGE
author: AUTHOR
draft: false
series:
    videos: NUMBER_OF_VIDEOS
    id: SERIES_ID
date: 2020-04-25T10:00:00.000Z
tags:
  - tag 1
  - tag 2
---

description of series here

```

### Add a video

```
---
layout: post
title: TITLE_OF_VIDEO
image: IMAGE
author: AUTHOR
video: VIDEO_FILE.mp4
draft: false
inseries:
  index: 2
  series: SERIES_ID
date: 2019-04-30T10:00:00.000Z
tags:
  - tag1
  - tag2
---

In this lesson
```