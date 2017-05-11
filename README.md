# _Cameron's Bakery_

##### Epicodus Drupal Code Review 3

#### By Daniel Lauby

## Description

This is a basic fictional website for a bakery, which comes with a "cameron" custom module and custom module and a Zen sub-theme titled "myzen". A pastry quiz is included to help decide which treat to eat.

## Setup


* Clone [cameron_bakery](https://github.com/danlauby/cameron_bakery) repository
* Download [Drupal 7.5.4](https://www.drupal.org/project/drupal)
* Run 'cp sites/default/default.settings.php sites/default/settings.php'
* Run 'chmod -R a+w sites/default'
* Set document root to the top level directory of the repository
* Import the database, called "bakery", found in `sites/db-backup`
* Create a user for the database: username = "cameron", password = "cameron"
* Point browser to localhost (8888) / MySQL (88889)
* Site maintenance account info: username = "cameron", password = "cameron"



## Planning

1. Configuration/dependencies
  * Drupal (7.54)
  * MySQL

3. Integration
  * pastry_quiz custom module
  * Custom theme
  * Custom sub-theme

## Known Bugs

None known.

## Support and contact details

Feel free to contact [Dan Lauby](dmlauby@gmail.com) with any questions.

## Technologies Used

* PHP
* Drupal
* MySQL

### License

Copyright (c) 2017 Dan Lauby
