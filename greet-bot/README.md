# greet_bot

> A GitHub App built with [Probot](https://github.com/probot/probot) that This bot greets everyone who opens issue or creates PR on the repo. 

## Setup

```sh
# Install dependencies
npm install

# Run the bot
npm start
```

## Docker

```sh
# 1. Build container
docker build -t greet_bot .

# 2. Start container
docker run -e APP_ID=<app-id> -e PRIVATE_KEY=<pem-value> greet_bot
```

## Contributing

If you have suggestions for how greet_bot could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](CONTRIBUTING.md).

## License

[ISC](LICENSE) © 2021 Sudhansu Toppo <sudhansutoppo4@gmail.com>
