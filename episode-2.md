# Intro to web development (Episode 2)
[Register Here](https://us02web.zoom.us/meeting/register/tZ0kduurpzoqH9ONpGazYfru3DxT5U4m0syE)

### Overview
- Browsers
    - It's important to have a general understanding of how browsers work. This means knowing what happens in the time between the moment you enter a URL and a functional website being displayed on your screen.
        - [Webpage Rendering](http://frontendbabel.info/articles/webpage-rendering-101/)
        - [How Browsers Work](https://www.html5rocks.com/en/tutorials/internals/howbrowserswork/#The_browser_high_level_structure)

- Development Cycle
    - Every company operates differently, and there are a multitude of different tools for project management, testing, deployment and version control. [Agile](https://www.agilealliance.org/agile101/) methodology seems to be the industry-preferred management style at the moment.
    - Tools such as [Jira](https://www.atlassian.com/software/jira) allow project managers to easily assign features/bugfixes and other tasks to developers
    - The lifecycle of a new feature roughly goes through the following process:
        - Branch off the current development branch and start editting the source code.
        - Commit finished code as wellas any unit/e2e tests. Merge 
        - Push feature branch and createpull request.
        - Merge feature branch intodevelopment branch and deploy itto test environments. Thisusually involves running testslinters to ensure old featuresaren't broken by new changes.
        - Create `release/x.x.x` branchfrom development branch anddeploy to productionenvironments.
        - Rinse and repeat.
