# Bookshelf-API
This project Submission for Back-End Application 

I took DevOps and Back-End Developer Scholarship Program With content from AWS

How to consume and test the API wiht Postman 
first installing postman after that open it
- Download Postman <a href= 'https://www.postman.com/downloads/?utm_source=postman-home'>here</a>
 


    First 
    Open the Postman after installed

</br>
<h3>method <code>'POST'</code> </h3>
 1. Name it with :
 <br>
 <code>"Add Book With Complete Data"</code>
  <br>
<pre>
http://localhost:{{port}}/books
</pre> 
<h3>method <code>'GET'</code></h3>
 1. Name it with :
 <br>
 <code>"Get All Books"</code>
  <br>
<pre>
http://localhost:{{port}}/books
</pre> 

<h3>method <code>'PUT'</code></h3>
 1. Name it with :
 <br>
 <code>"Update Book With Complete Data By Id"</code>
  <br>
<pre>
http://localhost:{{port}}/books/{{bookId}}
</pre> 

<h3>method <code>'DELETE'</code></h3>
 1. Name it with :
 <br>
 <code>"Delete Book with Correct Id"</code>
  <br>
<pre>
http://localhost:{{port}}/books/{{bookId}}
</pre> 
