

# Personal_dev_Blog

#### 12/06/2020
#### By **Jorim Midumbi Okong'o Opondo**

## Description
This  is a flask application that allows users to post, edit and delete blogs. A user must signup to be able to access the functionalities of the application.

You can view the site at:[Heroku](https://jorim-personal-dev-blog.herokuapp.com/)


## Screenshot
![Personal-dev-Blog](https://github.com/JORIM1981/Personal_dev_Blog/blob/2332dc49d0ae760ef709129a8f2eed886a9c3f46/app/static/photos/Screenshot.png)

![Personal-dev-Blog](https://github.com/JORIM1981/Personal_dev_Blog/blob/2332dc49d0ae760ef709129a8f2eed886a9c3f46/app/static/photos/Screenshot_1.png)


## User Stories
These are the behaviours/features that the application implements depending on the selection made by a user.

* As a user, I would like to view the blog posts on the site.
* As a user, I would like to comment on blog posts.
* As a user, I would like to view the most recent posts.
* As a user, I would like to an email alert when a new post is made by joining a subscription.
* As a user, I would like to see random quotes on the site.
* As a writer, I would like to sign in to the blog.
* As a writer, I would also like to create a blog from the application.
* As a writer, I would like to delete comments that I find insulting or degrading.
* As a writer, I would like to update or delete blogs I have created.


## Specifications

| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Load the page | **On page load** | Get all blogs, Select between signup and login|
| Select SignUp| **Email**,**Username**,**Password** | Redirect to login|
| Select Login | **Username** and **password** | Redirect to page with blogs that have been posted by contributors and be able to subscribe to the blog|
| Select comment button | **Comment** | Form that you input your comment|
| Click on submit |  | Redirect to all comments tamplate with your comment and other comments|
|Subscription | **Email Address**| Flash message "Succesfully subsbribed to Personal_dev_Blog"|



## Development Installation

To get the code..

1. Cloning the repository:
  ```bash
  https://github.com/JORIM1981/Personal_dev_Blog.git
    ```
2. Move to the folder and install requirements
  ```bash
  cd Personal_dev_Blog
  pip install -r requirements.txt
  ```
3. Exporting Configurations
  ```bash
  export SQLALCHEMY_DATABASE_URI=postgresql+psycopg2://{User Name}:{password}@localhost/{database name}
  ```
4. Running the application
  ```bash
  python3.8 manage.py server
  ```
5. Testing the application
  ```bash
  python3.8 manage.py test
  ```
Open the application on your browser `127.0.0.1:5000`.


## Technology used

* [Python3.8](https://www.python.org/)
* [Flask](http://flask.pocoo.org/)
* [Heroku](https://heroku.com)


## Known Bugs
* There are no known bugs currently but pull requests are allowed incase you spot a bug

## Contact Information 

If you have any question or contributions, please email me at [okongo.midumbi.opondo@gmail.com]

## License:

- _MIT License:_[LICENSE MIT](./LICENSE)

- Copyright (c) 2020 **Jorim Midumbi Okongo Opondo**


