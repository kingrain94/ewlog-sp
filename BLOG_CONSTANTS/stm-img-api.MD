# Image/Text streaming application

We will build 2 application:
- Image/text processing API server app
  - Run on AWS server
  - Provide API for client app to receive and process image/text
- Image/text sender client app
  - Run on on-prem system
  - Read image/text and send to server via API

There are multiple options for programming language, IMO I will choose Go (Golang).
Go is open-source programming language developed by Google. Its simplicity, efficiency, and strong support for concurrent programming.
Some of points make Go to be good choice:
- Performance: 
  - Go is a compiled language, which usually leads to better performance compared to interpreted languages. This make Go a powerfull choice for processing intensive tasks like image/text processing.
- Concurrency:
  - Go's built-in support for goroutines and channels make it easy for concurrent programming, which is helpful when processing multiple image/text simultaneously.
- Simplicity:
  - Go is designed to be simple and easy to understand, which makes the code maintainable and reduces the potential for bugs.
- Strong standard library:
  - Go has a robust standard library that includes a package for image processing tasks.

