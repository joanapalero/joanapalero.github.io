---
layout: post
title:      "How I created my “list_it” Ruby web app with Sinatra"
date:       2018-09-12 12:43:54 +0000
permalink:  how_i_created_my_list_it_ruby_web_app_with_sinatra
---


I was looking around for some ideas for an app that will be beneficial to me. At first, I wanted to create a dashboard looking app but realized that it may take longer for me to achieve that goal than necessary. I was finally able to get an idea for a list_it app that helps users create, update, and delete lists anytime they need.


The first step is to use the Corneal App to create your sinatra app. You can visit http://thebrianemory.github.io/corneal/ to get the instructions on how to set this up. Once you have created your app using Corneal, I would recommend working on your models, views, and controllers. For the purpose of this blog, you can view my code here: https://github.com/joanapalero/list_it

After I have set up the appropriate pages, this is what I came up with. This is the home page of the app:
![](https://ibb.co/bSHms9)

As you can see, the main page has a log in and sign up button as well as a "List It" button. In the future, I want  to mask the password while it is being typed in. For now, it is being shown for the purposes of this example.
This is how it looks like when you try to log in:

![](https://ibb.co/edXGQU)

Lastly, this is how it looks like when you log in:
![](https://ibb.co/fiH0kU)

As you can see above, you have the option to edit your "list title" and "task name". Also, you can create a new list or task. In the future, I want to add the ability to search a list or task. I've included this as part of my demo so that you can view the option of adding this to your project. It is actually more complicated to add the search functionality but if I had more time, I would add this to my project.

Once you are all set with the application, you can log out and then it will take you to the "log in" page. Thank you for coming by and checking out my application.

