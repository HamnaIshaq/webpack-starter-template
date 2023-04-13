# webpack starter template

This is a simple webpack template to quick start your projects without the hassle of manually setting up webpack each time you start a new project.

# Get started

To get your own copy of this template, follow the steps below

1. Fork this repo

<img src="./extra-assets/fork.JPG" alt="Fork repo by clicking on the fork button" title="Fork repo">

2. Make a new repository from this forked template

<img src="./extra-assets/create-new-repo.JPG" alt="Create a new repository by clicking on the 'use this template' button and selecting 'create a new repository' " title="Create a new repository">

3. Clone this repository to your local environment

<img src="./extra-assets/clone-repo.JPG" alt="Clone the repository by clicking on the 'clone' button and copying the URL from HTTPS" title="Clone repository">

```sh
  git clone https://github.com/YOUR_GITHUB_NAME/webpack-starter-template.git
```

4. Install all node packages needed

```sh
  npm install
```

5. To set up a local dev server, use the command

```sh
  npm start
```

6. To bundle your js files, use the command

```sh
  npm run build
```

# Folder Structure

```sh
project
|- package.json
|- package-lock.json
|- /dist
  |- index.html
  |- bundle.js
|- /src
  |- index.js
```

Add your files in the source folder and import them in the index.js file as this is the entry point from where webpack starts its bundling process.
