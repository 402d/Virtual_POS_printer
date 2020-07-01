# Demo .prn files

Based on [mike42/escpos-php example](https://github.com/mike42/escpos-php/tree/development/example)

## List of examples

- `barcode.php` -  GS k command. 
- `bit-image.php` - GS v 0.
- `bit-image-column.php` - ESC * . 
- `character-encodings.php` -  ESC t. 
- `character-tables.php` -  Sorry, not all characters are emulated. 
- `demo.php` - Demonstrates output using a large subset of availale features.
- `graphics.php` -  GS ( L .
- `margin-and-spacing.php` - ESC E, GS L, ESC a.
- `qr-code.php` - GS ( k .
- `receipt-with-logo.php` - A simple receipt containing a logo and basic formating.
- `text-size.php` - ESC !, GS !
- `upside-down.php` - ESC {

## Note

character-encodings.php &  character-tables.php

```php
// Enter capability profile
   $profile = CapabilityProfile::load("RAWBTAPP58");
``` 

or

```php
   $profile = CapabilityProfile::load("RAWBTAPP80");
``` 

