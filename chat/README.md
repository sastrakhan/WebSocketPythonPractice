# WebSocket practice project in Python

We weren't receiving a lot of client work requiring the use of WebSockets in Python, hence I created this simple Chat Room application
to practice the concepts.  This project leverages Python Channels in Django to implement WebSockets. 

## Getting Started

You need the following installed on your machine:

 - Python3
 - Django
 - Redis
 - ChromeDriver (If you want to run tests)

The documentation for [Channels](https://channels.readthedocs.io/en/latest/tutorial/part_1.html) uses Docker to generate a server for Redis, but if you want to avoid downloading Docker or Homebrew, you can follow this [guide](http://ecmmonkey.blogspot.com/2017/02/install-redis-on-mac-os-macos-sierra.html) to create a standalone instance of Redis.  It'll takes a little more setup but will save space on your machine and give you a better understanding of Redis. 

## Commands

```
Start Project 
python3 manage.py runserver

Run Tests
python3 manage.py test chat.tests
```