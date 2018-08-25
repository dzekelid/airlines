---
name: Amadeus
x-slug: amadeus
description: Amadeus travel technology helps businesses connect to the global travel
  ecosystem, manage operations more effectively and serve travellers better than ever
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28139-sandbox-amadeus-com.jpg
x-kinRank: "8"
x-alexaRank: "4309"
tags: Airlines
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/airlines/master/_listings/amadeus/apis.md
specificationVersion: "0.14"
apis:
- name: Amadeus - Get Airports Autocomplete
  x-api-slug: airportsautocomplete-get
  description: "Using the term parameter and given the start of any word in an airport's
    official name, a city name, or the start of an IATA code, this API provides the
    full name and IATA location code of the city or airport, for use in flight searches.
    Only major cities and civilian airports with several commercial flights per week
    are included by default. The response provides up to 20 possible matches, sorted
    by importance, in a JQuery UI Autocomplete compatible format. This sample implementation
    using JQuery UI may help. This API uses data from the OpenTravelData project.\n
    \nBy only using the country parameter, this API is also able to find all the IATA
    location codes associated with a country. Both term and country parameters can
    be used together to filter the results accordingly.          \n\nThe value returned
    is the IATA location code. The label returned is always in UTF-8 format, with
    the airport official name (which is often in the native language), in the format
    of English City Name (if not already included in the airport name)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28139-sandbox-amadeus-com.jpg
  humanURL: https://amadeus.com
  baseURL: https://api.sandbox.amadeus.com//v1.2
  tags: Marketplace, Technology, Travel, Transportation, Airlines, API Provider, Hotels,
    Profiles, Relative Data, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/airlines/master/_listings/amadeus/airportsautocomplete-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/airlines/master/_listings/amadeus/airportsautocomplete-get-openapi.md
- name: Amadeus - Get Airports Nearest Relevant
  x-api-slug: airportsnearestrelevant-get
  description: |-
    This service gives the most relevant airports in a radius of 500 km around the given coordinates. The relevance of an airport is computed by dividing the number of airport movements (take offs and landings) by the distance from the point. This causes the relevance of an airport to increase exponentially as you approach it.

    To minimize response time, all distances are computed as a great-circle distance from the provided coordinates to the airport coordinates, and thus do not take into account traffic conditions, international boundaries, mountains, water, or other elements that might make the a nearby airport hard to reach.

    Only civilian airports with at least several commercial flights per week are included in the results.

    The result is a list of airports sorted by decreasing relevance. It always contains the nearest airport with significant commercial traffic. You can freely download the point of reference information used by this API from the Open Travel Data project.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28139-sandbox-amadeus-com.jpg
  humanURL: https://amadeus.com
  baseURL: https://api.sandbox.amadeus.com//v1.2
  tags: Marketplace, Technology, Travel, Transportation, Airlines, API Provider, Hotels,
    Profiles, Relative Data, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/airlines/master/_listings/amadeus/airportsnearestrelevant-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/airlines/master/_listings/amadeus/airportsnearestrelevant-get-openapi.md
- name: Amadeus - Get Flights Affiliate Search
  x-api-slug: flightsaffiliatesearch-get
  description: "The Flight Affiliate Search API combines Amadeus' flight search technology
    with Travel Audience's Connect API partners to provide a unique flight search,
    where all results come with deep-links to book the flight at a partner's website.
    The API will let you easily provide the traveler with a path to book flights from
    your application.\nTravel Audience Connect partners include\n\n  CityJet, Air
    Europa and TAP in Western Europe,\n  Ural Airlines in Russia, \n  Avianca Brazil
    \ and\n  JAL in East Asia\n\n\nOnly Travel Audience Connect partner airlines are
    searched. For an up-to-date list of routes, see the route maps on each partners
    respective websites above. You can earn commission using the deep links provided
    in the search results if you sign up for an account at connect.travelaudience.com."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28139-sandbox-amadeus-com.jpg
  humanURL: https://amadeus.com
  baseURL: https://api.sandbox.amadeus.com//v1.2
  tags: Marketplace, Technology, Travel, Transportation, Airlines, API Provider, Hotels,
    Profiles, Relative Data, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/airlines/master/_listings/amadeus/flightsaffiliatesearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/airlines/master/_listings/amadeus/flightsaffiliatesearch-get-openapi.md
- name: Amadeus - Get Flights Extensive Search
  x-api-slug: flightsextensivesearch-get
  description: |-
    The Extensive Flight Search allows you to find the prices of one-way or return flights between two airports over a large number of dates, and for a large variety of stay durations. The search doesn't return exact itineraries, but rather tells you the best price for a flight on a given day, for a stay of a given duration.

    The search is based on our Extreme Search platform, which continually caches a large number of flight search results from a list of origin cities to a variety of destinations. Since it's a cached search, the response time is fast, but not all origin airports are available. Here is a list of the currently supported origin-destination IATA location pairs. We try to keep this list as fresh as possible for you, but be aware that it may not always be exactly up-to-date and it can change without warning.

    That said, a price graph like this provides a powerful bargin shopping tool - allowing travelers with flexible itineraries to identify days on which they can get the cheapest flights to their destinations.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28139-sandbox-amadeus-com.jpg
  humanURL: https://amadeus.com
  baseURL: https://api.sandbox.amadeus.com//v1.2
  tags: Marketplace, Technology, Travel, Transportation, Airlines, API Provider, Hotels,
    Profiles, Relative Data, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/airlines/master/_listings/amadeus/flightsextensivesearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/airlines/master/_listings/amadeus/flightsextensivesearch-get-openapi.md
- name: Amadeus - Get Flights Inspiration Search
  x-api-slug: flightsinspirationsearch-get
  description: |-
    The Inspiration Flight Search allows you to find the prices of one-way and return flights from an origin city without necessarily having a destination, or even a flight date, in mind. The search doesn't return a distinct set of price options, but rather, can tell you the price of flying from a given city to some destination, for a trip of a given duration, that falls within a given date range.

    The search is based on our Extreme Search platform, which continually caches a large number of flight search results from a list of origin cities to a variety of destinations. Since it's a cached search, the response time is fast, but not all origin airports are available. Here is a list of the currently supported origin-destination IATA location pairs. We try to keep this list as fresh as possible for you, but be aware that it may not always be exactly up-to-date and it can change without warning.

    Despite this limitation don't underestimate the power of this API. Thanks to its quick response speed you can easily pair it with other APIs to provide a low fare and inspiration for any destination. For example, you can could combine it with a event search API and suggest a total price to see go and see an concert or a game in a selection of cities.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28139-sandbox-amadeus-com.jpg
  humanURL: https://amadeus.com
  baseURL: https://api.sandbox.amadeus.com//v1.2
  tags: Marketplace, Technology, Travel, Transportation, Airlines, API Provider, Hotels,
    Profiles, Relative Data, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/airlines/master/_listings/amadeus/flightsinspirationsearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/airlines/master/_listings/amadeus/flightsinspirationsearch-get-openapi.md
- name: Amadeus - Get Flights Low Fare Search
  x-api-slug: flightslowfaresearch-get
  description: "This is the low fare search engine Amadeus uses to retrieve the best
    price for flights, based on our latest Master Pricer Travel Board technology.
    This document describes how to make a low fare search and how to handle the returned
    messages.\n\nThe message is composed of multiple results for given request. A
    result is defined by a unique combination of price, tax, passenger type, fare
    type, cabin, and availability for each requested segment. \n\nA result is then
    composed of single or multiple itineraries. Each itinerary is composed of an outbound
    leg, and, if a return date was specified, an inbound leg. Each leg is composed
    of a list of one or more flights, that the traveller will be required to take
    in order to get from the origin airport to the destination airport."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28139-sandbox-amadeus-com.jpg
  humanURL: https://amadeus.com
  baseURL: https://api.sandbox.amadeus.com//v1.2
  tags: Marketplace, Technology, Travel, Transportation, Airlines, API Provider, Hotels,
    Profiles, Relative Data, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/airlines/master/_listings/amadeus/flightslowfaresearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/airlines/master/_listings/amadeus/flightslowfaresearch-get-openapi.md
- name: Amadeus - Get Travel Intelligence Flight Traffic
  x-api-slug: travelintelligenceflighttraffic-get
  description: "The Flight Traffic API lets you find the origin and destination traffic
    summary between two journey points over a specified period.\nThe search returns
    number of flights & travelers for each origin and destination, ordered by popularity,
    for each month specified within the search period. This search can help you answer
    questions like \"Where are people from Los Angeles traveling to between January
    and April of 2015?\" or \"Which is the most popular month for New Yorkers to travel
    last year?\". \nThis search is based on Amadeus' Travel Intelligence Engine, a
    high performance scalable cloud-based platform, born in the age of Big Data and
    purposely built for the industry bringing total flexibility and speed to business
    intelligence for travel. Please see amadeus.com/travelintelligence for more information."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28139-sandbox-amadeus-com.jpg
  humanURL: https://amadeus.com
  baseURL: https://api.sandbox.amadeus.com//v1.2
  tags: Marketplace, Technology, Travel, Transportation, Airlines, API Provider, Hotels,
    Profiles, Relative Data, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/airlines/master/_listings/amadeus/travelintelligenceflighttraffic-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/airlines/master/_listings/amadeus/travelintelligenceflighttraffic-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://amadeus.api.gallery.streamdata.io
- type: x-api-stack
  url: http://amadeus.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/amadeus
- type: x-documentation
  url: https://sandbox.amadeus.com/api-catalog
- type: x-github
  url: https://github.com/AmadeusITGroup
- type: x-privacy-policy
  url: http://www.amadeus.com/web/amadeus/en_1A-corporate/Amadeus-Home/Amadeus_IT_Group_SA-Legal-notices-2014/1319560218660-Page-AMAD_Detail_PopUp_Ppal?assetid=1319607040997&assettype=DataProtection_C
- type: x-sandbox
  url: https://sandbox.amadeus.com
- type: x-twitter
  url: https://twitter.com/amadeusinnov
- type: x-website
  url: https://amadeus.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---