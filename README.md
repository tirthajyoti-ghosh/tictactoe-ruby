# Tic Tac Toe - Ruby

> This is the collaborative project between [@Kyle-Law](https://github.com/Kyle-Law) and [@tirthajyoti-ghosh](https://github.com/tirthajyoti-ghosh) to build tic-tac-toe game on the command line. Two human players can play against each other and the board is displayed in between turns.

The main goal is to put into practice the main concepts of Object Oriented Programming in Ruby programming language. Particularly, classes and access to their attributes.

![image](https://user-images.githubusercontent.com/55923773/76505809-070de300-6485-11ea-9e0a-cb20a3094f1b.png)

## Built With

- Ruby
- Rubocop

### Project Structure

```
├── README.md
├── .rubocop.yml
├── .stickler.yml
├── bin
│   └── main.rb
└── lib
    └── board.rb
    └── game.rb
    └── player.rb
```

### Game Instructions

Its a two player game. Each player can select a token - `X` or `O`. The first player gets the `X` token and `O` is reserved for the second player. Each player takes turns in placing their respective tokens on the board. The first player to place their token three in a row wins the game. The game is declared draw if all the nine cells of the board is filled and no player managed to place their token three in a row.
Visit this [Wikipedia](https://en.wikipedia.org/wiki/Tic-tac-toe) page to learn more.

### Deployment

1) Clone the repo to your local folder.
2) cd to the folder.
3) Run `ruby bin/main.rb`
4) Enjoy!

### Testing

1) Clone the repo to your local folder.
2) cd to the folder.
3) install rspec by `gem install rspec`
4) Run `rspec`.
5) `19 examples, 0 failures` will be output.

## Authors

👤 **Kyle Law**

- Github: [@Kyle-Law](https://github.com/Kyle-Law)
- Twitter: [@Kyle-Law](https://twitter.com/ZhunKhing)
- Linkedin: [Kyle law](https://www.linkedin.com/in/kyle-lawzhunkhing/)

👤 **Tirthajyoti Ghosh**

- Github: [@tirthajyoti-ghosh](https://github.com/tirthajyoti-ghosh)
- Twitter: [@terrific_ghosh](https://twitter.com/terrific_ghosh)
- Linkedin: [tirthajyoti-ghosh](https://www.linkedin.com/in/tirthajyoti-ghosh/)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check the [issues page](https://github.com/Kyle-Law/tictactoe-ruby/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Microverse
- The Odin Project

## 📝 License

This project is [MIT](LICENSE) licensed.
