# Custom error pages for Traefik

A bunch of custom error pages for Traefik built with [Jekyll](https://jekyllrb.com/).

This is a fork of [guillaumebriday's project](https://github.com/guillaumebriday/traefik-custom-error-pages) with my own template and backgrounds.

This also comes with a docker-compose file.

## Installation

```bash
$ bundle install
```

## Development

The current folder will be generated into ./_site :
```bash
$ jekyll build
```

Build the site on the preview server :
```bash
$ jekyll serve
$ open http://127.0.0.1:4000/
```

## How to use with Traefik and Docker

Labels are already defined in the image to work with Traefik.

To use it in production use the included compose file:

```bash
$ docker-compose up --build -d
```

## Credits

Credit to guillaumebriday for his [code](https://github.com/guillaumebriday/traefik-custom-error-pages).

## Contributing

Do not hesitate to contribute to the project by adapting or adding features ! Bug reports or pull requests are welcome.

## License

This project is released under the [MIT](http://opensource.org/licenses/MIT) license.
