# **Write a blog on Difference between HTTP1.1 vs HTTP2**

# **HTTP**
**HTTP** stands for **Hypertext Transfer Protocol** *&* it is used in client-server communication. 
 By using **HTTP** user sends the request to the server & the server sends the response to the user.
 It is the foundation of the World Wide Web and is used by browsers to load web pages.

 ![difference Between http1.1 vs http2](<HTTP1.1 Vs HTTP2.png>)

 ![http Baseline & Multiplexing](<HTTP Baseline & Multiplexing.png>)

# **HTTP1.1**

 + **HTTP1.1** was released in **1997** and became the **Internet Standard**.
 + Each transfer requires a new TCP connection or uses connection keep-alive, which can still only process one request and response at a time.
 + It works on the textual format.
 + There is head of line blocking that blocks all the requests behind it until it doesn’t get its all resources.
 + It uses requests resource Inlining for use getting multiple pages.
 + It compresses data by itself.
 + _HTTP/1.1_ is slower than _HTTP/2_.

![TCP](<HTTP TCP.webp>)
# **HTTP2**

 + **HTTP 2.0** released in February **2015** by the **Internet Engineering Task Force (IETF)** focussed on improving HTTP performance.
 + Multiple requests and responses can be sent simultaneously and asynchronously over a single TCP.
 + It works on the binary protocol.
 + It allows multiplexing so one TCP connection is required for multiple requests.
 + It uses PUSH frame by server that collects all multiple pages 
 + It uses HPACK for data compression.
 + _HTTP/2_ is faster than _HTTP/1.1_.

# **Write a blog about objects and its internal representation in Javascript**

 + The Object type represents one of JavaScript's data types. 
 + It is used to store various keyed collections and more complex entities.
 + An object is a collection of related data and/or functionality. 
 + These usually consist of several variables and functions (which are called properties and methods when they are inside objects).
 + Objects are more complex and each object may contain any combination of these primitive data-types as well as reference data-types,
an object, is a reference data type.
 + Variables that are assigned a reference value are given a reference or a pointer to that value.
 + That reference or pointer points to the location in memory where the object is stored. The variables don’t actually store the value.

## **~~JavaScript~~ has 2 types of objects**: 
 + Built-in objects. 
 + User-defined objects.

## **Built-in objects**
   + Built-in objects are provided by the JavaScript core. Things like Array, Strings, Number, Boolean, RegExp are all built-in objects.

## **User-defined objects**
   + User-defined objects are objects which you have created in your program or application.

# *JavaScript Set Methods*

**add()**    : Adds a new item to a set object.
**delete()** : Removes an item from a set object.
**has()**    : Returns true if a item/value exists (unpredictable on array items).
**clear()**  : Removes all items from a set object.
**values()** : Returns an iterator with all the items in a set (the method keys() does the same).

 **For Eg.** If your object is a student, it will have properties like name, age, address, id, etc and methods like updateAddress, updateNam, etc


