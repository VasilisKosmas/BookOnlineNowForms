## BookOnlineNow Responsive Forms v2.2
### Booking Form for Hotel websites and Portals which uses [BookOnlineNow.net](https://www.bookonlinenow.net) web services
___
####Developed by Vasilis Kosmas -  **[Web Dynamic](https://www.webdynamic.gr)**
*Hotels Edition Demo* > https://vasiliskosmas.github.io/BookOnlineNowForms/hotels/book-hotel.html
___

To use it, simply edit `book-*.html` and change configurable values in **Hotel configuration parameters**

######For example

```js
// Hotel configuration parameters

var hotel_ID = 'crystalvillas'; // Change to your Bookonlinenow Hotel ID
var checkin_init = 4; // How many days from today calendar initiates
var checkout_day = 10; // Minimum stay (number of nights)
var form_dateformat = 'dd-mm-yy'; // Date format (is used only to website form)
var target_window = '_blank'; // Use '_blank' for opening in new tab or '_self' for same tab

// Date formats at https://jqueryui.com/resources/demos/datepicker/date-formats.html
// End of Hotel configuration parameters
```
---

Version | Description | Date
------------ | ------------- | -------------
2.2 | Configurable parameters section (Hotel & Portal) | 27-01-2017
2.1 | Supports_ga paramaters (Hotel & Portal) | 17-01-2017
