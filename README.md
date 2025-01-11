# Calm Twitter

Forked from https://github.com/yusukesaitoh/calm-twitter

I modified this extension to work on Firefox with additional features and options to keep up with the current interface of Twitter/X.
While working on this, I found that there was a way better extension https://jbscript.dev/control-panel-for-twitter, so I recommend using that. Just using this experience to learn about writing browser extensions and how Twitter works to an extent.

Added options:
- Hide Grok, Lists, Jobs, Communities, Premium, Verified Orgs tabs from the sidebar
- Hide For You from the homepage

Build Instructions:

nodejs and npm is required.

1. git clone the repo
2. cd into the repo
3. run `npm install`
4. build the extension `npm run build` and extension is built in packages/
5. In `about:debugging#/runtime/this-firefox` load Temporary Add-on