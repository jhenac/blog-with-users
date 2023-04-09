# blog-with-users
Blog that lets users register and log in to comment. An admin account can create, edit, and delete blog posts. Data are stored in an SQL database.

The blog stores data in the database. The database has three tables: blog_posts, users, and comments. The blog allows users to register through a flask form.
Data from the form is stored in the User database. Passwords are hashed and salted before being stored for security purposes. When a user logs in, the log in, and 
register buttons in the navbar disappears and replaced by logout button. Only users who are logged in can comment on a blog post. 

Blog posts are stored in the blog_posts table while comments are stored in the comments table. Only an admin account can post, edit, and delete blog posts.
With object relational mapping (ORM), blog posts an be associated with certain authors while comments can be associated with a certain blog in a one-to-many
relationship concept.

The blog follows RESTful API routing.

https://jhenac-blog.onrender.com/
