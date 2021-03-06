# TechPass User Doc Repository
This is a documentation repository for TechPass.

> The repository is currently in active development and  contents will change rapidly.

## Contributing
Please create a new branch or fork the repository, make your changes and submit a PR.

For instructions on how to use docsify, please consult [docsify documentation](https://docsify.js.org/#/?id=docsify).

## File Structure
All markdown files should live within the **/docs** folder. Each main section should be a separate markdown file by itself. If you have added a new main section, you should also update [_sidebar.md](docs/_sidebar.md) so that it will show up when the webpage is rendered.

If you are unclear whether to start a new section, it ok. Just put the content down somewhere and someone will housekeep them eventually. The most important thing is to churn out the content.

All non-markdown files (i.e. images and sample code files) should live within the assets subfolder.

## Running Locally
### Setting Up
- Install docsify cli `npm -g install docsify-cli`
- Git pull this repository
- Run `docsify serve .`

### Customised Styling
By default, docsify renders the markdown using pre-defined docsify themes. If you want to customise the themes, [docsify-themeable](https://jhildenbiddle.github.io/docsify-themeable/#/customization) provides a comprehensive list of CSS properties that you can overwrite.

### Syntax Highlighting
By default, docsify renders CSS, Javascript and HTML. If you require syntax highlighting for other languages, please refer to this [section](https://docsify.js.org/#/language-highlight).

## Web Hosting
The documentation will be hosted on https://dev.docs.developer.gov.sg.