# Test Prodigybuild

This repository contains the necessary source code and scripts to run a binary search algorithm implementation in C.

## Prerequisites

### **On MAC**

1. **Installation of GCC:**
   
Install Homebrew by launching Terminal and entering the following command:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

After Homebrew installation, install GCC with this command: 

```bash
brew install gcc
```

2. **Installing Make:**

Install Make with this command:

```bash
brew install make
```

### **On Windows**

1. **Installation of MinGW-w64:**

Go to MinGW-w64 [download page](https://mingw-w64.org/doku.php/download/mingw-builds) and get the latest version. Install it and add MinGW to the PATH:

```bash
setx path "%path%;C:\mingw-w64\x86_64-7.2.0-posix-seh-rt_v5-rev1\mingw64\bin"
```

## Setup

Clone the repository locally:

```bash
git clone <repository_url>
```

Navigate to the project directory:

```bash
cd <repository_name>
```

## Running Locally

To compile and run the program:

```bash
gcc -o binsearch Prodigy_build-testBranch/c/algorithms/binsearch.c
./binsearch
```

## Environment Setup

There's no special environment setup required for this project, as it's just running a C file that doesn't interact with any databases or require any specific environment variables.

## CI/CD

This repository currently does not involve any CI/CD setup.

Please refer to the appropriate CI/CD documentation for pipeline setup and deployment processes if it's necessary in the future.
