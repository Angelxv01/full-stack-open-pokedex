# exercise1

### Some common steps in a CI setup include linting, testing, and building. What are the specific tools for taking care of these steps in the ecosystem of the language you picked?

Language chosen: **Python**

**Linting**

Generally speaking for Python there's `PEP8` which is a style guide that highlights the issues in the code. In addition to that, there are some external dependencies like `flake8` which checks whether the code follows the standard style guide and if it is readable by other developers.

**Testing**

In Python there are several way to test the program, I can unit test a program by creating a file which use `assert` to check the correctness of the code. I can also create a test suite using `pytest` which include a testing system using classes where I can test my program in a systematic way.

`pytest-cov` gives a good overview about **test coverage** which it's important when we try to find bugs in our program and be sure if the code is tested enough.

**Build**

As I learned in the material, there's no need for interpreted languages like Python to build.

### What alternatives are there to set up the CI besides Jenkins and GitHub Actions?

There are some CI/CD platforms like Harness or Azure DevOps.

### Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?

The choice of using self-hosted or cloud-based is based on the need of the developers. In this situation it could be reasonable to use cloud-based environment because it's one team and they may not need to having custom settings on the code base.