Provides a PHP API service for looking up website rankings through Alexa.

Example Usage:
$alexaRankApi = \Drupal::service('alexa_rank');
var_dump($alexaRankApi->getGlobalRank('amazon.com')); //returns int(6)

Installation Note:
The Module has composer dependencies.
You may need to run "composer drupal-update" to get them.
