**Welcome to UK Delivers.**

UK Delivers is a simple directory of independent businesses offering local delivery. Enabling people to stay at home and save lives, while keeping our high streets alive.

This project was originally bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

_Credit Rob Hough._

For reference, there are currently three versions available on GitHub:

* Deal Delivers: [https://github.com/heymynameisrob/deal-delivers-app](https://github.com/heymynameisrob/deal-delivers-app)
* Dulwich Delivers: [https://github.com/tomszekeres/dulwich-delivers-app](https://github.com/tomszekeres/dulwich-delivers-app)
* Reigate Delivers: [https://github.com/robin174/reigate-delivers-app](https://github.com/robin174/reigate-delivers-app)

# Accounts required

There are four accounts required to get a UK Delivers app online.

* [Airtable](https://airtable.com) - For your database and listing form
* [Netlify](https://www.netlify.com) - For deployment
* [MailChimp](https://mailchimp.com) - For email sign-ups
* [Cloudinary](https://cloudinary.com) - For hosting images on a Content Delivery Network (CDN)

A domain is also required. We recommend a '.com' URL for this.

# Brand

The design of each individual site is up to the owner and you will need to pick two hexadecimal values for your site; one for the large triangle and one for the smller triangle. The base background blue is #0B132B.

_For reference, Reigate Delivers: Pink #E20C5E, Yellow #FFB600._

### Artwork generation

For help with generating the necessary artwork files - please email [robin@reigatedelivers.com](mailto:robin@reigatedelivers.com).

___

# Stage 01 - Local

**To start, let's get a base version of the site live locally.**

### GitHub
Download or clone the repository. 

To get started you will need [Node.js](https://nodejs.org) installed on your computer. You have a choice of [Node package manager (npm)](https://nodejs.org) or [Yarn](https://yarnpkg.com) as your package manager.

Using the terminal, navigate to your app folder.

#### Via npm
`npm install` to install the necessary Node modules. 

`npm start` to start the server, available at `http://localhost:3000/`.

#### Via Yarn
`yarn install` to install the necessary Node modules

`yarn start` to start the server, available at `http://localhost:3000/`.

***NB. I had to update my version of Node. To update Node on Mac/Catalina:***

`nvm install node`

___

# Stage 02 - Online

**Once the app is available locally, let's get it online.**

### Upload to GitHub

### Connect to Netlify

### Connect Cloudinary

Update Cloudinary credentials in `public` - `admin` - `config.yml`

### Connect MailChimp

Update link to MailChimp list in `src` - `App.js`













