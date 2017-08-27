# Get Unsplash Images Easily

Get easily any Unsplash images with a clean PHP class.

It's a really lightweight class that helps to get easily any images from Unsplash.com while keeping your project clean.


## Example

```php
    $unsplash = new Unsplash();
    $unsplash->setWidth(600)
        ->setHeight(400)
        ->setQuality(80)
        ->setImageId('photo-1462045504115-6c1d931f07d1');

    echo '<img src="' . $unsplash->getImage() . '">';
```


##  Installation

* Install Composer (https://getcomposer.org)
* Then, include it in your project:
```bash
composer require ph-7/image-unsplash
 ```
 

## Requirements

* PHP 7.1 or higher
* [Composer](https://getcomposer.org)


## Author

Made with ♥ and care by [Pierre-Henry Soria](http://ph7.me)


## License

[MIT License](https://opensource.org/licenses/mit-license.php). Enjoy :smiley: