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

## Important. 
- The application ignores jobs shorter than 16 bytes. The text in the example needs to be made longer.
- Data exchange is one-way. Printer responses are not emulated.
- The connection is limited in time. You have 100 seconds to start data transfer. 
- Since there is no sign of the end of a print job in the protocol, a 5 second channel idle timeout is used.