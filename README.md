# Installation Guide for KGPverse

This is a comphrehesive guide on installing and running frontend and backend of the website on your machine. It is majorly written in [Javascript](https://www.javascript.com/), Shell, [Node 14.18.0](https://nodejs.org/ca/blog/release/v14.18.0/)

**Dependencies**
The project uses the following packages or Platforms that may have been used to serve the data.

- Yarn
- Node js
- prettier using husk
- React
- One Signal
- PM2 as daemon process manager
- Nginx
- AWS EC2  Instance for backend deployment
- Netlify for frontend deployment
- Different Dev  and Production for better management
- Cloudflare as DNS
- DNS Caching through Cloufflare
- Postgres Database from free SUPABASE instance
- Google sheets for easy data control for non techincal people 

**Basic Setup**
Clone the respective repositories from the following links:
[Front End](https://github.com/Hack-TeeEssGee/frontend)
[Back End](https://github.com/Hack-TeeEssGee/backend-node)

**Front End**
It's written mainly in React which uses React

1. Run backend with localhost .env
2. Clone project. inside project root directory, run the command ```yarn```
3. after installation of the packages is over, run the command ```yarn start``` to start the development server in port 3000.

**Back End**
It's mainly written in Yarn , Node 14.18.0

- Add env to root of folder
- Add gsheets.json to root of folder

> we are using Yarn as a package manager

- run Yarn to install all node modules
- Run ```yarn start```  to start the backend server of local machine
- For dev, server replace BACKEND_URL with http://localhost:8000
- and Frontend_URL to http://localhost:3000

> You can visit the respective READMEs for [Front End](https://github.com/Hack-TeeEssGee/frontend/blob/master/README.md), [Back End](https://github.com/Hack-TeeEssGee/backend/blob/master/README.md) and [Back End Node](https://github.com/Hack-TeeEssGee/backend-node/blob/master/README.md).
