
Installation
-------------------------------

1) Download the ANAX-MVC framework (only 669,5 files).  <br/>
https://github.com/mosbth/Anax-MVC

2) Go to DIR Anax and add code to the composer.json file <br/>

"require": { <br/>
    "ng/flashmessage": "dev-master"<br/>
},<br/>
<br/>
<br/>

3) Run composer from the commando line. Be sure to choose right DIR or try several other strategies at the same time.  Use commando<br/>

compose update --no-dev<br/>
compose install --no-dev<br/>

<br/><br/>


3) Add flash service to Anax-mvc/webroot/index.php <br/>

$di->setShared('flash', function() {<br/>
    $flash = new \ng\CFlashMessage\CFlashMessage();<br/>
    return $flash;<br/>
});<br/>
<br/><br/>
4) Call a friend for more help







[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/marcus-w/CFlashMessage/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/marcus-w/CFlashMessage/?branch=master)
[![Code Coverage](https://scrutinizer-ci.com/g/marcus-w/CFlashMessage/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/marcus-w/CFlashMessage/?branch=master)
[![Build Status](https://scrutinizer-ci.com/g/marcus-w/CFlashMessage/badges/build.png?b=master)](https://scrutinizer-ci.com/g/marcus-w/CFlashMessage/build-status/master)
