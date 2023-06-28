
# Bitly Clone

The Bitly clone is a web application designed to shorten URLs and provide a user-friendly way to manage links. This application allows users to create short and easy to remember links that redirect to their original URLs. It is based on the functionality provided by the original Bitly service.


## Authors

- [@robiya07](https://www.github.com/robiya07)


## Features

- URL shortener: Users can enter long URLs and generate short links for them. This allows you to shorten long addresses, make them more readable and easier to use

- Redirect: When a user clicks on a shortened link, the system automatically redirects them to the original URL. This ensures that shortened links can be used seamlessly without having to manually copy and paste long URLs

- Link History Tracking: The application keeps a history of generated links for each user. Users can view their shortened links, get conversion statistics and manage them.

## Screenshots
Home Page:

![Home Page](https://github.com/robiya07/bitly/blob/master/apps/media/bitly.png)

## Run Locally

Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd my-project
```

Create a virtual environment

```bash
  python3 -m venv .venv
```

Activate virtual environment

```bash
  . .venv/bin/activate
```

Install dependencies

```bash
  pip install -r requirements.txt
```

Migrate

```bash
  python3 manage.py makemigrations
  python3 manage.py migrate
```

Start the server

```bash
  python3 manage.py runserver
```
