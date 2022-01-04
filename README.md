# Pong-JS


# Running http.server

Your job is to get terminal to point to the directory on your computer where you are storing your p5.js work. For example:

```
cd /Users/Downloads/Pong-JS
```

(You don't need to type the '$' I'm just using it to represent a prompt.)

Once I'm there, I can start up a web server with the following command.

```
python -m http.server
```

I should then see:

```
Serving HTTP on 0.0.0.0 port 8000 ...
```

This means the server is up and running at [localhost](http://en.wikipedia.org/wiki/Localhost) on port 8000.  And this means I can type `http://localhost:8000/` into the address of a web browser and I'll see the game.
