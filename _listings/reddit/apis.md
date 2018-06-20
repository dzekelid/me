---
name: Reddit
x-slug: reddit
description: Reddit is a community of millions of users engaging in the creation of
  content and the sharing of conversation across tens of thousands of topics.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
x-kinRank: "9"
x-alexaRank: "6"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/apis.md
specificationVersion: "0.14"
apis:
- name: Reddit Get Me
  x-api-slug: reddit
  description: Returns the identity of the user currently authenticated via OAuth.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////v1/me
  tags: Me
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/v1me-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/v1me-getnbsp-openapi.md
- name: Reddit Get Me Karma
  x-api-slug: reddit
  description: Return a breakdown of subreddit karma.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////v1/me/karma
  tags: Me, Karma
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/v1mekarma-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/v1mekarma-getnbsp-openapi.md
- name: Reddit Get Me Prefs
  x-api-slug: reddit
  description: Return the preference settings of the logged in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////v1/me/prefs
  tags: Me, Prefs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/v1meprefs-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/v1meprefs-getnbsp-openapi.md
- name: Reddit Patch Me Prefs
  x-api-slug: reddit
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////v1/me/prefs
  tags: Me, Prefs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/v1meprefs-patchnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/v1meprefs-patchnbsp-openapi.md
- name: Reddit Get Me Trophies
  x-api-slug: reddit
  description: Return a list of trophies for the current user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////v1/me/trophies
  tags: Me, Trophies
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/v1metrophies-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/v1metrophies-getnbsp-openapi.md
- name: Reddit Delete Subreddit Emoji Emoji Name
  x-api-slug: reddit
  description: |-
    Delete a Subreddit emoji.
    Remove the emoji from Cassandra and purge the assets from S3
    and the image resizing provider.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////v1/subreddit/emoji/emoji_name
  tags: Subreddit, Emoji, Emoji, Name
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/v1subredditemojiemoji-name-deletenbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/v1subredditemojiemoji-name-deletenbsp-openapi.md
- name: Reddit Add Gold Gild Fullname
  x-api-slug: reddit
  description: fullname of a thing
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////v1/gold/gild/fullname
  tags: Gold, Gild, Fullname
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/v1goldgildfullname-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/v1goldgildfullname-postnbsp-openapi.md
- name: Reddit Add Gold Give Username
  x-api-slug: reddit
  description: an integer between 1 and 36
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////v1/gold/give/username
  tags: Gold, Give, Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/v1goldgiveusername-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/v1goldgiveusername-postnbsp-openapi.md
- name: Reddit Get By Names
  x-api-slug: reddit
  description: Get a listing of links by fullname.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////by_id/names
  tags: Names
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/by-idnames-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/by-idnames-get-openapi.md
- name: Reddit Get Subreddit Comments Article
  x-api-slug: reddit
  description: Get the comment tree for a given Link article.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com///{/r/subreddit}/comments/article
  tags: Subreddit, Comments, Article
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/rsubredditcommentsarticle-getnbsp-openapi.md
- name: Reddit Add Collapse Message
  x-api-slug: reddit
  description: Collapse a message
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////collapse_message
  tags: Collapse, Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/collapse-message-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/collapse-message-postnbsp-openapi.md
- name: Reddit Add Read All Messages
  x-api-slug: reddit
  description: Queue up marking all messages for a user as read.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////read_all_messages
  tags: Read, Messages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/read-all-messages-postnbsp-openapi.md
- name: Reddit Add Read Message
  x-api-slug: reddit
  description: A comma-separated list of thing fullnames
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////read_message
  tags: Read, Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/read-message-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/read-message-postnbsp-openapi.md
- name: Reddit Add Uncollapse Message
  x-api-slug: reddit
  description: Uncollapse a message
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////uncollapse_message
  tags: Uncollapse, Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/uncollapse-message-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/uncollapse-message-postnbsp-openapi.md
- name: Reddit Add Unread Message
  x-api-slug: reddit
  description: A comma-separated list of thing fullnames
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////unread_message
  tags: Unread, Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/unread-message-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/unread-message-postnbsp-openapi.md
- name: Reddit Get Message Where
  x-api-slug: reddit
  description: This endpoint is a listing.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////message/where
  tags: Message, Where
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/messagewhere-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/messagewhere-getnbsp-openapi.md
- name: Reddit Add Mute Message Author
  x-api-slug: reddit
  description: For muting user via modmail.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////mute_message_author
  tags: Mute, Message, Author
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/mute-message-author-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/mute-message-author-postnbsp-openapi.md
- name: Reddit Add Unmute Message Author
  x-api-slug: reddit
  description: For unmuting user via modmail.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////unmute_message_author
  tags: Unmute, Message, Author
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/unmute-message-author-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/unmute-message-author-postnbsp-openapi.md
- name: Reddit Add Multi Rename
  x-api-slug: reddit
  description: Rename a multi.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////multi/rename
  tags: Multi, Rename
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/multirename-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/multirename-postnbsp-openapi.md
- name: Reddit Get Multi User Username
  x-api-slug: reddit
  description: Fetch a list of public multis belonging to username
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////multi/user/username
  tags: Multi, User, Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/multiuserusername-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/multiuserusername-getnbsp-openapi.md
- name: Reddit Delete Multi Multipath Srname
  x-api-slug: reddit
  description: Remove a subreddit from a multi.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////multi/multipath/r/srname
  tags: Multi, Multipath, Srname
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/multimultipathrsrname-deletenbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/multimultipathrsrname-deletenbsp-openapi.md
- name: Reddit Get Multi Multipath Srname
  x-api-slug: reddit
  description: Get data about a subreddit in a multi.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////multi/multipath/r/srname
  tags: Multi, Multipath, Srname
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/multimultipathrsrname-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/multimultipathrsrname-getnbsp-openapi.md
- name: Reddit Put Multi Multipath Srname
  x-api-slug: reddit
  description: Add a subreddit to a multi.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////multi/multipath/r/srname
  tags: Multi, Multipath, Srname
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/multimultipathrsrname-putnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/multimultipathrsrname-putnbsp-openapi.md
- name: Reddit Get Recommend Sr Srnames
  x-api-slug: reddit
  description: Return subreddits recommended for the given subreddit(s).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////recommend/sr/srnames
  tags: Recommend, Sr, Srnames
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/recommendsrsrnames-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/recommendsrsrnames-getnbsp-openapi.md
- name: Reddit Get Search Reddit Names
  x-api-slug: reddit
  description: List subreddit names that begin with a query string.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////api/search_reddit_names.json
  tags: Search, Reddit, Names
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/apisearch-reddit-names-json-get-openapi.md
- name: Reddit Add Search Reddit Names
  x-api-slug: reddit
  description: List subreddit names that begin with a query string.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com////search_reddit_names
  tags: Search, Reddit, Names
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/search-reddit-names-postnbsp-openapi.md
- name: Reddit
  x-api-slug: reddit
  description: Reddit is a community of millions of users engaging in the creation
    of content and the sharing of conversation across tens of thousands of topics.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/reddit/openapi.md
x-common:
- type: x-authentication
  url: https://github.com/reddit/reddit/wiki/OAuth2
- type: x-base
  url: https://www.reddit.com/
- type: x-best-practices
  url: https://github.com/reddit/reddit/wiki/API
- type: x-blog
  url: http://www.redditblog.com/
- type: x-blog-rss
  url: https://www.reddit.com/r/datasets/.rss
- type: x-blog-rss
  url: http://www.redditblog.com/feeds/posts/default?alt=rss
- type: x-code-libraries
  url: https://github.com/reddit/reddit/wiki/API-Wrappers
- type: x-console
  url: https://apigee.com/console/reddit
- type: x-crunchbase
  url: https://crunchbase.com/organization/reddit
- type: x-developer
  url: http://www.reddit.com/dev/api
- type: x-email
  url: legal@reddit.com
- type: x-github
  url: https://github.com/reddit
- type: x-privacy
  url: https://www.reddit.com/help/privacypolicy
- type: x-security
  url: https://www.reddit.com/help/privacypolicy#section_security
- type: x-support
  url: https://www.reddit.com/contact/
- type: x-terms-of-service
  url: http://www.reddit.com/help/useragreement
- type: x-transparency-report
  url: https://www.reddit.com/wiki/transparency
- type: x-twitter
  url: https://twitter.com/reddit
- type: x-website
  url: http://www.reddit.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---