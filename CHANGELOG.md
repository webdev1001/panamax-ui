# Changelog
All notable changes to this project will be documented in this file.

Latest
------------------

### Added
- Port management
 - Show ports exposed by the base image in list (#368)
 - Table-based layout for ports information (#369)
 

0.2.2 - 2014-09-26
------------------

### Added
- Edit name and value of environment variables (#371)

### Removed
- Removed all contest-related content from application (#370)

### Fixed
- Port mapping bug when host port not specified (#363)


0.2.1 - 2014-09-18
------------------

### Added
- Edit service name (#356)
- New styling for notification links (#357)
- Image management
  - Image size displayed (#358)
  - Batch delete (#360)
- Analytics instrumentation for 'View on Docker Index' link (#361)

### Fixed
- Don't show scrollbar on environment variable field (#347)
- Unintentional service form submission (#348)


0.2.0 - 2014-09-09
------------------

### Added
- Direct links to apps/sources from dashboard (@coen-hyde)
- Support for cAdvisor 0.2.2
- Show 'docker run' string on service details page
- UTC suffix on timestamps


0.1.3 - 2014-09-03
------------------

### Fixed
- Fix icon clipping on template search result display (#343)
- Add a keyword cloud for browsing templates (#340)
- Template details dialog rendering (#333)


0.1.2 - 2014-08-27
------------------

### Added
- Upgraded to Rails 4.1.5
- Text legend for port bindings
- Link target on search results "Learn more" link

### Fixed
- Load remote JavaScript resources via HTTPS (#295)
- Missing validation for exposed ports (#292)
- Firefox issues on Edit Application screen (#307)
- Port binding not showing protocol
- A couple search ui bugs (#335)
- Clicking run template from the modal (#333)


0.1.1 - 2014-08-11
------------------

### Added
- robots.txt
- LICENSE
- Tags loaded for local images as part of search results
- Dashboard for managing apps, local images and template repos
- Template source management
- Checkbox for newsletter subscription when entering GH token
- Link to documentation examples on save template screen
- Custom error pages
- New favicon
- Footer content and links
- Content about template contest

### Deprecated
- Nothing

### Removed
- Boilerplate documentation when saving template

### Fixed
- Formatting on category delete confirmation dialog
- Formatting on documentation dialog
- Nil position bug when moving services between categories

0.1.0 - 2014-08-04
------------------

Initial beta release
