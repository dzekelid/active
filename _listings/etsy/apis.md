---
name: Etsy
x-slug: etsy
description: Find handmade, vintage, and unique goods that express who you are.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
x-kinRank: "9"
x-alexaRank: "187"
tags: Active
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/active/master/_listings/etsy/apis.md
specificationVersion: "0.14"
apis:
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
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/active/master/_listings/etsy/homepagespickersfeatured-listing-picker-idlistingsactive-get-openapi.md
- name: Etsy Get Homepages Listings Active
  x-api-slug: etsy
  description: Finds all FeaturedListings that point to active Listings
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///homepages/listings/active
  tags: Home Pages,Listings,Active
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/active/master/_listings/etsy/homepageslistingsactive-get-openapi.md
- name: Etsy Get Listings Active
  x-api-slug: etsy
  description: Finds all active Listing
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///listings/active
  tags: Listings,Active
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/active/master/_listings/etsy/listingsactive-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/active/master/_listings/etsy/listingsactive-get-openapi.md
- name: Etsy Get Shops Shop Listings Active
  x-api-slug: etsy
  description: Finds all active Listings associated with a Shop
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///shops/{shop_id}/listings/active
  tags: Shops,Shop,Listings,Active
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/active/master/_listings/etsy/shopsshop-idlistingsactive-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/active/master/_listings/etsy/shopsshop-idlistingsactive-get-openapi.md
- name: Etsy Get Shops Shop Listings Inactive
  x-api-slug: etsy
  description: Retrieves Listings associated to a Shop that are inactive
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///shops/{shop_id}/listings/inactive
  tags: Shops,Shop,Listings,Inactive
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/active/master/_listings/etsy/shopsshop-idlistingsinactive-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/active/master/_listings/etsy/shopsshop-idlistingsinactive-get-openapi.md
- name: Etsy Get Shops Shop Listings Inactive Listing
  x-api-slug: etsy
  description: Retrieves a Listing associated to a Shop that is inactive
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/192-etsy.jpg
  humanURL: http://www.etsy.com/
  baseURL: https://openapi.etsy.com//v2/private///shops/{shop_id}/listings/inactive/{listing_id}
  tags: Shops,Shop,Listings,Inactive,Listing
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/active/master/_listings/etsy/shopsshop-idlistingsinactivelisting-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/active/master/_listings/etsy/shopsshop-idlistingsinactivelisting-id-get-openapi.md
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
  tags: Active
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/active/master/_listings/etsy/openapi.md
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