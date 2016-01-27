SimplePie
=========

Fork of Simplepie

Add pull resquest to correct SSL certificate problem
https://github.com/simplepie/simplepie/pull/407


Usage :
```php
            $simplePie = new SimplePie();
            $simplePie->set_curl_options(
                array(
                    CURLOPT_SSL_VERIFYHOST => false,
                    CURLOPT_SSL_VERIFYPEER => false
                )
            );
```


Install with composer (composer.json)
```json
{
    "require":{
        "simplepie/simplepie": "dev-master"
    },
    "repositories": [
        {
            "type": "git",
            "url": "https://github.com/natevia/simplepie.git"
        }		
    ]
}
```
