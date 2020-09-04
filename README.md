# popdog-card-clone

Files associated with my YT video series where I try to create a clone of the Top Games card on [popdog.com](https://popdog.com).

## Videos
1) [Building out the structure and animations](https://youtu.be/YmyqlM13JUU)
2) [Adding the icons with Font Awesome and pseudo-elements](https://youtu.be/lMBa7gLWyO4)
3) [Creating the pulsing animation](https://youtu.be/PMGCOVfK-8s)
4) [Animated SVG wave clip-path](#) - coming soon

## Building and Running

There are many ways to build and run this project. 1 suggestion is to use both the sass and http-server NPM commands.

### To install

```
npm -g sass
npm -g http-server
```

### Building

In 2 terminal windows:

```
# Terminal Window 1
sass --watch scss/main.scss:css/main.css

# Terminal Window 2
http-server .
```

### Running

When both commands are running, open `http://localhost:8080` in your web browser.