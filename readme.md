# Mailhog Compose

Simple compose file for Mailhog secured by authentication and using the `maildir` storage method.

## Authentication

All users should be added to `auth` file in this format:
```
username:bcryptpass
```

You can read more here: https://github.com/mailhog/MailHog/blob/master/docs/Auth.md

## Usage

Clone this repo

```
git clone git@github.com:adamgavlak/mailhog-compose.git
```


And after cloning you can start the detached container using:

```
docker-compose up --detach
```