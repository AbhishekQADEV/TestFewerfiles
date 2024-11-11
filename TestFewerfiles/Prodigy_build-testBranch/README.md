# Test Prodigybuild

This is the repository for Test Prodigybuild, an innovative project showcasing binary search algorithm implementation in C.

## Prerequisites

Ensure the following dependencies are installed on your machine:

- GCC (GNU Compiler Collection) for compiling the C program. For MAC, you should use `brew install gcc`. For Windows, download it from the [official GNU website](http://www.mingw.org/).
- Git for version control.

## Setup Steps

1. Clone the repository to your local environment:

```shell
git clone https://github.com/[username]/test_prodigybuild.git
```

2. Navigate to the Test Prodigybuild folder:

```shell
cd test_prodigybuild
```

## Running all Tests

Compile and run the main file:

```shell
gcc -o binsearch TestFewerfiles/Prodigy_build-testBranch/c/algorithms/binsearch.c
./binsearch
```

## Environment Setup

This project does not require any specific environment setup as it utilizes basic C programming and GCC for compiling the program.

For CI/CD, you would need to set that up based on the pipeline you use, such as Jenkins, Travis CI, etc.

## Deployment

The deployment process would involve setting up a CI/CD pipeline to build and test your code whenever changes are pushed to the main branch.

1. Set up your CI/CD pipeline tool.
2. Configure the pipeline to track your repo and the main branch.
3. Configure the pipeline to compile and run tests (gcc and ./binsearch).

Note: all commands provided in this document are to be run in a Terminal window (MAC) or Command Prompt (Windows).
