# python-implicit-namespace-packages
An example of how to use implicit namespaces for python packages.

Example usage:
```
% python3 some/path/to/app/main.py
hello-bot
hola-bot
%
% cd some/path/to/app
% python3 main.py
hello-bot
hola-bot
%
% cd module1
% python3 ../main.py
hello-bot
hola-bot
```
