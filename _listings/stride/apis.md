---
name: Stride
x-slug: stride
description: Stride is a cloud-based team business communication and collaboration
  tool, launched by Atlassian to replace the cloud-based version of HipChat. Stride
  software is available to download onto computers running Windows, Mac or Linux,
  as well as Android, iOS smartphones, and tablets
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/atlassian-stride-logo.jpg
x-kinRank: "8"
x-alexaRank: "0"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stride/apis.md
specificationVersion: "0.14"
apis:
- name: Stride Send app configuration updates
  x-api-slug: stride
  description: |-
    Post app configuration updates telling the.

    Authentication required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/atlassian-stride-logo.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com////app/module/chat/conversation/chat:configuration/{key}/state
  tags: Messaging,App, Module, Chat, Conversation, Chat, Configuration, Key, State
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stride/appmodulechatconversationchatconfigurationkeystate-post-openapi.md
- name: Stride Send glance updates
  x-api-slug: stride
  description: |-
    Post glance updates which will be pushed for all users within the specified context.

    Authentication required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/atlassian-stride-logo.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com////app/module/chat/conversation/chat:glance/{key}/state
  tags: Messaging,App, Module, Chat, Conversation, Chat, Glance, Key, State
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stride/appmodulechatconversationchatglancekeystate-post-openapi.md
- name: Stride Get conversation list for site
  x-api-slug: stride
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/atlassian-stride-logo.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com////site/{cloudId}/conversation
  tags: Messaging,Site, Cloud, Conversation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stride/sitecloudidconversation-get-openapi.md
- name: Stride Create conversation
  x-api-slug: stride
  description: Authentication required, with scope manage:conversation
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/atlassian-stride-logo.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com////site/{cloudId}/conversation
  tags: Messaging,Site, Cloud, Conversation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stride/sitecloudidconversation-post-openapi.md
- name: Stride Send message to user
  x-api-slug: stride
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/atlassian-stride-logo.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com////site/{cloudId}/conversation/user/{userId}/message
  tags: Messaging,Site, Cloud, Conversation, User, User, Message
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stride/sitecloudidconversationuseruseridmessage-post-openapi.md
- name: Stride Get conversation details
  x-api-slug: stride
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/atlassian-stride-logo.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com////site/{cloudId}/conversation/{conversationId}
  tags: Messaging,Site, Cloud, Conversation, Conversation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stride/sitecloudidconversationconversationid-get-openapi.md
- name: Stride Update conversation
  x-api-slug: stride
  description: Authentication required, with scope manage:conversation
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/atlassian-stride-logo.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com////site/{cloudId}/conversation/{conversationId}
  tags: Messaging,Site, Cloud, Conversation, Conversation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stride/sitecloudidconversationconversationid-patch-openapi.md
- name: Stride Archive conversation
  x-api-slug: stride
  description: Authentication required, with scope manage:conversation
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/atlassian-stride-logo.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com////site/{cloudId}/conversation/{conversationId}/archive
  tags: Messaging,Site, Cloud, Conversation, Conversation, Archives
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stride/sitecloudidconversationconversationidarchive-put-openapi.md
- name: Stride Upload a file
  x-api-slug: stride
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/atlassian-stride-logo.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com////site/{cloudId}/conversation/{conversationId}/media
  tags: Messaging,Site, Cloud, Conversation, Conversation, Media
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stride/sitecloudidconversationconversationidmedia-post-openapi.md
- name: Stride Get a file
  x-api-slug: stride
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/atlassian-stride-logo.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com////site/{cloudId}/conversation/{conversationId}/media/{mediaId}
  tags: Messaging,Site, Cloud, Conversation, Conversation, Media, Media
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stride/sitecloudidconversationconversationidmediamediaid-get-openapi.md
- name: Stride Get conversation history
  x-api-slug: stride
  description: "Authentication required, with scope participate:conversation\n\nThis
    method returns messages after/before a given messageIDs or/and timestamps.\nIf
    these parameters are omitted the method returns conversation\u2019s latest messages."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/atlassian-stride-logo.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com////site/{cloudId}/conversation/{conversationId}/message
  tags: Messaging,Site, Cloud, Conversation, Conversation, Message
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stride/sitecloudidconversationconversationidmessage-get-openapi.md
- name: Stride Send a message to a conversation
  x-api-slug: stride
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/atlassian-stride-logo.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com////site/{cloudId}/conversation/{conversationId}/message
  tags: Messaging,Site, Cloud, Conversation, Conversation, Message
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stride/sitecloudidconversationconversationidmessage-post-openapi.md
- name: Stride Get latest messages for conversation
  x-api-slug: stride
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/atlassian-stride-logo.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com////site/{cloudId}/conversation/{conversationId}/message/recent
  tags: Messaging,Site, Cloud, Conversation, Conversation, Message, Recent
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stride/sitecloudidconversationconversationidmessagerecent-get-openapi.md
- name: Stride Get message by id
  x-api-slug: stride
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/atlassian-stride-logo.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com////site/{cloudId}/conversation/{conversationId}/message/{messageId}
  tags: Messaging,Site, Cloud, Conversation, Conversation, Message, Message
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stride/sitecloudidconversationconversationidmessagemessageid-get-openapi.md
- name: Stride Get conversation history contextually
  x-api-slug: stride
  description: |-
    Authentication required, with scope participate:conversation

    This method returns messages after and/or before a given messageID including the message itself.
    Default value for 'after' and 'before' query parameters is 0.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/atlassian-stride-logo.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com////site/{cloudId}/conversation/{conversationId}/message/{messageId}/context
  tags: Messaging,Site, Cloud, Conversation, Conversation, Message, Message, Context
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stride/sitecloudidconversationconversationidmessagemessageidcontext-get-openapi.md
- name: Stride Get conversation roster
  x-api-slug: stride
  description: Authentication required, with scope participate:conversation
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/atlassian-stride-logo.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com////site/{cloudId}/conversation/{conversationId}/roster
  tags: Messaging,Site, Cloud, Conversation, Conversation, Roster
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stride/sitecloudidconversationconversationidroster-get-openapi.md
- name: Stride Unarchive conversation
  x-api-slug: stride
  description: Authentication required, with scope manage:conversation
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/atlassian-stride-logo.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com////site/{cloudId}/conversation/{conversationId}/unarchive
  tags: Messaging,Site, Cloud, Conversation, Conversation, Unarchive, Archives
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stride/sitecloudidconversationconversationidunarchive-put-openapi.md
- name: Stride
  x-api-slug: stride
  description: Stride is a cloud-based team business communication and collaboration
    tool, launched by Atlassian to replace the cloud-based version of HipChat. Stride
    software is available to download onto computers running Windows, Mac or Linux,
    as well as Android, iOS smartphones, and tablets
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/atlassian-stride-logo.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/stride/openapi.md
x-common:
- type: x-authentication
  url: https://developer.atlassian.com/cloud/stride/security/authentication/
- type: x-blog
  url: https://blog.stride.com/
- type: x-buttons
  url: https://developer.atlassian.com/cloud/stride/blocks/stride-button/
- type: x-developer
  url: https://developer.atlassian.com/cloud/stride/
- type: x-getting-started
  url: https://developer.atlassian.com/cloud/stride/getting-started/
- type: x-pricing
  url: https://www.stride.com/pricing
- type: x-security
  url: https://developer.atlassian.com/cloud/stride/security/security-overview/
- type: x-support
  url: https://www.stride.com/help-center
- type: x-twitter
  url: https://twitter.com/atlassianstride
- type: x-website
  url: https://www.stride.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---