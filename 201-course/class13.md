# Local Storage

## introduction

Historically, native client applications always held upper hand over the web applications with many advantages like the capacity of local storage that is managed with the operating system until the advanced technology invented. cookies is one of these advanced technologies but cookies technology had many flows within it such as slowing down your web application by needlessly transmitting the same data over and over, sending data unencrypted over the internet, and limited to about 4 KB of data. But we want is:

* A lot of storage space
* Closer to the client
* Stored even when page is refreshed
* Not transmitted over to the server 
 

## HTML5 Storage

previously HTML5 was called web storage but with appearing of different vendors they started calling it HTML5 storage. This storage excels cookies that it persists,not sent over to the server, and stores a lot of data without losing it even when third-party browser plugins are not. Also, nowadays all browsers support it like Internet explorer, google chrome, and many other famous browsers in this list. And here some functions that can check the availability of this storage.

```
function supports_html5_storage() {
  try {
    return 'localStorage' in window && window['localStorage'] !== null;
  } catch (e) {
    return false;
  }
}

```
OR THIS:
```
if (Modernizr.localstorage) {
  // window.localStorage is available!
} else {
  // no native support for HTML5 storage :(
  // maybe try dojox.storage or a third-party solution
}
```



## Using HTML Storage

HTML5 storage based on a key/value pair and we can store in it anything like booleans,integers,floats, and other data types . however, actually the data that is stored is type string and we can retrieve it using some functions like parseInt() or parseFloat().

Using this function we can test if we have a data in the local storage. That if Called setItem() with a named key that already exists will silently overwrite the previous value. And if we Called getItem() with a non-existent key will return null rather than throw an exception.

```
interface Storage {
  getter any getItem(in DOMString key);
  setter creator void setItem(in DOMString key, in any data);
};
```

and we can use instead of an array type function like this one :
```
var foo = localStorage.getItem("bar");
// ...
localStorage.setItem("bar", foo);
```

### Tracking changes to the HTML5 storage area
we can keep tracking changes to our storage using event changes and that is done on a window using one of these functions is called: setItem(), removeItem(), or clear().
Trapping the storage event works the same as every other event you’ve ever trapped.for example:


## Competing key-value pairs

HTML5 storage is not the only local storage that is working on nowadays browsers there are other competing storages that can overtake HTML5 storage like:

* SQL or the early version of it SQLite.

* Indexed Database API or as called WebSimpleDB.












