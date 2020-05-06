# Ecommerce(Generics) Sapper App

## How to setup this project

Create a directory, for example `sapper-app`, and open this directory with VSCode

Clone this repo and and place under `sapper-app` directory

Change directory 
```
cd ecommerce-generics-sapper-app-master
```

Install all the dependencies
```
npm i
```

Start development
```
npm run dev
```

## Project Structure

src
- api ( backend services, not implemented yet )
- components
  - Nav.svelte
  - Footer.svelte
- routes
  - index.svelte ( home page )
  - store.svelte ( store page )
  - about.svelte ( about page )
- store
  - musicStore.js
  - tourStore.js

## Upload your sapper project to Github

Create a local git repo
```
git init
```

Add all files to local repo
```
git add .
```

Commit your local git repo
```
git commit -m "your-comment"
```

Create a new repo in your Gituhb account (`github.com`)

Click `new`

Enter your Repository name and click `Create repository`

Establish remote connection on the command line
```
git remote add origin https://github.com/[your-name]/[your-repo-name].git
```

Push your local repo to your Github account
```
git push origin master
```

## Deploy Sapper App to Netlify

Login your Netlify account

Go to `app.netlify.com/teams/[your-team]/sites` page

Click `New site from Git`

Select `GitHub`  under `Continuous Deployment`

Type your repo name in `Search repos` input box or simply click the item list

Enter `npm run export` in `Build command` input box

Enter `__sapper__/export` in `Publish directory` input box

Click `Deploy site`

## Recommend Learning resources

- Svelte Master
  - [Svelte tutorial](https://www.youtube.com/watch?v=cU8ZPBKaEwU&list=PLcjHRSem_cvP440pjw79kB85Z_7Nn8VqZ)
  - [Sapper tutorial](https://www.youtube.com/watch?v=kGfplN8HtlQ&list=PLcjHRSem_cvNDvCP3l6diqi7YBAsjfplL)
- The Net Ninja
  - [Svelte Tutorial for Beginners](https://www.youtube.com/watch?v=zojEMeQGGHs&list=PL4cUxeGkcC9hlbrVO_2QFVqVPhlZmz7tO)









