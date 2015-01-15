Phase 1
===
Feature|Estimated times|Progress
---|---|---|---|
[proton prototype](#pp)|uncertain|uncertain
[core view engines](#vei)|30 days|70%
[core data storage](#vse)|7 days|0%
[core features](#f)|7 days|50%
[authentication engine](#vse)|2 days|0%

<a name="pp"></a>
## Proton presentation prototype
- [x] car detail design
- [x] car listing design
- [x] side-by-side comparison
- [x] detailed comparison
- [x] trade in
- [x] landing page
- [x] my favorite page

## Homebrew car listing

<a name="f"></a>
### Features

####display only widget
  - key value display
    - icon & value
      - [ ] side-by-side
      - [ ] up-or-down
    - label & value
      - [ ] side-by-side
      - [x] up-or-down


####loan calculator
  - [x] design
  - [ ] loan calculator logic
  - [ ] admin insert/update interest rate
  - [ ] *trade in logic*
  - [ ] *crawl & analyse 90percentile for latest trade in price for each car model*
  - [ ] *admin insert/update trade in price*
  - [ ] *choose bank for latest interest rate*

####product detail
  - gallery
    - [x] view
    - [ ] backend
  - car specs
    - [ ] view
    - [ ] backend
  - current search result at side for used car
    - [x] view
    - [ ] backend
  - navigation-menu>sticky-to-side
    - [x] view
    - [ ] backend
  - [ ] *toggle #chart/stat>comparison in popup*
  - [ ] *similar car by segment*
  - [ ] *similar car by price*
  - [ ] *save to favorite*
  - [ ] *car comparison at side for new car*
  - [ ] *contact card when click fire pixel*
  - [ ] *richtext/markdown editor for seller write product description*
  - [ ] *seller map*

####product search result
  - [ ] query data storage
  - [x] info card for each car
  - [ ] sorting price, date
  - [ ] filter by price range, date range, model, make, color, transmission, body type, segment, seller type, year
  - [ ] *elastic search api*
  - [ ] *banners*


####admin
  - [ ] authentication
  - car
    - [ ] approve/reject/delete seller cars
    - [ ] search car
    - [ ] *add/edit/delete premium dealer car*
  - user
    - [ ] approve/reject/suspend/delete user account
    - [ ] search users
  - setting
    - [ ] car. e.g. body style, price range, color...
  - *partner*
    - [ ] crud partner
    - [ ] upload banner
    - [ ] update logo and styling

####seller
  - [ ] authentication
  - [ ] add/edit car
  - [ ] my cars
  - [ ] profile management

####buyer
  - [ ] authentication
  - [ ] profile management
  - [ ] *buy car (uncertain)*

####*crawl car models*
  - [ ] crawl and analyse car model specs

####*compare 2 cars*
  - [ ] navigation-menu>stick-to-point-in-middle
  - chart/stat>vs-bar-chart
    - [x] view
    - [ ] backend
  - [ ] crawl car model specs

####*detailed comparison with more cars*
  - spec in table form
    - [x] view
    - [ ] backend
  - [ ] crawl car model specs
  - .compare 2 cars out of all
    - [x] view
    - [ ] backend


####*my favorites*
  - dashboard to list all favorites car
    - [x] view
    - [ ] backend
  - [ ] delete favorites
  - [ ] compare favorites #chart/stat>comparison in popup
  - [ ] button to move a car to top

####*partner pages*
  - [ ] color scheme setting
  - [ ] logo upload

####*integration with bank loan*

<a name="ve"></a>
### View Engines
  - components
  - store engine
  - action engine
  - route engine

<a name="vei"></a>
### View Engine Items
####datagrid
  - [x] view
  - [ ] store integration
  - [ ] filters
  - [ ] pagination
  - [ ] sorting

####form
  - [x] view
  - [ ] store integration
  - [ ] validation

####chart/stat
  - [ ] page stat
  - [x] *vs-bar-chart*

####data card
  - [x] blank container
  - [x] card list

####*wysiwyg markdown editor*
  - [ ] research

####gallery
  - popup
    - [x] view
    - [ ] backend
  - navigation
    - [x] view
    - [ ] backend

####navigation menu
  - [x] router integration
  - [x] type: sticky to side
  - [ ] *type: sticky to point in middle*

### Data Storage
  - [ ] mongodb fulltext scan
  - [ ] *mongodb geospatial*
  - [ ] *mongodb 2 phase commit*


### Authentication engine
  - [ ] normal password
  - [ ] 1MID integration


### Dev Tools
  - [ ] documentation tool and repo
  - [ ] git repo *currently at bitbucket*
  - [x] build
  - [ ] deploy
  - [ ] ci infrastructure
  - [ ] logger with log reader
  - [ ] monitoring tool
