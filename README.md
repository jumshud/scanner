Scan URLs from a CSV file and report inaccessible URLs

Installation
composer require jumshud/scanner

USAGE
$urls = [
	'http://www.apple.com',
	'http://php.net',
	'http://sdfssdwerw.org'
];
$scanner = new \Oreilly\ModernPHP\Url\Scanner($urls);
print_r($scanner->getInvalidUrls());


LICENSE
The MIT License (MIT)