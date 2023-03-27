Let's assume that the application is written in Python. In the Python ecosystem, there are several popular tools for handling the common steps in a CI setup.

For linting, Flake8 is a widely used tool that checks for code style issues and potential bugs. It combines several other tools like PEP8, PyFlakes, and McCabe into one tool.

For testing, pytest is a popular testing framework that provides a lot of features, such as fixtures, parameterization, and plugins, to make testing easier and more efficient.

For building, setuptools is the most common tool for building Python packages. It can create source distributions, binary distributions, and wheels, which are the preferred format for distributing packages.

Besides Jenkins and GitHub Actions, there are several other alternatives to set up CI. For example, GitLab CI/CD, Travis CI, and CircleCI are widely used cloud-based CI tools that can be integrated with GitHub, GitLab, or Bitbucket. Additionally, self-hosted CI tools like Buildbot and Drone can provide more customization and control over the CI environment.

The decision between a self-hosted or cloud-based environment for the CI setup depends on various factors. Cloud-based CI tools offer a simple and easy-to-use interface, automatic scaling, and integration with other cloud services. However, self-hosted CI tools can provide more control, customization, and security. To make a decision, we need to consider the team's size, expertise, budget, and requirements for customization and control over the CI environment. Additionally, we need to evaluate the cost-benefit of managing the CI infrastructure ourselves versus using a cloud-based service.