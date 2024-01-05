This project contains two categories of files:

1. Generic extendable examples of using GitLab CI/CD for various functions of testing, building, and deploying. These are found in the respective .yml files and define the main functionality of the different jobs, including accepting variables. Comments are included for further explanation on each job definition.
1. An example of a project CI file that would implement those functions.

This could be collapsed into one .gitlab-ci.yml file, particularly if you are only working on one project that would make use of them. They are divided here to demonstrate [the use of extending job definitions](https://docs.gitlab.com/ee/ci/yaml/#extends), which is a powerful way to centrally define reusable job templates referenced by multiple other projects.