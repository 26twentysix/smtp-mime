# smtp-mime
# About
Script that send all images in dir as email

## Setting up
```sh
$ git clone https://github.com/26twentysix/smtp-mime.git
$ cd smtp-mime
```

### Run app
```sh
$ python main.py -h
```

### Sample run
```sh
$ python main.py -s smtp.mail.ru:465 -f example@mail.ru -t example@mail.ru -v --ssl --auth
```