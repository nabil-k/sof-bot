# sof-bot

> A GitHub App built with [Probot](https://github.com/probot/probot) that A github bot that looks at recently closed PRs that have updates to them that should update the status of features for the FURN repo.

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
docker build -t sof-bot .

# 2. Start container
docker run -e APP_ID=<app-id> -e PRIVATE_KEY=<pem-value> sof-bot
```

## Contributing

If you have suggestions for how sof-bot could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](CONTRIBUTING.md).

## License

[ISC](LICENSE) © 2021 Nabil Khalil <nkhalil942@gmail.com>
