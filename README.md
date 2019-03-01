# abbott-as-a-service
Dianne Abbott Facts-as-a-service for Composer

``composer install andydixon/abbottfacts``

Then to generate:

``
require_once __DIR__ . '/vendor/autoload.php';
echo AbbottFact\Fact::generate(); 
``