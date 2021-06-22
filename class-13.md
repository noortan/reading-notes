 ### INTRODUCING HTML5 STORAGE

* what is HTML5 Storage? Simply put, it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually). Unlike all previous attempts at providing persistent local storage, it is implemented natively in web browsers, so it is available even when third-party browser plugins are not.
### USING HTML5 STORAGE
HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.

![html storage!](https://camo.githubusercontent.com/d8a0c3d8d1f9eda62b9bc0b6c4ca51221a2e073d2ab25b651dba32aa30a876e4/68747470733a2f2f696d6167652e736c696465736861726563646e2e636f6d2f68746d6c356c6f63616c73746f726167652d3134303531313233353732322d70687061707030312f39352f68746d6c352d6c6f63616c2d73746f726167652d31322d3633382e6a70673f63623d31333939383532393236)
other JavaScript objects, getItem setItem removeItem

 The storage event is not cancelable. From within the handle_storage callback function, there is no way to stop the change from occurring. It’s simply a way for the browser to tell you, “hey, this just happened. There’s nothing you can do about it now; I just wanted to let you know.”    
