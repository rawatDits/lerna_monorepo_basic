# Basic Monorepo Demo Using Lerna

This repository demonstrates a basic monorepo setup using Lerna, where packages can be utilized by other packages (components) within a single repo.

## Getting Started

### Prerequisites

Make sure you have Node.js and npm installed on your machine. You can download them from [Node.js official website](https://nodejs.org/).

### Installing Lerna

To manage this monorepo, you need to install Lerna globally. Run the following command:

```sh
npm install -g lerna

```



### Initializing the Monorepo

After installing Lerna, initialize your monorepo by running:
```sh
lerna init

```


### Installing Dependencies
```sh
npm install

```

### Building the Packages
To build all packages within the monorepo, use the following command:
```sh
lerna run build

```



