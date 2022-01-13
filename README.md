# Regexper

Code for the [Regular Expression Visualization Site](https://kellnerd.github.io/regexper/) with support for additional regex features (see the [changelog](https://kellnerd.github.io/regexper/changelog.html) since 2022).
Based on the latest version of the original site https://regexper.com/ from [GitLab](https://gitlab.com/javallone/regexper-static).

## Contributing

I greatly appreciate any contributions that you may have for the site. Feel free to fork the project and work on any of the reported issues, or let me know about any improvements you think would be beneficial.

When sending pull requests, please keep them focused on a single issue. I would rather deal with a dozen pull requests for a dozen issues with one change each over one pull request fixing a dozen issues. Also, I appreciate tests to be included with feature development, but for minor changes I will probably not put up much of a fuss if they're missing.

### Working with the code

Node is required for working with this site.

To start with, install the necessary dependencies:

    $ yarn install

To start a development server, run:

    $ yarn start

This will build the site into the ./build directory, start a local start on port 8080, and begin watching the source files for modifications. The site will automatically be rebuilt when files are changed. Also, if you browser has the LiveReload extension, then the page will be reloaded.

These other gulp tasks are available:

    $ yarn docs # Build documentation into the ./docs directory
    $ yarn build # Build the site into the ./build directory
    $ yarn test # Run JSCS lint and Karma tests

## License

See [LICENSE.txt](/LICENSE.txt) file for licensing details.
