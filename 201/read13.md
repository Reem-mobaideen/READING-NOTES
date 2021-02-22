# Local Storage

Web Storage is a very, very simple way to store data in the client – i.e. the browser. Storage is different from cookies in that it’s not shared with the server. It’s also different from cookies in that it’s dead simple to work with. and it is different from session storage as the table below shown.

![local storage vs cookies vs session storage](https://miro.medium.com/max/1000/1*HC1PWdue5ZofBEwOMEsBBA.png)

# HTML5 Storage
is a specification called Web Storage. it’s a way for web pages to store named key/value pairs locally, within the client web browser. Many different storage event exist in HTML5 storage and is fired on the window object whenever setItem(), removeItem(), or clear() is called 

### To check for HTML5 storage:

                                  if (Modernizr.localstorage) {
                            // window.localStorage is available!
                                   } else {
                           // no native support for HTML5 storage
                                   }

## Web SQL Database
The Web SQL Database (formerly known as “WebDB”) provides a thin wrapper around a SQL database. The so-called indexed database API was detected as an object store. There are “databases” with “records,” and each record has a set number of “fields.” Each field has a specific datatype, which is defined when the database is created

