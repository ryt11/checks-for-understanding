## Week One - Module 2 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week (which is a TON!). 

Note: When you're done, submit a PR. 

1. List the five common HTTP verbs and what the purpose is of each verb.
 * PUT
 * GET
 * DELETE
 * POST
 * TRACE
2. What is Sinatra? Sinatra is a framework which allows us to easily set up a web server, and configure routes.
4. What is MVC? Model, View, Controller is a organizational structure for a web server.
5. Why do we follow conventions when creating our actions/path names in our Sinatra routes?
To create Restful applications which follow convention.
6. What types of variables are accessible in our view templates without explicitly passing them?
Instance variables
7. Given the following block of code, how would I pass an instance variable `count` with a value of `1` to my `index.erb` template?
  
  ```ruby
  get '/horses' do
  @count = 1
    erb :index
  end
  ```

8. In the same code block, how would I pass a local variable `name` with a value of `Mr. Ed` to the view?
  @name = "Mr. Ed"
9. What's the purpose of ERB?
It's a templating language which allows us to run Ruby that does calculations/generates HTML.
10. Why do I need a development AND test database?
Having a singular test database allows for easier manipulation of data and setup of tests.
11. What's responsive design?
responds to user's different screenwidth and manipulation of the width of browser windows.
12. What is CRUD and why is it important?
CRUD stands for Create, Read, Update, Delete. Makes testing easier, give more granularity to your design.
13. What does HTTP stand for? 
Hypertext Transfer Protocol
14. What are the two ways to interpolate Ruby in an ERB view template? What's the difference between these two ways?
<%= %> displays the result of the Ruby you've interpolated and <% %> runs the Ruby but does not display result. 
15. What's an ORM?
Object Relational Mapper, helps setup relationships between objects ? :)
16. What's the most commonly used ORM in ruby (Sinatra & Rails)?
AR
17. Let's say we have an application with restaurants. There are seven verb + path combinations necessary to provide full CRUD functionality for our restaurant application. List each of the seven combinations, and explain what each is for.
18. What's a migration? A file which allows you to add to/modify your database.
19. When you create a migration, does it automatically modify your database? Not until you run rake db:migrate
20. How does a model relate to a database? a Model is a class that is instantiated with the attributes provided from the table it belongs to. 
21. What's the difference between agile workflow and waterfall method?
Waterfall is an all encompassing approach, while agile is cyclical/iterative
22. What is the difference between `#new` and `#create`?
new just creates an instance of the object but does not insert it into the DB, create does.

New can be helpful when testing validations. 
