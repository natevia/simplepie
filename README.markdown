SimplePie fork
=========

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
