# Simplefolio ⚡️ [![GitHub](https://img.shields.io/github/license/SheLearningCode/simplefolio?color=blue)](https://github.com/SheLearningCode/simplefolio/blob/master/LICENSE.md) ![GitHub stars](https://img.shields.io/github/stars/SheLearningCode/simplefolio) ![GitHub forks](https://img.shields.io/github/forks/SheLearningCode/simplefolio)

## A minimal portfolio template for Developers!

<h2 align="center">
  <img src="https://github.com/SheLearningCode/gatsby-simplefolio/blob/master/examples/example.gif" alt="Simplefolio" width="600px" />
  <br>
</h2>

## Features

⚡️ Modern UI Design + Reveal Animations\
⚡️ One Page Layout\
⚡️ Styled with Bootstrap v4.3 + Custom SCSS\
⚡️ Fully Responsive\
⚡️ Valid HTML5 & CSS3\
⚡️ Optimized with Parcel\
⚡️ Well organized documentation



---

## Why do you need a portfolio? ☝️

- Professional way to showcase your work
- Increases your visibility and online presence
- Shows you’re more than just a resume

## Getting Started 🚀

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites 📋

You'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [NPM](http://npmjs.com)) installed on your computer.

```
node@v16.4.2 or higher
npm@7.18.1 or higher
git@2.30.1 or higher
```

Also, you can use [Yarn](https://yarnpkg.com/) instead of NPM ☝️

```
yarn@v1.22.10 or higher
```

---

## How To Use 🔧

From your command line, first clone Simplefolio:

```bash
# Clone the repository
$ git clone https://github.com/cobiwave/simplefolio

# Move into the repository
$ cd simplefolio

# Remove the current origin repository
$ git remote remove origin
```

After that, you can install the dependencies either using NPM or Yarn.

Using NPM: Simply run the below commands.

```bash
# 2022 Update - Fix Dependencies
$ npm audit fix
$ npm i @parcel/transformer-sass

# Install dependencies
$ npm install

# Start the development server
$ npm start
```

Using Yarn: Be aware of that you'll need to delete the `package-lock.json` file before executing the below commands.

```bash
# Install dependencies
$ yarn

# Start the development server
$ yarn start
```

**NOTE**:
If your run into issues installing the dependencies with NPM, use this below command:

```bash
# Install dependencies with all permissions
$ sudo npm install --unsafe-perm=true --allow-root
```

Once your server has started, go to this url `http://localhost:1234/` to see the portfolio locally. It should look like the below screenshot.


### Step 2 - STYLES

Change the color theme of the website - (choose 2 colors to create a gradient)

Go to `/src/sass/abstracts/_variables.scss` and only change the values for this variables `$main-color` and `$secondary-color` with your prefered HEX color.
If you want to get some gradients inspiration I highly recommend you to check this website [UI Gradient](https://uigradients.com/#BrightVault)

```scss
// Default values
$main-color: #02aab0;
$secondary-color: #00cdac;
```

---

## Deployment 📦

Once you finish your setup. You need to put your website online!


## Technologies used 🛠️

- [Parcel](https://parceljs.org/) - Bundler
- [Bootstrap 4](https://getbootstrap.com/docs/4.3/getting-started/introduction/) - Frontend component library
- [Sass](https://sass-lang.com/documentation) - CSS extension language
- [ScrollReveal.js](https://scrollrevealjs.org/) - JavaScript library
- [Tilt.js](https://gijsroge.github.io/tilt.js/) - JavaScript tiny parallax library

## License 📄

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details