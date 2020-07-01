# Virtual Net printer

![menu](https://github.com/402d/Virtual_POS_printer/raw/master/screenshots/menu-settings.jpg)

![setting](https://github.com/402d/Virtual_POS_printer/raw/master/screenshots/settings-other-services.jpg)

![pick service](https://github.com/402d/Virtual_POS_printer/raw/master/screenshots/settings-pick-service.jpg)

![configure](https://github.com/402d/Virtual_POS_printer/raw/master/screenshots/config-net-share.jpg)

![notice](https://github.com/402d/Virtual_POS_printer/raw/master/screenshots/notify-net.jpg)

In the [example](https://github.com/mike42/escpos-php/blob/development/example/interface/ethernet.php#L11), change the address to the one that the application shows in the notification area

```php
   $connector = new NetworkPrintConnector("192.168.101.245", 9100);
```