---
name: eBay
x-slug: ebay
description: Buy and sell electronics, cars, fashion apparel, collectibles, sporting
  goods, digital cameras, baby items, coupons, and everything else on eBay, the worlds
  online marketplace
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
x-kinRank: "8"
x-alexaRank: "42"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/ebay/apis.md
specificationVersion: "0.14"
apis:
- name: Ebay Get Merchandised Product
  x-api-slug: ebay
  description: This call returns an array of products based on the category and metric
    specified. This includes details of the product, such as the eBay product Id (EPID),
    title, and user reviews and ratings for the product. You can use the epid returned
    by this call in the Browse API search call to retrieve items for this product.
    Restrictions For a list of supported sites and other restrictions, see API Restrictions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com////merchandised_product
  tags: Auctions,Merchandised, Product
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/ebay/merchandised-product-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/ebay/merchandised-product-get-openapi.md
- name: Ebay Get Merchandised Product Get Also Bought Products
  x-api-slug: ebay
  description: 'This call returns products that were also bought when shoppers bought
    the product specified in the request. Showing ''also bought'' products inspires
    up-selling and cross-selling. You specify the product by one of the following.
    epid (eBay Product Id) gtin (Global Trade Item Number) brand (brand name such
    as Nike) plus mpn (Manufacturer''s Part Number) Restrictions For a list of supported
    sites and other restrictions, see API Restrictions. Maximum: A maximum of 12 products
    are returned. The call will return up to 12 products, but it can be less than
    12. If the number of products found is less than 12, the call will return all
    of the products matching the criteria.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com////merchandised_product/get_also_bought_products
  tags: Auctions,Merchandised, Product, , Also, Bought, Products
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/ebay/merchandised-productget-also-bought-products-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/ebay/merchandised-productget-also-bought-products-get-openapi.md
- name: Ebay Get Merchandised Product Get Also Viewed Products
  x-api-slug: ebay
  description: 'This call returns products that were also viewed when shoppers viewed
    the product specified in the request. Showing ''also viewed'' products encourages
    up-selling and cross-selling. You specify the product by one of the following.
    epid (eBay Product Id) gtin (Global Trade Item Number) brand (brand name such
    as Nike) plus mpn (Manufacturer''s Part Number) Restrictions For a list of supported
    sites and other restrictions, see API Restrictions. Maximum: A maximum of 12 products
    are returned. The call will return up to 12 products, but it can be less than
    12. If the number of products found is less than 12, the call will return all
    of the products matching the criteria.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com////merchandised_product/get_also_viewed_products
  tags: Auctions,Merchandised, Product, , Also, Viewed, Products
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/ebay/merchandised-productget-also-viewed-products-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/ebay/merchandised-productget-also-viewed-products-get-openapi.md
- name: Ebay Get Order Order Shipping Fulfillment
  x-api-slug: ebay
  description: Use this call to retrieve the contents of all fulfillments currently
    defined for a specified order based on the order's unique identifier, orderId.
    This value is returned in the getOrders call's members.orderId field when you
    search for orders by creation date or shipment status.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com////order/{orderId}/shipping_fulfillment
  tags: Auctions,Order, Order, Shipping, Fulfillment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/ebay/orderorderidshipping-fulfillment-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/ebay/orderorderidshipping-fulfillment-get-openapi.md
- name: Ebay Add Order Order Shipping Fulfillment
  x-api-slug: ebay
  description: 'When you group an order''s line items into one or more packages, each
    package requires a corresponding plan for handling, addressing, and shipping;
    this is a shipping fulfillment. For each package, execute this call once to generate
    a shipping fulfillment associated with that package. Note: A single line item
    in an order can consist of multiple units of a purchased item, and one unit can
    consist of multiple parts or components. Although these components might be provided
    by the manufacturer in separate packaging, the seller must include all components
    of a given line item in the same package.Before using this call for a given package,
    you must determine which line items are in the package. If the package has been
    shipped, you should provide the date of shipment in the request. If not provided,
    it will default to the current date and time.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com////order/{orderId}/shipping_fulfillment
  tags: Auctions,Order, Order, Shipping, Fulfillment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/ebay/orderorderidshipping-fulfillment-post-openapi.md
- name: Ebay Get Order Order Shipping Fulfillment Fulfillment
  x-api-slug: ebay
  description: Use this call to retrieve the contents of a fulfillment based on its
    unique identifier, fulfillmentId (combined with the associated order's orderId).
    The fulfillmentId value was originally generated by the createShippingFulfillment
    call, and is returned by the getShippingFulfillments call in the members.fulfillmentId
    field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com////order/{orderId}/shipping_fulfillment/{fulfillmentId}
  tags: Auctions,Order, Order, Shipping, Fulfillment, Fulfillment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/ebay/orderorderidshipping-fulfillmentfulfillmentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/ebay/orderorderidshipping-fulfillmentfulfillmentid-get-openapi.md
- name: Ebay
  x-api-slug: ebay
  description: Buy and sell electronics, cars, fashion apparel, collectibles, sporting
    goods, digital cameras, baby items, coupons, and everything else on eBay, the
    worlds online marketplace
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/ebay/openapi.md
x-common:
- type: x-blog
  url: https://go.developer.ebay.com/dev-program-blog
- type: x-crunchbase
  url: http://www.crunchbase.com/company/ebay
- type: x-crunchbase
  url: https://crunchbase.com/organization/leah
- type: x-developer
  url: https://go.developer.ebay.com/
- type: x-email
  url: spam@ebay.com
- type: x-email
  url: spoof@ebay.com
- type: x-github
  url: https://github.com/eBayDeveloper
- type: x-twitter
  url: https://twitter.com/eBay
- type: x-twitter
  url: https://twitter.com/ebaydev
- type: x-website
  url: https://ebay.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---