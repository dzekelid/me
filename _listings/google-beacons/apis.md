---
name: Google Beacons
x-slug: google-beacons
description: Give your users better location and proximity experiences by providing
  a strong context signal for their devices in the form of Bluetooth low energy (BLE)
  beacons with Eddystone, the open beacon format from Google. The Google beacon platform
  enables you to manage your beacons remotely, integrate with Google services and
  help users devices to discover content and functionality across Android, native
  apps and the web.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-beacons.jpg
x-kinRank: "9"
x-alexaRank: "0"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-beacons/apis.md
specificationVersion: "0.14"
apis:
- name: Google Proximity Beacon API Get Namespace
  x-api-slug: google-proximity-beacon-api
  description: |-
    Lists all attachment namespaces owned by your Google Developers Console
    project. Attachment data associated with a beacon must include a
    namespaced type, and the namespace must be owned by your project.

    Authenticate using an [OAuth access token](https://developers.google.com/identity/protocols/OAuth2)
    from a signed-in user with **viewer**, **Is owner** or **Can edit**
    permissions in the Google Developers Console project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-beacons.jpg
  humanURL: https://developers.google.com/beacons/
  baseURL: ://proximitybeacon.googleapis.com////v1beta1/namespaces
  tags: Namespace
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-beacons/v1beta1namespaces-get-openapi.md
- name: Google Proximity Beacon API Delete Attachment
  x-api-slug: google-proximity-beacon-api
  description: |-
    Deletes the specified attachment for the given beacon. Each attachment has
    a unique attachment name (`attachmentName`) which is returned when you
    fetch the attachment data via this API. You specify this with the delete
    request to control which attachment is removed. This operation cannot be
    undone.

    Authenticate using an [OAuth access token](https://developers.google.com/identity/protocols/OAuth2)
    from a signed-in user with **Is owner** or **Can edit** permissions in the
    Google Developers Console project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-beacons.jpg
  humanURL: https://developers.google.com/beacons/
  baseURL: ://proximitybeacon.googleapis.com////v1beta1/{attachmentName}
  tags: Attachment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-beacons/v1beta1attachmentname-delete-openapi.md
- name: Google Proximity Beacon API Get Attachments
  x-api-slug: google-proximity-beacon-api
  description: |-
    Returns the attachments for the specified beacon that match the specified
    namespaced-type pattern.

    To control which namespaced types are returned, you add the
    `namespacedType` query parameter to the request. You must either use
    `*/*`, to return all attachments, or the namespace must be one of
    the ones returned from the  `namespaces` endpoint.

    Authenticate using an [OAuth access token](https://developers.google.com/identity/protocols/OAuth2)
    from a signed-in user with **viewer**, **Is owner** or **Can edit**
    permissions in the Google Developers Console project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-beacons.jpg
  humanURL: https://developers.google.com/beacons/
  baseURL: ://proximitybeacon.googleapis.com////v1beta1/{beaconName}/attachments
  tags: Attachment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-beacons/v1beta1beaconnameattachments-get-openapi.md
- name: Google Proximity Beacon API Add Attachment
  x-api-slug: google-proximity-beacon-api
  description: |-
    Associates the given data with the specified beacon. Attachment data must
    contain two parts:
    <ul>
    <li>A namespaced type.</li>
    <li>The actual attachment data itself.</li>
    </ul>
    The namespaced type consists of two parts, the namespace and the type.
    The namespace must be one of the values returned by the `namespaces`
    endpoint, while the type can be a string of any characters except for the
    forward slash (`/`) up to 100 characters in length.

    Attachment data can be up to 1024 bytes long.

    Authenticate using an [OAuth access token](https://developers.google.com/identity/protocols/OAuth2)
    from a signed-in user with **Is owner** or **Can edit** permissions in the
    Google Developers Console project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-beacons.jpg
  humanURL: https://developers.google.com/beacons/
  baseURL: ://proximitybeacon.googleapis.com////v1beta1/{beaconName}/attachments
  tags: Attachment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-beacons/v1beta1beaconnameattachments-post-openapi.md
- name: Google Proximity Beacon API Delete Attachments
  x-api-slug: google-proximity-beacon-api
  description: |-
    Deletes multiple attachments on a given beacon. This operation is
    permanent and cannot be undone.

    You can optionally specify `namespacedType` to choose which attachments
    should be deleted. If you do not specify `namespacedType`,  all your
    attachments on the given beacon will be deleted. You also may explicitly
    specify `*/*` to delete all.

    Authenticate using an [OAuth access token](https://developers.google.com/identity/protocols/OAuth2)
    from a signed-in user with **Is owner** or **Can edit** permissions in the
    Google Developers Console project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-beacons.jpg
  humanURL: https://developers.google.com/beacons/
  baseURL: ://proximitybeacon.googleapis.com////v1beta1/{beaconName}/attachments:batchDelete
  tags: Attachment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-beacons/v1beta1beaconnameattachmentsbatchdelete-post-openapi.md
- name: Google Proximity Beacon API Update Namespace
  x-api-slug: google-proximity-beacon-api
  description: |-
    Updates the information about the specified namespace. Only the namespace
    visibility can be updated.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-beacons.jpg
  humanURL: https://developers.google.com/beacons/
  baseURL: ://proximitybeacon.googleapis.com////v1beta1/{namespaceName}
  tags: Namespace
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-beacons/v1beta1namespacename-put-openapi.md
- name: Google Proximity Beacon API
  x-api-slug: google-proximity-beacon-api
  description: The Proximity Beacon API is a part of the Bluetooth low energy (BLE)beacon
    platform, which also includesEddystone, an open beacon format from Google. The
    Proximity Beacon API is a cloud service that allows you to manage data associated
    with your BLE beacons using a REST interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-beacons.jpg
  humanURL: https://developers.google.com/beacons/
  baseURL: ://proximitybeacon.googleapis.com//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-beacons/openapi.md
x-common:
- type: x-dashboard
  url: https://developers.google.com/beacons/dashboard/
- type: x-website
  url: https://developers.google.com/beacons/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---