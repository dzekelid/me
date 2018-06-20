---
name: Buffer
x-slug: buffer
description: Buffer is an intuitive social media management platform trusted by brands,
  businesses, agencies, and individuals to help drive social media results.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/994-buffer.jpg
x-kinRank: "7"
x-alexaRank: "2789"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/apis.md
specificationVersion: "0.14"
apis:
- name: Buffer Get Info Configuration Mediatypeextension
  x-api-slug: buffer
  description: Returns an object with the current configuration that Buffer is using,
    including supported services, their icons and the varying limits of character
    and schedules.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/994-buffer.jpg
  humanURL: http://bufferapp.com
  baseURL: https://api.bufferapp.com//1///info/configuration{mediaTypeExtension}
  tags: Info,ConfigurationmediaTypeExtension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/infoconfigurationmediatypeextension-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/infoconfigurationmediatypeextension-get-openapi.md
- name: Buffer Get Links Shares Mediatypeextension
  x-api-slug: buffer
  description: Returns an object with a the numbers of shares a link has had using
    Buffer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/994-buffer.jpg
  humanURL: http://bufferapp.com
  baseURL: https://api.bufferapp.com//1///links/shares{mediaTypeExtension}
  tags: Links,SharesmediaTypeExtension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/linkssharesmediatypeextension-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/linkssharesmediatypeextension-get-openapi.md
- name: Buffer Post Profiles Schedules Update Mediatypeextension
  x-api-slug: buffer
  description: Post Profiles Schedules Update Mediatypeextension
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/994-buffer.jpg
  humanURL: http://bufferapp.com
  baseURL: https://api.bufferapp.com//1///profiles/{id}/schedules/update{mediaTypeExtension}
  tags: Profiles,Id,Schedules,UpdatemediaTypeExtension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/profilesidschedulesupdatemediatypeextension-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/profilesidschedulesupdatemediatypeextension-post-openapi.md
- name: Buffer Get Profiles Schedules Mediatypeextension
  x-api-slug: buffer
  description: Returns details of the posting schedules associated with a social media
    profile.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/994-buffer.jpg
  humanURL: http://bufferapp.com
  baseURL: https://api.bufferapp.com//1///profiles/{id}/schedules{mediaTypeExtension}
  tags: Profiles,Id,SchedulesmediaTypeExtension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/profilesidschedulesmediatypeextension-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/profilesidschedulesmediatypeextension-get-openapi.md
- name: Buffer Get Profiles Updates Pending Mediatypeextension
  x-api-slug: buffer
  description: Get Profiles Updates Pending Mediatypeextension
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/994-buffer.jpg
  humanURL: http://bufferapp.com
  baseURL: https://api.bufferapp.com//1///profiles/{id}/updates/pending{mediaTypeExtension}
  tags: Profiles,Id,Updates,PendingmediaTypeExtension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/profilesidupdatespendingmediatypeextension-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/profilesidupdatespendingmediatypeextension-get-openapi.md
- name: Buffer Post Profiles Updates Reorder Mediatypeextension
  x-api-slug: buffer
  description: Edit the order at which statuses for the specified social media profile
    will be sent out of the buffer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/994-buffer.jpg
  humanURL: http://bufferapp.com
  baseURL: https://api.bufferapp.com//1///profiles/{id}/updates/reorder{mediaTypeExtension}
  tags: Profiles,Id,Updates,ReordermediaTypeExtension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/profilesidupdatesreordermediatypeextension-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/profilesidupdatesreordermediatypeextension-post-openapi.md
- name: Buffer Get Profiles Updates Sent Mediatypeextension
  x-api-slug: buffer
  description: Returns an array of updates that have been sent from the buffer for
    an individual social media profile.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/994-buffer.jpg
  humanURL: http://bufferapp.com
  baseURL: https://api.bufferapp.com//1///profiles/{id}/updates/sent{mediaTypeExtension}
  tags: Profiles,Id,Updates,SentmediaTypeExtension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/profilesidupdatessentmediatypeextension-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/profilesidupdatessentmediatypeextension-get-openapi.md
- name: Buffer Post Profiles Updates Shuffle Mediatypeextension
  x-api-slug: buffer
  description: Randomize the order at which statuses for the specified social media
    profile will be sent out of the buffer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/994-buffer.jpg
  humanURL: http://bufferapp.com
  baseURL: https://api.bufferapp.com//1///profiles/{id}/updates/shuffle{mediaTypeExtension}
  tags: Profiles,Id,Updates,ShufflemediaTypeExtension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/profilesidupdatesshufflemediatypeextension-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/profilesidupdatesshufflemediatypeextension-post-openapi.md
- name: Buffer Get Profiles Mediatypeextension
  x-api-slug: buffer
  description: Returns details of the single specified social media profile.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/994-buffer.jpg
  humanURL: http://bufferapp.com
  baseURL: https://api.bufferapp.com//1///profiles/{id}{mediaTypeExtension}
  tags: Profiles,IdmediaTypeExtension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/profilesidmediatypeextension-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/profilesidmediatypeextension-get-openapi.md
- name: Buffer Get Profiles Mediatypeextension
  x-api-slug: buffer
  description: Returns an array of social media profiles connected to a users account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/994-buffer.jpg
  humanURL: http://bufferapp.com
  baseURL: https://api.bufferapp.com//1///profiles{mediaTypeExtension}
  tags: ProfilesmediaTypeExtension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/profilesmediatypeextension-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/profilesmediatypeextension-get-openapi.md
- name: Buffer Post Updates Create Mediatypeextension
  x-api-slug: buffer
  description: Create one or more new status updates.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/994-buffer.jpg
  humanURL: http://bufferapp.com
  baseURL: https://api.bufferapp.com//1///updates/create{mediaTypeExtension}
  tags: Updates,CreatemediaTypeExtension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/updatescreatemediatypeextension-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/updatescreatemediatypeextension-post-openapi.md
- name: Buffer Post Updates Destroy Mediatypeextension
  x-api-slug: buffer
  description: Permanently delete an existing status update.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/994-buffer.jpg
  humanURL: http://bufferapp.com
  baseURL: https://api.bufferapp.com//1///updates/{id}/destroy{mediaTypeExtension}
  tags: Updates,Id,DestroymediaTypeExtension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/updatesiddestroymediatypeextension-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/updatesiddestroymediatypeextension-post-openapi.md
- name: Buffer Get Updates Interactions Mediatypeextension
  x-api-slug: buffer
  description: Returns the detailed information on individual interactions with the
    social media update such as favorites, retweets and likes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/994-buffer.jpg
  humanURL: http://bufferapp.com
  baseURL: https://api.bufferapp.com//1///updates/{id}/interactions{mediaTypeExtension}
  tags: Updates,Id,InteractionsmediaTypeExtension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/updatesidinteractionsmediatypeextension-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/updatesidinteractionsmediatypeextension-get-openapi.md
- name: Buffer Post Updates Move To Top Mediatypeextension
  x-api-slug: buffer
  description: Move an existing status update to the top of the queue and recalculate
    times for all updates in the queue. Returns the update with its new posting time.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/994-buffer.jpg
  humanURL: http://bufferapp.com
  baseURL: https://api.bufferapp.com//1///updates/{id}/move_to_top{mediaTypeExtension}
  tags: Updates,Id,Move,To,TopmediaTypeExtension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/updatesidmove-to-topmediatypeextension-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/updatesidmove-to-topmediatypeextension-post-openapi.md
- name: Buffer Post Updates Share Mediatypeextension
  x-api-slug: buffer
  description: Immediately shares a single pending update and recalculates times for
    updates remaining in the queue.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/994-buffer.jpg
  humanURL: http://bufferapp.com
  baseURL: https://api.bufferapp.com//1///updates/{id}/share{mediaTypeExtension}
  tags: Updates,Id,SharemediaTypeExtension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/updatesidsharemediatypeextension-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/updatesidsharemediatypeextension-post-openapi.md
- name: Buffer Post Updates Update Mediatypeextension
  x-api-slug: buffer
  description: Edit an existing, individual status update.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/994-buffer.jpg
  humanURL: http://bufferapp.com
  baseURL: https://api.bufferapp.com//1///updates/{id}/update{mediaTypeExtension}
  tags: Updates,Id,UpdatemediaTypeExtension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/updatesidupdatemediatypeextension-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/updatesidupdatemediatypeextension-post-openapi.md
- name: Buffer Get Updates Mediatypeextension
  x-api-slug: buffer
  description: Returns a single social media update.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/994-buffer.jpg
  humanURL: http://bufferapp.com
  baseURL: https://api.bufferapp.com//1///updates/{id}{mediaTypeExtension}
  tags: Updates,IdmediaTypeExtension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/updatesidmediatypeextension-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/updatesidmediatypeextension-get-openapi.md
- name: Buffer Get User Mediatypeextension
  x-api-slug: buffer
  description: Get user mediatypeextension.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/994-buffer.jpg
  humanURL: http://bufferapp.com
  baseURL: https://api.bufferapp.com//1///user{mediaTypeExtension}
  tags: UsermediaTypeExtension
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/usermediatypeextension-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/usermediatypeextension-get-openapi.md
- name: Buffer
  x-api-slug: buffer
  description: Buffer is an intuitive social media management platform trusted by
    brands, businesses, agencies, and individuals to help drive social media results.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/994-buffer.jpg
  humanURL: http://bufferapp.com
  baseURL: https://api.bufferapp.com//1/
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/buffer/openapi.md
x-common:
- type: x-base
  url: https://api.bufferapp.com/
- type: x-blog
  url: http://blog.bufferapp.com
- type: x-blog-rss
  url: http://blog.bufferapp.com/feed/
- type: x-github
  url: https://github.com/joelg
- type: x-crunchbase
  url: https://crunchbase.com/organization/buffer
- type: x-crunchbase
  url: http://www.crunchbase.com/company/buffer
- type: x-developer
  url: https://bufferapp.com/developers
- type: x-email
  url: hello@bufferapp.com
- type: x-email
  url: hello@buffer.com
- type: x-email
  url: copyright@buffer.com
- type: x-email
  url: api@bufferapp.com
- type: x-github
  url: https://github.com/bufferapp
- type: x-pricing
  url: https://buffer.com/pricing
- type: x-twitter
  url: https://twitter.com/buffer
- type: x-website
  url: http://bufferapp.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---