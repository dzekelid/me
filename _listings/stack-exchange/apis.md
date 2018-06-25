---
name: Stack Exchange
x-slug: stack-exchange
description: After someone asks a question, members of the community propose answers.
  Others vote on those answers. Very quickly, the answers with the most votes rise
  to the top. You dont have to read through a lot of discussion to find the best answer.    Like
  to...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/253-stack-exchange.jpg
x-kinRank: "8"
x-alexaRank: "126"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/apis.md
specificationVersion: "0.14"
apis:
- name: Stack Exchange Get Answer Comments
  x-api-slug: stack-exchange
  description: "Gets the comments on a set of answers.\n \nIf you know that you have
    an answer id and need the comments, use this method. If you know you have a question
    id, use /questions/{id}/comments. If you are unsure, use /posts/{id}/comments.\n
    \n{ids} can contain up to 100 semicolon delimited ids, to find ids programatically
    look for answer_id on answer objects.\n \nThe sorts accepted by this method operate
    on the follow fields of the comment object:\n - creation - creation_date\n - votes
    - score\n  creation is the default sort.\n \n It is possible to create moderately
    complex queries using sort, min, max, fromdate, and todate.\n \nThis method returns
    a list of comments."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/253-stack-exchange.jpg
  humanURL: http://stackexchange.com
  baseURL: https://api.stackexchange.com//2.2//answers/{ids}/comments
  tags: Answers,comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/answersidscomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/answersidscomments-get-openapi.md
- name: Stack Exchange Get Comments
  x-api-slug: stack-exchange
  description: "Gets all the comments on the site.\n \nIf you're filtering for interesting
    comments (by score, creation date, etc.) make use of the sort paramter with appropriate
    min and max values.\n \nIf you're looking to query conversations between users,
    instead use the /users/{ids}/mentioned and /users/{ids}/comments/{toid} methods.\n
    \nThe sorts accepted by this method operate on the follow fields of the comment
    object:\n - creation - creation_date\n - votes - score\n  creation is the default
    sort.\n \n It is possible to create moderately complex queries using sort, min,
    max, fromdate, and todate.\n \nThis method returns a list of comments."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/253-stack-exchange.jpg
  humanURL: http://stackexchange.com
  baseURL: https://api.stackexchange.com//2.2//comments
  tags: Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/comments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/comments-get-openapi.md
- name: Stack Exchange Get Comment
  x-api-slug: stack-exchange
  description: "Gets the comments identified in id.\n \nThis method is most useful
    if you have a cache of comment ids obtained through other means (such as /questions/{id}/comments)
    but suspect the data may be stale.\n \n{ids} can contain up to 100 semicolon delimited
    ids, to find ids programatically look for comment_id on comment objects.\n \nThe
    sorts accepted by this method operate on the follow fields of the comment object:\n
    - creation - creation_date\n - votes - score\n  creation is the default sort.\n
    \n It is possible to create moderately complex queries using sort, min, max, fromdate,
    and todate.\n \nThis method returns a list of comments."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/253-stack-exchange.jpg
  humanURL: http://stackexchange.com
  baseURL: https://api.stackexchange.com//2.2//comments/{ids}
  tags: Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/commentsids-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/commentsids-get-openapi.md
- name: Stack Exchange Delete Comment
  x-api-slug: stack-exchange
  description: "Deletes a comment.\n \nUse an access_token with write_access to delete
    a comment.\n \nIn practice, this method will never return an object."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/253-stack-exchange.jpg
  humanURL: http://stackexchange.com
  baseURL: https://api.stackexchange.com//2.2//comments/{id}/delete
  tags: Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/commentsiddelete-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/commentsiddelete-post-openapi.md
- name: Stack Exchange Edit Comment
  x-api-slug: stack-exchange
  description: "Edit an existing comment.\n \nUse an access_token with write_access
    to edit an existing comment.\n \nThis method return the created comment."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/253-stack-exchange.jpg
  humanURL: http://stackexchange.com
  baseURL: https://api.stackexchange.com//2.2//comments/{id}/edit
  tags: Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/commentsidedit-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/commentsidedit-post-openapi.md
- name: Stack Exchange My Comments
  x-api-slug: stack-exchange
  description: "Returns the comments owned by the user associated with the given access_token.\n
    \nThis method returns a list of comments."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/253-stack-exchange.jpg
  humanURL: http://stackexchange.com
  baseURL: https://api.stackexchange.com//2.2//me/comments
  tags: Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/mecomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/mecomments-get-openapi.md
- name: Stack Exchange My Comments
  x-api-slug: stack-exchange
  description: "Returns the comments owned by the user associated with the given access_token
    that are in reply to the user identified by {toId}.\n \nThis method returns a
    list of comments."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/253-stack-exchange.jpg
  humanURL: http://stackexchange.com
  baseURL: https://api.stackexchange.com//2.2//me/comments/{toId}
  tags: Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/mecommentstoid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/mecommentstoid-get-openapi.md
- name: Stack Exchange My Mentions
  x-api-slug: stack-exchange
  description: "Returns the comments mentioning the user associated with the given
    access_token.\n \nThis method returns a list of comments."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/253-stack-exchange.jpg
  humanURL: http://stackexchange.com
  baseURL: https://api.stackexchange.com//2.2//me/mentioned
  tags: Mentioned
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/mementioned-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/mementioned-get-openapi.md
- name: Stack Exchange My Merges
  x-api-slug: stack-exchange
  description: "Returns a record of merges that have occurred involving a user identified
    by an access_token.\n \nThis method allows you to take now invalid account ids
    and find what account they've become, or take currently valid account ids and
    find which ids were equivalent in the past.\n \nThis is most useful when confirming
    that an account_id is in fact \"new\" to an application.\n \nAccount merges can
    happen for a wide range of reasons, applications should not make assumptions that
    merges have particular causes.\n \nNote that accounts are managed at a network
    level, users on a site may be merged due to an account level merge but there is
    no guarantee that a merge has an effect on any particular site.\n \nThis method
    returns a list of account_merge."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/253-stack-exchange.jpg
  humanURL: http://stackexchange.com
  baseURL: https://api.stackexchange.com//2.2//me/merges
  tags: Merges
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/memerges-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/memerges-get-openapi.md
- name: Stack Exchange My Timeline
  x-api-slug: stack-exchange
  description: "Returns a subset of the actions the user identified by the passed
    access_token has taken on the site.\n \nThis method returns a list of user timeline
    objects."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/253-stack-exchange.jpg
  humanURL: http://stackexchange.com
  baseURL: https://api.stackexchange.com//2.2//me/timeline
  tags: Tags,Timeline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/metimeline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/metimeline-get-openapi.md
- name: Stack Exchange Get Post Comments
  x-api-slug: stack-exchange
  description: "Gets the comments on the posts identified in ids, regardless of the
    type of the posts.\n \nThis method is meant for cases when you are unsure of the
    type of the post id provided. Generally, this would be due to obtaining the post
    id directly from a user.\n \n{ids} can contain up to 100 semicolon delimited ids,
    to find ids programatically look for post_id, answer_id, or question_id on post,
    answer, and question objects respectively.\n \nThe sorts accepted by this method
    operate on the follow fields of the comment object:\n - creation - creation_date\n
    - votes - score\n  creation is the default sort.\n \n It is possible to create
    moderately complex queries using sort, min, max, fromdate, and todate.\n \nThis
    method returns a list of comments."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/253-stack-exchange.jpg
  humanURL: http://stackexchange.com
  baseURL: https://api.stackexchange.com//2.2//posts/{ids}/comments
  tags: Posts,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/postsidscomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/postsidscomments-get-openapi.md
- name: Stack Exchange Add Comment Post
  x-api-slug: stack-exchange
  description: "Create a new comment.\n \nUse an access_token with write_access to
    create a new comment on a post.\n \nThis method returns the created comment."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/253-stack-exchange.jpg
  humanURL: http://stackexchange.com
  baseURL: https://api.stackexchange.com//2.2//posts/{id}/comments/add
  tags: Posts,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/postsidcommentsadd-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/postsidcommentsadd-post-openapi.md
- name: Stack Exchange Get Question AnsweTimeliners
  x-api-slug: stack-exchange
  description: "Returns a subset of the events that have happened to the questions
    identified in id.\n \nThis provides data similar to that found on a question's
    timeline page.\n \nVoting data is scrubbed to deter inferencing of voter identity.\n
    \n{ids} can contain up to 100 semicolon delimited ids, to find ids programatically
    look for question_id on question objects.\n \nThis method returns a list of question
    timeline events."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/253-stack-exchange.jpg
  humanURL: http://stackexchange.com
  baseURL: https://api.stackexchange.com//2.2//questions/{ids}/timeline
  tags: Questions,Timeline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/questionsidstimeline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/questionsidstimeline-get-openapi.md
- name: Stack Exchange Get User Comments
  x-api-slug: stack-exchange
  description: "Get the comments posted by users in {ids}.\n \n{ids} can contain up
    to 100 semicolon delimited ids, to find ids programatically look for user_id on
    user or shallow_user objects.\n \nThe sorts accepted by this method operate on
    the follow fields of the comment object:\n - creation - creation_date\n - votes
    - score\n  creation is the default sort.\n \n It is possible to create moderately
    complex queries using sort, min, max, fromdate, and todate.\n \nThis method returns
    a list of comments."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/253-stack-exchange.jpg
  humanURL: http://stackexchange.com
  baseURL: https://api.stackexchange.com//2.2//users/{ids}/comments
  tags: Users,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/usersidscomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/usersidscomments-get-openapi.md
- name: Stack Exchange Get User Comments Told
  x-api-slug: stack-exchange
  description: "Get the comments that the users in {ids} have posted in reply to the
    single user identified in {toid}.\n \nThis method is useful for extracting conversations,
    especially over time or across multiple posts.\n \n{ids} can contain up to 100
    semicolon delimited ids, to find ids programatically look for user_id on user
    or shallow_user objects. {toid} can contain only 1 id, found in the same manner
    as those in {ids}.\n \nThe sorts accepted by this method operate on the follow
    fields of the comment object:\n - creation - creation_date\n - votes - score\n
    \ creation is the default sort.\n \n It is possible to create moderately complex
    queries using sort, min, max, fromdate, and todate.\n \nThis method returns a
    list of comments."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/253-stack-exchange.jpg
  humanURL: http://stackexchange.com
  baseURL: https://api.stackexchange.com//2.2//users/{ids}/comments/{toid}
  tags: Users,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/usersidscommentstoid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/usersidscommentstoid-get-openapi.md
- name: Stack Exchange Get User Mentioned
  x-api-slug: stack-exchange
  description: "Gets all the comments that the users in {ids} were mentioned in.\n
    \nNote, to count as a mention the comment must be considered to be \"in reply
    to\" a user. Most importantly, this means that a comment can only be in reply
    to a single user.\n \n{ids} can contain up to 100 semicolon delimited ids, to
    find ids programatically look for user_id on user or shallow_user objects.\n \nThe
    sorts accepted by this method operate on the follow fields of the comment object:\n
    - creation - creation_date\n - votes - score\n  It is possible to create moderately
    complex queries using sort, min, max, fromdate, and todate.\n \nThis method returns
    a list of comments."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/253-stack-exchange.jpg
  humanURL: http://stackexchange.com
  baseURL: https://api.stackexchange.com//2.2//users/{ids}/mentioned
  tags: Users,Mentioned
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/usersidsmentioned-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/usersidsmentioned-get-openapi.md
- name: Stack Exchange Get User Merges
  x-api-slug: stack-exchange
  description: "Returns a record of merges that have occurred involving the passed
    account ids.\n \nThis method allows you to take now invalid account ids and find
    what account they've become, or take currently valid account ids and find which
    ids were equivalent in the past.\n \nThis is most useful when confirming that
    an account_id is in fact \"new\" to an application.\n \nAccount merges can happen
    for a wide range of reasons, applications should not make assumptions that merges
    have particular causes.\n \nNote that accounts are managed at a network level,
    users on a site may be merged due to an account level merge but there is no guarantee
    that a merge has an effect on any particular site.\n \nThis method returns a list
    of account_merge."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/253-stack-exchange.jpg
  humanURL: http://stackexchange.com
  baseURL: https://api.stackexchange.com//2.2//users/{ids}/merges
  tags: Users,Merges
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/usersidsmerges-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/usersidsmerges-get-openapi.md
- name: Stack Exchange
  x-api-slug: stack-exchange
  description: After someone asks a question, members of the community propose answers.
    Others vote on those answers. Very quickly, the answers with the most votes rise
    to the top. You dont have to read through a lot of discussion to find the best
    answer.    Like to...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/253-stack-exchange.jpg
  humanURL: http://stackexchange.com
  baseURL: https://api.stackexchange.com//2.2
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stack-exchange/openapi.md
x-common:
- type: x-authentication
  url: https://api.stackexchange.com/docs/authentication
- type: x-base
  url: https://api.stackexchange.com/
- type: x-blog
  url: http://stackexchange.com/blogs
- type: x-blog-rss
  url: http://blog.stackoverflow.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/stack-exchange
- type: x-crunchbase
  url: https://crunchbase.com/organization/stack-exchange
- type: x-developer
  url: http://api.stackexchange.com/
- type: x-email
  url: legal@stackexchange.com
- type: x-email
  url: team@stackexchange.com
- type: x-email
  url: team+api@stackexchange.com
- type: x-error-codes
  url: https://api.stackexchange.com/docs/error-handling
- type: x-github
  url: https://github.com/StackExchange
- type: x-javascript-sdk
  url: https://api.stackexchange.com/docs/js-lib
- type: x-linkedin
  url: https://www.linkedin.com/company/stack-exchange
- type: x-privacy
  url: https://stackexchange.com/legal/privacy-policy
- type: x-rate-limits
  url: https://api.stackexchange.com/docs/throttle
- type: x-selfservice-registration
  url: https://stackapps.com/users/login?returnurl=/apps/oauth/register
- type: x-support
  url: https://stackexchange.com/about/contact
- type: x-terms-of-service
  url: http://stackexchange.com/legal/api-terms-of-use
- type: x-twitter
  url: https://twitter.com/StackExchange
- type: x-website
  url: http://stackexchange.com
- type: x-website
  url: https://stackexchange.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---