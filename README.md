# Dancer2 sample app

This is a fairly trivial demonstration of using Dancer 2 to serve
GraphQL. To use:

```
cpanm GraphQL
plackup bin/app.psgi
```

It has a tiny, "Hello world" schema. If you view your localhost on port
5000, you will see the "GraphiQL" link. Follow it and you will be in the
"GraphiQL" environment. Try typing this query at the bottom of the left frame:

```
{ helloWorld }
```
