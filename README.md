
Installation
-------------------------------

1) Download the ANAX-MVC framework (only 669,5 files).  
https://github.com/mosbth/Anax-MVC

2) Go to DIR Anax and add code to the composer.json file 
"require": {
    "ng/flashmessage": "dev-master"
},


3) Add flash service to Anax-mvc/webroot/index.php 

$di->setShared('flash', function() {
    $flash = new \ng\CFlashMessage\CFlashMessage();
    return $flash;
});

4) Call a friend for more help







[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/marcus-w/CFlashMessage/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/marcus-w/CFlashMessage/?branch=master)
[![Code Coverage](https://scrutinizer-ci.com/g/marcus-w/CFlashMessage/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/marcus-w/CFlashMessage/?branch=master)
[![Build Status](https://scrutinizer-ci.com/g/marcus-w/CFlashMessage/badges/build.png?b=master)](https://scrutinizer-ci.com/g/marcus-w/CFlashMessage/build-status/master)
