# Developer Portfolio 


## Table of Contents :scroll:
- [Sections](#sections-bookmark)
- [Installation](#installation-arrow_down)
- [Hosting](#hosting-globe_with_meridians)




# Sections :bookmark:
- HOME
- ABOUT
- RESUME
    - EDUCATION
    - SKILLS
    - EXPERIENCE
    - PROJECTS 
    - Achievements 
- BLOG
- CONTACTS 



# Installation :arrow_down:
### You will need to download Git and Node to run this project

- [Git](https://git-scm.com/downloads)
- [Node](https://nodejs.org/en/download/)

## Also check [this](https://reactjs.org/docs/create-a-new-react-app.html) out if you are new to react.

#### Make sure you have the latest version of both Git and Node on your computer.

```
node --version
git --version
```

<br />


### Install packages from the root directory
```
npm install
```
#### or
```
yarn install
```
### Start the development server
```
npm start
```
#### or
```
yarn start
```



Eg:
```javascript
export const headerData = {
    name: '-- YOUR NAME --',
    title: '-- YOUR TITLE --',
    desciption:'-- DESCRIPTION --',
    image: '-- IMAGE --',
    resumePdf: ''
}

// You can also import image and PDF from assets as shown below

import resume from '../assets/pdf/resume.pdf'
import profileImg from '../assets/png/profileImg'

export const headerData = {
    name: '-- YOUR NAME --',
    title: '-- YOUR TITLE --',
    desciption:'-- DESCRIPTION --',
    image: profileImg,
    resumePdf: resume
}
```

#### Data for each component is divided into respective files.
>#### Set website theme in [`src/data/themeData.js`](https://github.com/suryansaravanan/portfolio/blob/master/src/data/themeData.js) and choose your favourite font from [`src/App.css`](https://github.com/suryansaravanan/portfolio/blob/master/src/App.css)

> #### About You - [`src/data/aboutData.js`](https://github.com/suryansaravanan/portfolio/blob/master/src/data/aboutData.js)

> #### Education details - [`src/data/educationData.js`](https://github.com/suryansaravanan/portfolio/blob/master/src/data/educationData.js) 

> #### Enter your Projects - [`src/data/projectsData.js`](https://github.com/suryansaravanan/portfolio/blob/master/src/data/projectsData.js)

> #### Add your Skills - [`src/data/skillsData.js`](https://github.com/suryansaravanan/portfolio/blob/master/src/data/skillsData.js)

> #### Experience - [`src/data/experienceData.js`](https://github.com/suryansaravanan/portfolio/blob/master/src/data/experienceData.js)

> #### Achievements - [`src/data/achievementData.js`](https://github.com/suryansaravanan/portfolio/blob/master/src/data/achievementData.js)

> #### Your Blogs and Articles - [`src/data/blogData.js`](https://github.com/suryansaravanan/portfolio/blob/master/src/data/blogData.js)

> #### Contact Details - [`src/data/contactsData.js`](https://github.com/suryansaravanan/portfolio/blob/master/src/data/contactsData.js)

> #### Social Media Profiles - [`src/data/contactsData.js`](https://github.com/suryansaravanan/portfolio/blob/master/src/data/socialsData.js)


# Hosting :globe_with_meridians:
## Netlify
| Site   | Docs  | Demo  |
| :-------------: |:-------------: |:-------------: |
| [Netlify](https://www.netlify.com/) | [3 ways to deploy React apps to Netlify](https://blog.logrocket.com/3-ways-to-deploy-react-apps-to-netlify/) | [Youtube](https://www.youtube.com/watch?v=sGBdp9r2GSg) |

## Firebase
| Site   | Docs  | Demo  |
| :-------------: |:-------------: |:-------------: |
| [Firebase](https://firebase.google.com/docs/hosting) | [Deploy a React App with Firebase](https://medium.com/swlh/how-to-deploy-a-react-app-with-firebase-hosting-98063c5bf425) | [Youtube](https://www.youtube.com/watch?v=1wZw7RvXPRU) |


## Heroku
| Site   | Docs  | Demo  |
| :-------------: |:-------------: |:-------------: |
| [Heroku](https://www.heroku.com/) | [Deploying React App on Heroku from GitHub](https://medium.com/make-it-heady/deploying-create-react-app-on-heroku-from-github-49447561f670) | [Youtube](https://www.youtube.com/watch?v=dn4mmfbletg) |

## Github Pages
| Site   | Docs  | Demo  |
| :-------------: |:-------------: |:-------------: |
| [GitHub Pages](https://pages.github.com/) | [Deploying React App on GitHub Pages from GitHub](https://create-react-app.dev/docs/deployment/#github-pages) | [Youtube](https://youtu.be/F8s4Ng-re0E) |



