# Mad Men - Share your favorite Quote

Mad Men theme inspired coding project using plain html/css (although I love cats too!)

## Getting Started

Download the source code with the following code as outlined below.

### Downloading the Repo

In the command line, run the following command to clone the repo

```
$ git clone git://github.com/SpringSource/spring-data-graph-examples.git
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* Bootstrap 3.3.7
* Atom
* http://codepen.io/wenima/ for testing various things

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

## Author

* **Marc Kessler-Wenicker**

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT)

## Acknowledgments

* Thanks to [StackOverflow](www.stackoverflow.com) for finding the answer to some bootstrap related questions (although it sometimes sent me on a wild goose chase)
* [Codecademy](www.codecademy.com) for teaching the basics in HTML/CSS
* The awesome show MadMen by Matthew Weiner on AMC

## Wall of Shame

List of things I'm unhappy with in the project but did not have enough time/skill to fix/do right

* Not being able to get an individually compiled bootstrap with SASS going. The current css files pain me but setting up a best-practice SASS project (including automated compiles using gulp) turned out to be more time-consuming than expected.
* lots of use of fixed-heights or fixed-widths which breaks responsive design
* Screen Readers are not supported through ARIA roles etc
* using elements to be buttons which are [not buttons](http://www.karlgroves.com/2013/05/14/links-are-not-buttons-neither-are-divs-and-spans/)
* spent a lot of time trying to figure out the underling in the h2 headers when apparently a simple <hr> would have done the trick
* didn't finish the carousel/slider to make it work and be styled like the mockup
