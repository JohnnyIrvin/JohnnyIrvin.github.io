# JohnathanIrvin.com

This is the source code for my personal website, [JohnathanIrvin.com](https://johnathanirvin.com).

The website is a static site using [Picocss](https://picocss.com) and good old HTML.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Personlly, I do not know what you would want to do with this code, but if you do, feel free to use it.

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

## Acknowledgments

* [Picocss](https://picocss.com) for the CSS framework
* [Randall Williams](https://www.linkedin.com/in/randallwilliamsdeveloper/) for his proofreading and suggestions.
