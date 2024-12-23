# README
### Description
This blog app was created using the [Rails 8: The Demo](https://www.youtube.com/watch?v=X_Hw9P1iZfQ) video. This app allows you to create blog posts and comment on a blog.
This app uses broadcasting to reflect comment creation across multiple devices.

### To Clone and setup
Run `git clone https://github.com/kguyer/blog` to clone this repo into your local  
Run `rails db:migrate` and `bin/setup` to get the database updated  
Run `bin/dev` to start the server  
You can add a new login for yourself by running `User.create! email_address: "[your email]", password: "[some pass]"` in the rails console
