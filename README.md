# etsy clone
Base project from:
https://github.com/jasminenoack/typescript-base

Best viewed in a recent version of Chrome on desktop.

## install
run  `npm run install`

## build
Add an [Etsy API key](https://www.etsy.com/developers/documentation/getting_started/register) to `src/credentials.ts`
run `npm run build`

## test
run `npm run test` (no tests implemented)

## features
Search for items by typing in the search bar. Favorite items by clicking on the heart.

## background

The goal is to build a site that can search the Etsy catalog via their API and display the results to the user. Support for bookmarkable search results would be nice too.

A clean presentation of the end-user content is important but secondary to architecture and code readability/cleanliness. Please include in the readme which browser the app looks best in; we want to see your best.  If you write tests for your code, include those in the project and how we can run them in the readme.

The entire code needs to be client side, the only exception is anything needed to serve static files.  When we evaluate the code, we will be using our own static serving. Refrain from using jquery and other dom manipulation libraries unless absolutely necessary. (We want to see your pure javascript skills as much as possible).

Use your best judgment given the nature of the project and include in the readme why you made those choices.  If you find anything confusing though, please reach out to [redacted] and ask questions.

To deliver the finished code test, make a repo (GitHub, BitBucket, etc.) and share with the team.  It’s helpful for us if you commit as you work. That will help us see how you work. All quality-type evaluations will only apply to the final commit.

[Main Api Call](http://www.etsy.com/developers/documentation/reference/listing#method_findalllistingactive)
[Main Data Structure](http://www.etsy.com/developers/documentation/reference/listing#section_fields)
[JSONP](http://www.etsy.com/developers/documentation/getting_started/jsonp#section_using_the_jsonp_interface_with_javascript)
[Associations](http://www.etsy.com/developers/documentation/getting_started/resources#section_associations)
