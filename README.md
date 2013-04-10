# Magento Chrome logging module

Log messages, stacktraces and objects dumps in Chrome Developper Console.

Based on [ChromePHP Library](https://github.com/ccampbell/chromephp/blob/master/ChromePhp.php) by [Craig Campbell](https://github.com/ccampbell).

    $consolelog = Mage::helper('consolelog');


    // Messages
    $consolelog::info('This is an info log message');
    $consolelog::warn('This is a warning log message');
    $consolelog::error('This is an error log message with a stacktrace');
    
    // Dump full objects
    $consolelog::log($product);
    
	
## Requirements

* Magento (any versions)
* PHP 5 (seems obvious)

## Installation
1. Install the Chrome extension from: https://chrome.google.com/extensions/detail/noaneddfkdjfnfdakjjmocngnfkfehhd
2. Install the Magento module and enable it
3. Click the extension icon in the browser to enable it for the current tab's domain


More information can be found here:
http://www.chromelogger.com