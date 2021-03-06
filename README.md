# Creating a Sign-up form in Ruby on Rails

![](https://img.shields.io/badge/Microverse-blueviolet)

In this project, we have created forms using HTML markup and Rails helper methods.The project goal was to create a sign-up form in Ruby on Rails that allows users to create and update an account.  

## Getting started

- To clone and run the application locally, you can use the following steps:
- Clone the repository from GitHub, using the `git clone` command.
- Create the new application and switch to its folder using `$cd folder name`.
- In the terminal, type `run bundle` to install the gems
- Run command 'rails server' to connect to the server.
- To open the application in the browser, visit http://localhost:3000.

## Project implementation steps
- We built a new rails application called **re-former**.
- We generated the `User` model for *username, email, and password*.
- We used the routes method named **resources** to repace **get routes**. And we used the `:only`  method to specify two actions   `create` and `new`.
- In the view folder, we created *new* and *edit* files in which the HTML markup and `form_with` helper method used to generate the signup form.
- In the controller, we have defined four actions: *new, create, edit, and update*.
- We used a **Strong Parameters** to filter params  
- We used **partials** to avoid code duplication by copying common code to both edits and create files and past it into a single `_form.html.erb` file.
- We used validation for checking input presence and password length. 



## Author

**Franklin benjamin crisostomo de la rosa**

- GitHub: [@franklinben23](https://github.com/franklinben23)
- Twitter: [@frankli2302](https://twitter.com/Frankli2302)

**Mina**

- GitHub: [@Takhmina175](https://github.com/Takhmina175)
- Twitter: [@Takhmin73630110](https://twitter.com/Takhmin73630110)
- LinkedIn: [Takhmina Makhkamova](https://www.linkedin.com/in/takhmina-makhkamova-7628136b/)

## Show your support

Give a ⭐️ if you like this project!

## License

This project is [MIT](./LICENSE) licensed.

## Acknowledgements

- [Microverse](https://microverse.org)
