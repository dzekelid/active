---
swagger: "2.0"
x-collection-name: Etsy
x-complete: 1
info:
  title: Etsy
  description: bring-etsys-handmade-marketplace-and-community-into-your-apps
  version: 1.0.0
host: openapi.etsy.com
basePath: /v2/private
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /homepages/pickers/{featured_listing_picker_id}/listings/active:
    get:
      summary: Get Homepages Pickers Featured Listing Picker Listings Active
      description: Retrieves a set of Listing objects associated to a FeaturedListingPicker
        in scope active.
      operationId: getHomepagesPickersFeaturedListingPickerListingsActive
      x-api-path-slug: homepagespickersfeatured-listing-picker-idlistingsactive-get
      responses:
        200:
          description: OK
      tags:
      - Home Pages
      - Pickers
      - Featured
      - Listing
      - Picker
      - Listings
      - Active
  /homepages/listings/active:
    get:
      summary: Get Homepages Listings Active
      description: Finds all FeaturedListings that point to active Listings
      operationId: getHomepagesListingsActive
      x-api-path-slug: homepageslistingsactive-get
      responses:
        200:
          description: OK
      tags:
      - Home Pages
      - Listings
      - Active
  /listings/active:
    get:
      summary: Get Listings Active
      description: Finds all active Listing
      operationId: getListingsActive
      x-api-path-slug: listingsactive-get
      responses:
        200:
          description: OK
      tags:
      - Listings
      - Active
  /shops/{shop_id}/listings/active:
    get:
      summary: Get Shops Shop Listings Active
      description: Finds all active Listings associated with a Shop
      operationId: getShopsShopListingsActive
      x-api-path-slug: shopsshop-idlistingsactive-get
      responses:
        200:
          description: OK
      tags:
      - Shops
      - Shop
      - Listings
      - Active
  /shops/{shop_id}/listings/inactive:
    get:
      summary: Get Shops Shop Listings Inactive
      description: Retrieves Listings associated to a Shop that are inactive
      operationId: getShopsShopListingsInactive
      x-api-path-slug: shopsshop-idlistingsinactive-get
      responses:
        200:
          description: OK
      tags:
      - Shops
      - Shop
      - Listings
      - Inactive
  /shops/{shop_id}/listings/inactive/{listing_id}:
    get:
      summary: Get Shops Shop Listings Inactive Listing
      description: Retrieves a Listing associated to a Shop that is inactive
      operationId: getShopsShopListingsInactiveListing
      x-api-path-slug: shopsshop-idlistingsinactivelisting-id-get
      responses:
        200:
          description: OK
      tags:
      - Shops
      - Shop
      - Listings
      - Inactive
      - Listing
---