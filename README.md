# Baking App (Sinatra)

This application is an introduction to a few of the core ideas involved in
building a web application.  Most importantly:

- [Routing][glossary-routing], i.e., the relationship between the URL you visit
  in your browser and the code your web application runs.
- [Query strings][glossary-query-string] as a way for the user to pass dynamic
  information from the browser to the web application.
- Dynamically generating HTML documents to send back to the browser

## Running The Baking App

### Install The Required Libraries

To install the libraries required for this application, first run the following
command:

```shell-session
$ bundle install
```

### Run The Baking App

Once you've installed the required libraries, run the following command:

```shell-session
$ ruby bake_app.rb
```

To stop your application, press `Ctrl+c`.  That means press the "Control" key
and the "c" key at the same time.

[glossary-routing]: https://glossary.codeunion.io/routing/
[glossary-query-string]: https://glossary.codeunion.io/query-string/
