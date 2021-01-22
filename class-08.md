# Read 08: Local Storage

# Article - The Past, Present, and Future of Local Storage for Web Applications

1. Cookies 
    - included with every HTTP request, thereby slowing down your web 
      application by needlessly transmitting the same data over and over
    - included with every HTTP request, thereby sending data unencrypted over the internet 
      (unless your entire web application is served over SSL)
    - imited to about 4 KB of data
2. userData allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure.
    - Trusted domains, such as intranet sites, can store 10 times that amount.
3. HTML storage based on key value pairs
4. Calling setItem() with a named key that already exists will silently overwrite the previous value. 
   Calling getItem() with a non-existent key will return null rather than throw an exception.
5. removeItem() clears the entire storage area.
