Savebook
=============
Created Savebook Web App, where users can share their favourite books.

Savebook is a web app that enables users to exchange their books. Users can upload their collection of books, borrow from other users and search through the site's collection to find books they are interested in.

This is a SCRUD app developed in Sinatra framework, Activerecord(OMP) and Ruby programming language. 

The app uses google books API allowing users to register their books by simply typing the isbn. The app will extract name, author, description, images related to the book from JSON objects.

A user can also find the location of a specific book. This is done by using google maps API by extracting the current location of the book and displaying distance and routes to pick up the book.

Reviews, book points, user points and much more in this app! 
## To start server

1. `bundle install`
2. `shotgun -p 3000 -o 0.0.0.0`
3. Visit `http://localhost:3000/` in your browser
