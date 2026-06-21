# JohnathanIrvin.com

This is the source code for my personal website, [JohnathanIrvin.com](https://johnathanirvin.com).

The website is a static site built using the [Hugo](https://gohugo.io/) static site generator and the [Hugo Coder](https://github.com/luizdepra/hugo-coder) theme.

## Local Development

If you have Hugo installed locally, you can start the development server to test changes:

```bash
hugo server -D --ignoreCache --minify
```

Then open `http://localhost:1313` in your browser.

## Docker

Build the site into a container image:

```bash
docker build -t johnathanirvin-site .
```

Run the built site locally on port 8080:

```bash
docker run --rm -p 8080:80 johnathanirvin-site
```

Then open `http://localhost:8080` to test the generated site.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Personally, I do not know what you would want to do with this code, but if you do, feel free to use it.

## Acknowledgments

* [Hugo](https://gohugo.io) for the blazing fast static site generator.
* [Hugo Coder Theme](https://github.com/luizdepra/hugo-coder) for the minimalist theme.
