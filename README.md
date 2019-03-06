# README

This sample project reproduces issue
https://github.com/rails/rails/issues/35500.

Perform a `bundle install` and then run the following command. It results in an
error and should not:

```
bin/rails runner 'Foo::Bar'
```
