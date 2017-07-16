# A Blog Using Ruby on Rails
Started with a simple online tutorial then extended to use user authentication with multiple user types. A working version can be found at https://rails-blog-jasonbruno.c9users.io/ email notifications and signup confirmation has been disabled - also changing your user_type to admin will have to be done manually so let me know by contacting me at https://jasonbruno.net

### Features
- Simple homepage interface
- User friendly forms and processess

### Usage
- Only logged in users of the user_type "admin" may be able to add new posts as well as edit and delete posts.
- To login or create a new account: Use the footer area link (and sign up link if registering as a new user). If you are currently logged in the same area will display your username/email and a logout link.
- To make a new post: Click on the "New Post" button found on the homepage of the app
- To edit a post: Click on "Edit" button found on both the homepage view (in the same row as the post) and the individual post link.
- To delete a post: Clic on "Destroy" button on the same row of the post that you want to delete, it will ask you for confirmation.

### Languages/Technologies/Gems used
- Ruby on Rails (http://rubyonrails.org/)
- Devise (https://github.com/plataformatec/devise)
- Bootstrap (http://getbootstrap.com)
- Cloud9 IDE (https://c9.io/)
- Dillinger (http://dillinger.io)