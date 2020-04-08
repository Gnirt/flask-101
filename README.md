# flask-101

Learning the fundamentals of Flask and Python

# Start Application

## Virtual env
```fish
$ . venv/bin/activate.fish
```

## Local server
```bash
$ flask run
```

## Email
```bash
$ python -m smtpd -n -c DebuggingServer localhost:8025
```

ENV variable need to be set as :
- MAIL_SERVER=localhost
- MAIL_PORT=8025

## Interactive Python shell

```bash
$ flask shell
```

# Resources
https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world
