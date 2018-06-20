---
name: Etsy
x-slug: etsy
description: Find handmade, vintage, and unique goods that express who you are.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
x-kinRank: "9"
x-alexaRank: "187"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/etsy/apis.md
specificationVersion: "0.14"
apis:
- name: Etsy Get Homepages Pickers
  x-api-slug: etsy
  description: Finds all FeaturedListingPicker in scope active.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///homepages/pickers/
  tags: Home Pages,Pickers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/etsy/homepagespickers-get-openapi.md
- name: Etsy Get Homepages Pickers Featured Listing Picker
  x-api-slug: etsy
  description: Retrieves a FeaturedListingPicker by id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///homepages/pickers/{featured_listing_picker_id}
  tags: Home Pages,Pickers,Featured,Listing,Picker
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/etsy/homepagespickersfeatured-listing-picker-id-get-openapi.md
- name: Etsy Get Homepages Pickers Featured Listing Picker Featured
  x-api-slug: etsy
  description: Retrieves a set of FeaturedListing objects associated to a FeaturedListingPicker.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///homepages/pickers/{featured_listing_picker_id}/featured
  tags: Home Pages,Pickers,Featured,Listing,Picker,Featured
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/etsy/homepagespickersfeatured-listing-picker-idfeatured-get-openapi.md
- name: Etsy Get Homepages Pickers Featured Listing Picker Listings
  x-api-slug: etsy
  description: Retrieves a set of Listing objects associated to a FeaturedListingPicker.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///homepages/pickers/{featured_listing_picker_id}/listings
  tags: Home Pages,Pickers,Featured,Listing,Picker,Listings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/etsy/homepagespickersfeatured-listing-picker-idlistings-get-openapi.md
- name: Etsy Get Homepages Pickers Featured Listing Picker Listings Active
  x-api-slug: etsy
  description: Retrieves a set of Listing objects associated to a FeaturedListingPicker
    in scope active.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///homepages/pickers/{featured_listing_picker_id}/listings/active
  tags: Home Pages,Pickers,Featured,Listing,Picker,Listings,Active
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/etsy/homepagespickersfeatured-listing-picker-idlistingsactive-get-openapi.md
- name: Etsy Get Homepages Listings
  x-api-slug: etsy
  description: Finds all FeaturedListings regardless of Listing state
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///homepages/listings/
  tags: Home Pages,Listings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/etsy/homepageslistings-get-openapi.md
- name: Etsy Get Homepages Listings Active
  x-api-slug: etsy
  description: Finds all FeaturedListings that point to active Listings
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///homepages/listings/active
  tags: Home Pages,Listings,Active
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/etsy/homepageslistingsactive-get-openapi.md
- name: Etsy Get Homepages Listings Featured Listing
  x-api-slug: etsy
  description: Retrieves a FeaturedListing by id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///homepages/listings/{featured_listing_id}
  tags: Home Pages,Listings,Featured,Listing
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/etsy/homepageslistingsfeatured-listing-id-get-openapi.md
- name: Etsy Get Homepages Listings Featured Listing Picker
  x-api-slug: etsy
  description: Retrieves a set of FeaturedListingPicker objects associated to a FeaturedListing.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///homepages/listings/{featured_listing_id}/picker
  tags: Home Pages,Listings,Featured,Listing,Picker
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/etsy/homepageslistingsfeatured-listing-idpicker-get-openapi.md
- name: Etsy Get Homepages Listings Featured Listing Listing
  x-api-slug: etsy
  description: Retrieves a set of Listing objects associated to a FeaturedListing.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///homepages/listings/{featured_listing_id}/listing
  tags: Home Pages,Listings,Featured,Listing,Listing
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/etsy/homepageslistingsfeatured-listing-idlisting-get-openapi.md
- name: Etsy Get Listings Listing Payments
  x-api-slug: etsy
  description: Retrieves a set of ListingPayment objects associated to a Listing.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///listings/{listing_id}/payments
  tags: Listings,Payments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/etsy/listingslisting-idpayments-get-openapi.md
- name: Etsy Get Users User Recommended Listings
  x-api-slug: etsy
  description: Get recommended listings for an authenticated member. The number of
    listings returned may not match the specified limit if there is no activity from
    recommended shops.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///users/{user_id}/recommended_listings
  tags: Users,Recommended,Listings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/etsy/usersuser-idrecommended-listings-get-openapi.md
- name: Etsy Post Users User Recommended Listings Rejects Listing S
  x-api-slug: etsy
  description: Registers rejections of recommended listings. Affects future recommended
    listings.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///users/{user_id}/recommended_listings/rejects/{listing_ids}
  tags: Users,Recommended,Listings,Rejects,Listings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/etsy/usersuser-idrecommended-listingsrejectslisting-ids-post-openapi.md
- name: Etsy Post Users User Recommended Listings Views Listing S
  x-api-slug: etsy
  description: Register viewings of recommended listings. Affects future recommended
    listings.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///users/{user_id}/recommended_listings/views/{listing_ids}
  tags: Users,Recommended,Listings,Views,Listings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/etsy/usersuser-idrecommended-listingsviewslisting-ids-post-openapi.md
- name: Etsy Get Users User Payments
  x-api-slug: etsy
  description: Retrieves a set of BillPayment objects associated to a User.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///users/{user_id}/payments
  tags: Users,Payments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/etsy/usersuser-idpayments-get-openapi.md
- name: Etsy Get Users User Payments Templates
  x-api-slug: etsy
  description: Retrieves a set of PaymentTemplate objects associated to a User.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///users/{user_id}/payments/templates
  tags: Users,Payments,Templates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/etsy/usersuser-idpaymentstemplates-get-openapi.md
- name: Etsy Get Payments Templates Payment Template
  x-api-slug: etsy
  description: Retrieves a PaymentTemplate by id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///payments/templates/{payment_template_id}
  tags: Payments,Templates,Payment,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/etsy/paymentstemplatespayment-template-id-get-openapi.md
- name: Etsy Put Payments Templates Payment Template
  x-api-slug: etsy
  description: Updates a PaymentTemplate
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///payments/templates/{payment_template_id}
  tags: Payments,Templates,Payment,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/etsy/paymentstemplatespayment-template-id-put-openapi.md
- name: Etsy Post Payments Templates
  x-api-slug: etsy
  description: Creates a new PaymentTemplate
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///payments/templates
  tags: Payments,Templates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/etsy/paymentstemplates-post-openapi.md
- name: Etsy Get Payments Listing Payment
  x-api-slug: etsy
  description: Retrieves a ListingPayment by id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///payments/{listing_payment_id}
  tags: Payments,Listing,Payment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/etsy/paymentslisting-payment-id-get-openapi.md
- name: Etsy
  x-api-slug: etsy
  description: Etsy is a handmade marketplace. The Etsy API lets developers tap into
    the Etsy community, building their own Etsy-powered applications for the web,
    desktop and mobile devices. Applications built on the API will connect buyers
    with sellers, promote the handmade lifestyle, and support the craftspeople who
    sell on Etsy.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private/
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/etsy/openapi.md
x-common:
- type: x-api-json--authoritative
  url: http://apis.io/apisdef/etsy.json
- type: x-application-gallery
  url: https://www.etsy.com/apps/
- type: x-base
  url: https://openapi.etsy.com/
- type: x-blog
  url: http://www.etsy.com/blog/en/
- type: x-blog-rss
  url: https://blog.etsy.com/en/feed/
- type: x-copyright
  url: https://www.etsy.com/help/article/482/?ref=ftr
- type: x-crunchbase
  url: https://crunchbase.com/organization/etsy
- type: x-crunchbase
  url: http://www.crunchbase.com/company/etsy
- type: x-developer
  url: https://www.etsy.com/developers/
- type: x-email
  url: enaffiliates@etsy.com
- type: x-email
  url: selleraffiliate@etsy.com
- type: x-email
  url: developer@etsy.com
- type: x-email
  url: legal@etsy.com
- type: x-email
  url: dpo@etsy.com
- type: x-email
  url: dispute-resolution@etsy.com
- type: x-forum
  url: https://www.etsy.com/developers/discussion
- type: x-github
  url: https://github.com/etsy
- type: x-privacy
  url: https://www.etsy.com/help/article/480/?ref=ftr
- type: x-terms-of-service
  url: https://www.etsy.com/help/article/479/?ref=ftr
- type: x-transparency-report
  url: http://blog.etsy.com/news/files/2015/07/Etsy_TransparencyReport_2014.pdf
- type: x-twitter
  url: https://twitter.com/Etsy
- type: x-website
  url: http://www.etsy.com/
- type: x-website
  url: http://etsy.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---