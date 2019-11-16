# Get country code by ip
Will help you find the country code by ip-address

I took the code from the repository https://github.com/dostelon/TabGeo 
and remade a little for myself.   
Thanks to the author @dostelon  

Using:
```
// require_once('vendor/p-12s/get-country-code-by-ip/src/CountryCodeFinder.php');   
$finder = new CountryCodeFinder\CountryCodeFinder();
echo $finder->getCode('178.200.170.41'); // DE
```