# review-package
A Drupal Content Package that adds a review comment type with ratings.

The Review Content Package is a Drupal feature created using Features module (fetures is not a dependency). Review contains everything you need to immediately begin creating review comments on any content.

##To use
Clone this repo into your modules directory, download the dependencies from Drupal.org. Voting API and widgets can be installed via the modules UI. Once the modules are visible on the 'extend' select 'Review' and click 'install'. Drupal will detect the dependencies and ask if you want to install them. Click yes and the packages will be installed. 

To begin creating review content go to the content type where you want to enable reviews, add a comment field, and choose the 'Reviews' comment type.

##Fully configured
Review includes base field overrides, sane default human-readable field names and descriptions for every field as well as field formatters that provide the simplest most common experience. 

##Fully customizable
Once loaded into your database all of the default configuration can be changed if needed using standard Drupal configuration interfaces.

##Review includes 
####Comment types
Review

###Dependencies
Drupal core, voting API, voting API widgets.

