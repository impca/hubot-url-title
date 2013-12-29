# hubot-url-title

Returns the title when a link is posted.

## Installation

Install the module:

    npm install --save hubot-url-title

(this will update your `package.json`).

Then add hubot-url-title to `external-scripts.json`:

```coffee
["hubot-url-title"]
```

## Configuration

#### Regular expression used to exclude URLs

    HUBOT_HTTP_INFO_IGNORE_URLS

If you use HipChat, it's useful to ignore sites already supported by HipChat:

    HUBOT_HTTP_INFO_IGNORE_URLS="github.com|twitter.com|imgur.com"

#### Comma-separated list of users to ignore

    HUBOT_HTTP_INFO_IGNORE_USERS