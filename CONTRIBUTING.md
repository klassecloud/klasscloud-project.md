# Contributing
First off, thank you for considering contributing to klasse.cloud. It's people like you that make this project possible.
Following these guidelines helps to communicate that you respect the time of the developers managing and developing this open source project. In return, they should reciprocate that respect in addressing your issue, assessing changes, and helping you finalize your pull requests.

We are an open source project and we love to receive contributions from our community — you! There are many ways to contribute, from writing tutorials or blog posts, improving the documentation, submitting bug reports and feature requests or writing code which can be incorporated into the project itself.


## Open Development
Most work on klasse.cloud happens directly here on GitHub. Both core team members and external contributors send pull requests which go through the same review process.

## Branch Organization
We will do our best to keep the master branch in good shape, with tests passing at all times. But in order to move fast, we will make changes that your custom changes might not be compatible with. We recommend that you use the latest stable version of this project. Please use feature branches when working on more complex changes, so others can follow and contribute, too.

If you send a pull request, please do it against the master branch.

## How to suggest a feature or enhancement
This project just started! Please wait for the first few versions to be released, before requesting exciting new stuff!

## Responsibilities

- Ensure cross-platform compatibility for every change that's accepted.
- Ensure that code that goes into master branch meets all requirements from the requirements list below
- Create issues for any major changes and enhancements that you wish to make. Discuss things transparently and get community feedback. (exception: use slack or similar at Hackathons)
- Don't add any classes to the codebase unless needed.
- Be welcoming to newcomers and encourage diverse new contributors from all backgrounds. See the [Contributor Covenant](https://www.contributor-covenant.org/) Community Code of Conduct.
- Take the time to get things right. Pull Requests (PR) almost always require additional improvements to meet the bar for quality. Be very strict about quality. This usually takes several commits on top of the original PR.
- Update documentation where necessary, write documentation when required. Use the klassecloud.github.io repository when targeting users of this project. Write green code or text files when targeting other developers.

## Requirements for code contributions to master branch
- Try to only contribute working code, no dead code, no "soon to be used" code and no "will fix it soon" code
- No huge methods, try to reduce complexity, write readable code -> see [Clean Code Cheat Sheet](https://www.bbv.ch/images/bbv/pdf/downloads/V2_Clean_Code_V3.pdf)
- When copying others peoples/projects code, check licenses. Make sure to not add dependencies which restrict future licensing of this project's code.

## Code Style 
This project sticks to code style suggestions according to https://google.github.io/styleguide/

```
// TODO add sample code here
```

## Project Structure

| What | Where |
|---|---|
| Landingpage (static content) | https://github.com/klassecloud/landingpage |
| Ionic based Frontend | https://github.com/klassecloud/frontendIonic |
| Frontend code for teacher, student and administration | https://github.com/klassecloud/frontend |
| Backend services code | https://github.com/klassecloud/backend |
| Teacher application server code | https://github.com/klassecloud/backendTeacher |
| project website and user targeting documentation | https://github.com/klassecloud/klassecloud.github.io |
| old frontend - dead | https://github.com/klassecloud/frontend |
| old stuff | https://github.com/klassecloud/digitales-klassenzimmer-backend-appsync |

## Project Insights
Any changes to the master branch of a code repository starts an automatic build test and deploy pipeline. Pull requests targeting master branch are only built and tested, but never get deployed.

### Used tools
- Visual Paradigm Community Edition: Entity Relationship modelling
- IntelliJ / Eclipse: Java integrated 
- Adobe XD: frontend clickdummy design 

### Tests
Backend Java code can be tested using JUnit 5 tests.
