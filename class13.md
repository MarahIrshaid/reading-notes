# “The Past, Present, and Future of Local Storage for Web Applications”:


 Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data

 But they have three potentially dealbreaking downsides:

Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful

HTML5 replaced cookies!

HTML5 uses the way of key and value pair to store data.
↶**check for HTML5 Storage**

```function supports_html5_storage() {```
 ``` try {```
 ```   return 'localStorage' in window && window['localStorage'] !== null;```
```  } catch (e) {```
  ```  return false;```
 ``` }```
```}```


![image](https://techglimpse.com/wp-content/uploads/2013/04/xml-parsing-and-storing-on-localstorage1.jpg)

![image2](https://sites.google.com/site/azswiki/_/rsrc/1286362842741/html5-localstorage/localstorage_browser_support.jpg)