TwitterKit has been [abandoned on October 31, 2018](https://blog.twitter.com/developer/en_us/topics/tools/2018/discontinuing-support-for-twitter-kit-sdk.html).
This fork aims to keep it alive and up-to-date.

## Twitter Kit Features

* Compose Tweets
* Log in with Twitter
* Access the Twitter API

## Getting Started

* Generate your Twitter API keys through the [Twitter developer apps dashboard](https://apps.twitter.com/).
* Install Twitter Kit using instructions below.

### Install manually

Grab the aar files from the releases tab and moved them into your project, usually under the `/libs` folder.
```groovy

dependencies {
  implementation name: 'tweet-composer-{version}', ext: 'aar'
  implementation name: 'twitter-core-{version}', ext: 'aar'
}

```

## Original license

Copyright 2017 Twitter, Inc.

Licensed under the Apache License, Version 2.0: http://www.apache.org/licenses/LICENSE-2.0
