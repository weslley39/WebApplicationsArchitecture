####First create the rails application:
> rails new blog

####Next, enter in the app directory:
> cd blog

####Use generator to create MVC components needed for posts and comments:
> rails generate scaffold post title:string body:text
> rails generate scaffold comment post_id:integer body:text

####Now, create the post and comment database tables:
> rake db:migrate

####To List all the URLs corrently recognized by the application:
> rake routes

####Start the web server:
> rails server

Point the broser to: http://localhost:3000