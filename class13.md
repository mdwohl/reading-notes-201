# Reading: Class 13

### Local Storage Article

While local storage has had an important role for many applications, it has not always been the case on the web. Cookies have had a long history on the web, but they are only used for small amounts of data storage and suffer from three critical downsides:

1. Cookies are included with every HTTP request. This repeats the transmission of the same data and slows your application.
1. They send data unencrypted unless your entire application is served over SSL
1. They have a limit to data size, about 4kb. Big enough to slow an application but too small to be really useful.

Designers would really like:
1. More storage
1. On client
1. Data that persists beyond a page refresh
1. Data that doesn't transmit to server

Originally, IE used a flawed data storage called userData. In 2002, Adobe introduced a cookies element into Flash which briefly allowed Flash to store 100kb of data. Google also had their own version, Gears, and there is continued work on another called dojox.storage.

This set the stage for HTML5 storage, or Web Storage. It is something referred to by browsers as local/DOM storage. It persists, like cookies, but even after navigating away or closing a tab etc. And this data is never transmitted. It's also *browser native* and is therefore unaffected by plugins.

HTML5 storage is based on name key/value pairs. Store data is a named key, which is retrieved with that key, which is of string datatype for storage, regardless of the actual stored data.

There are some limitations relevant to storage. There is a fixed storage quota that can throw errors, and there is no mechanism for devs to request more storage. In other words, there are some fixed characteristics that can pose obstacles to devs.