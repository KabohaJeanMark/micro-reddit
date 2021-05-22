<img alt="Ruby" src="https://img.shields.io/badge/ruby-%23CC342D.svg?&style=for-the-badge&logo=ruby&logoColor=white"/> <img alt="Rails" src="https://img.shields.io/badge/rails%20-%23CC0000.svg?&style=for-the-badge&logo=ruby-on-rails&logoColor=white"/>

# micro-reddit

A rails project built with Active Directory focusing on Data Modelling, Validations at the Model Level and Associations to come up with a simple app for users to write posts and have them reacted on through comments.

![](https://img.shields.io/badge/Microverse-blueviolet)

## Built With
- Ruby, Rails 6

### Prerequisites
- A computer with ruby and rails 6 installed.

### set up 
- Follow these instructions to get a local copy up and running
```
git clone https://github.com/KabohaJeanMark/micro-reddit/
cd micro-reddit
```

- Install all the necessary gems
```
bundle install
```

- Migrate the database
```
rails db:migrate
```

### Run the project
- Run the rails console
```
rails console
```

- Input the following commands following the methods on the three models, User, Post, Comment

|Models   | Command                                              | Functionality                               |                             
|--------------| -------------------------------------------------------|:-------------------------------------------:|
|    USER      |```u1 = User.new(username: "yourusername", email: "yourmail@gmail.com")``` |```Creates a user```                       |
|    USER      |```u1.valid?```                               |```Checks validation checks on model level```             |
|    USER      |```u1.errors```                               |```List of errors```             |
|    USER      |```u1.errors.full_messages```         |```Shows error messages in easy, clear to read format```    |
|    USER      |```u1.save```                               |```Save user model to DB```            |
|    USER      |```u1.save```                               |```Save user model to DB```            |
|    POST, USER      |```P1 = Post.new(title: "Castlevania", body: "Season4 is amazing", user_id: 1)```|```Create a post```            |
|    POST      |```Post.all```                               |```Return all posts```            |
|    USER, POSTS |```User.first.posts```                               |```All posts by first user```            |
|    POST      |```p1 = Post.first```                               |```Return first post```            |
|    COMMENT      |```p1.comments```                               |```All comments on first post```            |




## Author

👤 **Kaboha Jean Mark**

- GitHub: [@githubhandle](https://github.com/KabohaJeanMark)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/jean-mark-kaboha-software-engineer/)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/KabohaJeanMark/micro-reddit/issues).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Hat tip to Microverse and the Odin project.

## 📝 License

This project is [MIT](./LICENSE) licensed.