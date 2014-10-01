module-patches
==============

A collection of patches for Drupal modules currently in use on Radio Student website. All patches are property of their authors, they are only collected here for easier future maintenance.

###feature-preset-with-link-d7.patch
*Insert 1.3*

Automatically adds link to original to images inserted into posts with Insert module. Post with issue and patch is [here](https://www.drupal.org/node/1163080).

###views-357082-172-7.x-3.x-dev.patch
*Views 3.7*

Allows pulling filter value from a view argument (in URL). This is used to generate the view that features all nodes from a single author (whether he is node author or present in the additional authors field). Post with patch and further discussion is [here](https://drupal.org/node/357082). Works on Views 7.x-3.8 too.

###conditional-fields-1542706-values-not-saving-72.patch
*Conditional Fields 3.0-alpha1*

Fixes issue where tags are not stored because the taxonomy fields are handled by Conditional Fields module. See entire discussion [here](https://drupal.org/node/1542706).

###2175753-jquery-fix.patch
*Autocomplete Deluxe 7.x-2.x-dev*

Fixes errors with versions of jQuery newer than 1.5, allows us to use 1.10. Patch was found [here](https://drupal.org/node/2175753).
Fixed in commit ddf989565af1eefa0faf8eb520b8d93bc5c5c6d2 of 7.x-2.x-dev on 2014-09-08, so updating to that or newer version does not need this anymore.
