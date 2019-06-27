# #100DaysOfCode Log - Round 1

The log of my #100DaysOfCode challenge. Started on [March 31, Sunday, 2019].

## Log

#girlswhocode #girlsintech #codergirl #peoplewhocode #codeforlife #codinglife #codingforweb

### R1D1

- set up github (https://github.com/gitfrosh/100-days-of-code-projects) & logbook & twitter ✔
- mini-code "when does the challenge finish?" (https://github.com/gitfrosh/100-days-of-code-projects/tree/master/timer) ✔
- check out https://github.com/florinpop17/app-ideas ✔
- collect projects:
  - dig into Javascript Grammar book
  - Vue.js introductory course
  - DevOps course ✔
  - finish Smart Home tutorial
  - search an Open Source project and contribute
  - revamp ueberdiespree.de ✔
  - https://www.frontendmentor.io/ ✔
  - build a Go Backend ✔
  - build an Electron App ✔
  - dig into typescript ✔
  - Junior to Senior Udemy Course https://www.udemy.com/the-complete-junior-to-senior-web-developer-roadmap/ ✔
  - what to do with Firebase? ✔
  - finish IF course
  - Web Components?!
  - Twitter Bot https://www.codewall.co.uk/twitter-bot-tutorial-retweet-nodejs/?utm_source=CWTwitter&utm_medium=social
  - SSR: blog post comparing Gatsby.js, Next.js, Nest Framework, ReactStatic.js
  - React CSS Styling: blog post comparing "normal" CSS style sheets, inline CSS styling, CSS in JS styling (glamorous, styled components,emotion,..) css modules
  - Svelte.js / Sapper ✔
  - build a LOTR api with Kaggle data on ~~Flask & Vue.js~~ Node.js & SSR React ✔
  - React Hooks
  - serverless apps
  - AWS Lambda (https://www.youtube.com/watch?v=3CFN9bSVfqc#action=share) ✔
  - create an npm package

### R1D2

Reworked my #nodejs mini server app to a #go #golang powered app and realised how much I got used to javascript's lack of typesafety. Took me some time! (Never worked with Go before)

- go run start.go

### R1D3

My #go #golang backend is now able to serve html and css files. Decided to quit working on the app for now, started an advanced #webdev tutorial by @AndreiNeagoie and already had some eureka moments regarding #ssh and #rsa. https://www.udemy.com/share/1009OgAEcccV9TR3g=/

### R1D4

No coding today but completed the 1st performance optimization part of the advanced #webdev course I started yesterday. Tomorrow I will dive into #React again after a few months of abstinence.

### R1D5

Got into #redux today and learned that it is based on #flux pattern and can be used in other UI layers such as #vuejs! (I like #MobX simplicity though 😇) Will have a look into Context API & Hooks based on
@dceddia articles tomorrow. https://daveceddia.com/archives/

### R1D6

Rewrote my app again and substituted #redux with state management based on React's context API and Hooks. Works like charm following this tutorial by @develop_simply https://link.medium.com/aLzWYbn2qV

I now have the same mini app running on MobX, Redux and Context API for comparison. Might add a new Github repository tomorrow. :)

### R1D7

Took a small (but highly overdue) journey into #javascript bundlers like #webpack and set up an example mini app. Realised that it is never good to just use things without at least understanding them in a basic way. Will have a look into #parcel and #rollup later.

### R1D8

Working on the advanced #webdev course frontend performance optimization chapter.

Resources:
webpagetest.org

React CSS Styling:

- tailwind?
- glamorous
- styled components
- css modules

### R1D9

Working further on the advanced #webdev course frontend performance optimization chapter.

- Code splitting with asnyc components
  React components rerender when their parents update (but this is not always necessary and a performance decreaser)
- PureComponent: only updates when received props change (but warning: it's not a deep comparison and will not properly work with complicated data props)
- shouldComponentUpdate: can be used alternatively, but is a more safe way
- why-did-you-update library!
- check React app performance: http://localhost:3000/?react_perf

### R1D10

Covered an important topic today: Progressive Web Apps and their pros and cons. Also I started working on a relaunch of my website and blog, including a move to @digitalocean!
Resources:
https://whatwebcando.today/
Lighthouse Plugin
https://www.pwabuilder.com/
cloudflare hoster
https://realfavicongenerator.net/

### R1D11

I tortured myself with webserver (#apache) configuration today, while moving domains and webspaces around providers and still not everything works properly. I'm now following an old programmer's rule: Stop when stuck and continue later (in my case tomorrow morning) with a fresh mind.

### R1D12

Finalized move of my website and blog to digitalocean.com!

### R1D13

Set up Let's Encrypt SSL Certificate, PWA installation for blog and website; digged into Testing and Behaviour Driven Development

Resources:

- Jasmine
- Jest (must popular!)
- Mocha
- Chai (language chains)
- Karma.js (only test runner)
- Sinon.js (mock, spies and stubs (e.g. make fake server))
- Istanbul (test coverage and where missing tests are)
- Tape, Ava
- Enzyme (esp. for React)

### R1D14

R1D014 #100DaysOfCode: Today I started working on a topic I've been neglecting for a long time: Testing in (#frontend) web development. 🙄 I started with some insights in #jest. Hope to find out more about the "when, what and whys" instead of the "how" to test!

- React components are pure functions and are easily tested with unit tests
- integration tests test connections between components (e.g. API calls)
- automation tests (= end-to-end-tests) are UI user tests (Nighwatch, WebDriverIO, TestCafe, CyPress) --> very expensive to implement

### R1D15

R1D15 #100DaysOfCode: More #jest #javascript testing today including async tests, assertions and mockups. Tomorrow will be about testing #react with #enzyme.
Resources:
https://github.com/sapegin/jest-cheat-sheet

### R1D16

R1D16 #100DaysOfCode: Didn't have too much fun with more testing on #react today so I will move on and start with learning #typescript from tomorrow.

Enzyme:

- shallow: renders the component without child components
- mount: full DOM rendering
- render: renders to static HTML (cheerio lib)
  yarn test -- --coverage

### R1D17

- dynamic (Python, Ruby, JS, PHP, ..)/static (C, C#, Java, Scala) programming languages
- static types must be declared!
  var a = 100; vs. int a;

- strong/weak programming languages (type coercion is the process of converting value from one type to another -> strong langs don't do that )

- Flow is compiled to JS with Babel, which compiles to ES5; ReasonML, Elm, Typescript have their own compiler

### R1D18

My baby girl took much of my attention the last two days, so progress on working on #typescript was slow but still steady. #100DaysOfCode 💪

init TypeScript project: tsc --init
compile .ts file to .js: tsc app.ts (--watch)

### R1D19

R1D19 #100DaysOfCode: Started working on #typescript in #react and did not feel very comfortable with it. I should probably keep on learning tomorrow.

Resources:

- definitelytyped.org (add ts to js-based 3rd party libraries like react)
- https://facebook.github.io/create-react-app/docs/adding-typescript
- npx create-react-app my-app --typescript

### R1D20

No coding today.

### R1D21

R1D21 #100DaysOfCode: No "real" coding today but reading some #webdev newsletters and writing which resulted in two new short tutorials about #nodejs & #expressjs APIs for #postgresql on my weblog.
Resources

- https://frontendmasters.com/books/front-end-handbook/2019/

### R1D22

R1D22 #100DaysOfCode: Started working on server-side rendered web apps, which has been on my bucket list for months! Started my first Next.js project stumbled open @ReactStaticJS and @nestframework.. much to learn apparently!

Libraries like react-snapshot can be added to your project, used to generate HTML copies of your application pages and save them to a specified folder. You can then deploy this folder alongside your JS bundle. This way, the HTML will be served along with the response allowing your site to be accessible by users with JavaScript disabled, search engines etc.

Resources

- Gatsby.js
- Next.js
- ReactStaticJs
- Nest.js

### R1D23

R1D23 #100DaysOfCode: More coding on server-side rendered apps today! Read about #CRA vs. #Nextjs vs. #Gatsbyjs and still need to figure out which framework is great for specific use-cases.

https://coffeencoding.com/cra-vs-next-js-vs-gatsby/

### R1D24

R1D24 #100DaysOfCode: So I'm starting to convert my vanilla #HTML #CSS #JavaScript portfolio to a #Gatsbyjs powered #SSR website and I'm not yet sure if it is worth the massive boilerplate code that is added. Like the overall configuration experience though!

#webdev #frontend #reactjs #coding #programming #womenwhocode

### R1D25

R1D25 #100DaysOfCode: WIP with Gatsby.js.

### R1D26

R1D26 #100DaysOfCode: Almost done with the mini relaunch of my website with Gatsby.js. 🧐 There are still some responsiveness issues to solve and I should have a check with @\_\_\_\_lighthouse. First thing tomorrow morning!

### R1D27

R1D27 #100DaysOfCode: I'm done rebuilding my website with @gatsbyjs and now it's time for some ice-cream. 🙂

### R1D28

R1D28 #100DaysOfCode: Super excited to start a whole new chapter today: Writing an app with @electronjs and starting with the #react boilerplate. Maybe I test out the @hapijs framework as a backend service right away.
"Track your mood!"

### R1D29

R1D29 #100DaysOfCode: I don't like it when the setup of my tech stack lasts so long I almost lose interest in actual coding 😬 well, at least I'm done now starting my @electronjs project with Next.js, styled-components and UI library.

### R1D30

R1D30 #100DaysOfCode: Anyone feeling nostalgic tonight? 💙 My fun @electronjs project looks like a Windows 95 software and I think it's adorable.

### R1D31

More coding on @electronjs app.

### R1D32

R1D32 #100DaysOfCode: I finished my Node.js API powered by Hapi.js (not Express.js this time), CRUD actions and database connection today. I love the simplicity of lowdb for experimenting and fast prototyping.

Check it out if you don't know it yet: https://github.com/typicode/lowdb

### R1D33

R1D33 #100DaysOfCode: Okay, back to the serious stuff now after I have finished my @electronjs daily mood tracker fun app today ((link: https://github.com/gitfrosh/track-ur-mood) github.com/gitfrosh/track…).
😌 #electronjs #nextjs #hapijs #windows95 #react

Security Resources

- Knex.js or other ORMS
- nsp check, snyk test // check 3rd party libs
- logging; winston, morgan, pino, roarr

### R1D34

More Security Resources

- Set Content-Security-Policy
- csurf: more security for cookies
- https://www.hacksplaining.com/

### R1D35

Wow, time moves fast during the #100DaysOfCode and my to-do list is still long covering topics like server-side rendering, web components and React styling libs.
Also I'm still working on @andreineagoie|s #webdev course on #udemy and @svelte keeps popping up everywhere lately..

### R1D36

R1D36 #100DaysOfCode: Unfortunately, only minimal coding today: Read about @svelte and set up the sapper example app: https://github.com/sveltejs/sapper-template. Tomorrow I'll keep working on it.

### R1D37

R1D37 #100DaysOfCode: I started a fun project with @svelte today, played around with some open APIs and even tried out some #python web scraping. Will deploy tomorrow :)

### R1D38

R1D38 #100DaysOfCode: Took me a while, but now it's up and running: My >> false quotes generator << that missmatches mostly Simpsons' quotes to famous people. Have fun! :)
For the project I tried out @svelte and sapper with a #nodejs polka backend.

### R1D39

R1D39 #100DaysOfCode: A day without coding but at least reading about web security and code analysis. Tomorrow I will be starting learning about #docker and #kubernetes. Looking forward!!

### R1D40

No coding today.

### R1D41

R1D41 #100DaysOfCode: Hurray, today I created my first Dockerfile! I only finished a small introductory course about #devops and might continue tomorrow (if I get not distracted by a new side project idea I came upt with today)

- Docker can duplicate containers when app must scale
  DOCKER
- touch Dockerfile
- docker build -t superawesomecontainer .
- docker run -it superawesomecontainer
- docker run superawesomecontainer (& go inside container)
- docker run -it -d superawesomecontainer (run in background)
- docker ps (show all running containers)
- docker exec -it <hash> bash (go inside container)
- docker stop <hash>
- Dockerfile: FROM, WORKDIR, COPY, RUN, CMD
- port forwarding/binding: expose inner-container port to actual (host) machine:
  - docker run -it -p 3000:3000 superawesomecontainer
    DOCKER-COMPOSE
- touch docker-compose.yml
- sudo docker-compose build (you could "compose" just one service and build it from existing Dockerfile)
- rebuild everytime .yml changes
- sudo docker-compose run <service-name>
- sudo docker-compose down (kill everything)
- sudo docker-compose up --build (run all services)
- sudo docker-compose exec smart-brain-api bash (after up -d in background enter bash)

Resources

- hub.docker

### R1D42

No coding today.

### R1D43

R1D43 #100DaysOfCode: I finally catched up on authentication methods and read about JSON Web Tokens, and cookies. Oh and set up my first redis server for session management.

REDIS

- redis-cli
- redis-server
- commands: SET, GET, EXISTS, DEL, EXPIRE session 10, INCRBY counter 33, DECR counter (default is 1), MSET (set multiple values), MGET
- hashes: HMSET user id 45 name "John", HGET user id, HGETALL
- lists: LPUSH ourlist 10, RPUSH/LPUSH ourlist "hello", LRANGE ourlist 0 1 (show content), RDROP, LPOP/RPOP
- sets (no duplicate values): SADD ourset 1 2 3 4 5, SMEMBERS ourset (show content), SISMEMBER ourset 5
- sorted sets: ZADD team 1 "Wizards", ZRANK

AUTHENTICATION

- COOKIE-BASED

* user sends username & password to server, server checks and answers with cookie (in header: session: "randomstring123445"), identifies browser which saves it in internal datastore
* everytime a user returns the browser asks for the same cookie and server authenticates if cookie is the same
* on logout the session will be destroyed

- TOKEN-BASED (JWT is most popular)

* user sends username & password to server, server checks and answers with token (in header: token: "randomstring123445"), identifies browser which saves it in internal datastore and resends it to server with every request, server verifies it without!! database just with method
* JWT can even store information like user ID, ..
* on logout the token will be destroyed
* token can be used throughout different apis
* can server mobile/browser

### R1D44

R1D44 #100DaysOfCode: Today was intense: My first try using #Swagger and #Node.js #Hapi to generate a #RESTful API out of a huge dataset. Good Night for now!

### R1D45

R1D45 #100DaysOfCode: Playing around with my biiig #data set and #python's #pandas library .. actually having fun because things just work?!
#webdev #data #DataScience #DataAnalytics
(link: http://pandas.pydata.org) pandas.pydata.org

### R1D46

R1D46 #100DaysOfCode: Finished working on my database and started a new frontend based on #Nuxt.js. Oh I think I need to slow down a bit when learning new stuff to avoid my sloppyness.

### R1D47

No coding today.

### R1D48

R1D48 #100DaysofCode: Struggled a bit with my #Hapi server-side rendering #React app but got everything working in the end.
👊 Next days will be about #css styling, typography and beautifying.
#ssr #Javascript #codinglife #coders #webdev

### R1D49

No coding today.

### R1D50

Hurray, I finished the first half of my #100DaysofCode challenge and I loved it so far!! Connecting to other coders on twitter makes it so very inspiring and motivating, I already learned & built so much I'm totally looking forward towards the 2nd half!
#womenwhocode #coderslife

### R1D51

R1D51 #100DaysOfCode: Sometimes you just _know_ that you already solved that particular tiny problem sometime in the past but you just can't remember how and it's driving you insane.

Will continue working on my #hapi authorization issues tomorrow...
#javascript #react #coding

### R1D52

R1D52 #100DaysOfCode: So I fixed some routing issues in my #NodeJS #Hapi backend and there's no way around #JSON Web Tokens tomorrow. Is there anybody actually enjoying authorization implementation?
😆 #coderslife

### R1D53

R1D53 #100DaysOfCode: Set up my JSON Web Tokens authorization logic today, login and logout for my new web app. Went smoothly in the end thanks to this great #NodeJS #Hapi plugin: https://github.com/dwyl/hapi-auth-jwt2

### R1D54

R1D54 #100DaysOfCode: So I implemented some cookie
🍪 handling and conditional #reactjs rendering today regarding my login / logout logic and I really need to read more about security best practices
😬 (still not my favourite topic)
#coderslife #womenwhocode

### R1D55

R1D55 #100DaysOfCode: Some frustrating debugging sessions today.
🙄 Over and out.

### R1D56

No coding today.

### R1D57

R1D57 #100DaysOfCode: Rebuilt my #React forms with Formik due to security reasons and enjoyed working with the library. (link: https://jaredpalmer.com/formik/) jaredpalmer.com/formik/ Tomorrow I have some #MongoDB #Mongoose tasks on my to-do list. #coderslife ⛳️

### R1D58

R1D58 #100DaysOfCode: My open #MongoDB issues were easily done and I wrote some documentation on my new #Hapi powered app. But honestly, my knowledge about server performance is poor especially when it comes to scaling and dealing with many requests.

### R1D59

No coding today.

### R1D60

R1D60 #100DaysOfCode: Procrastination is finally here!
😣 Minimal progress today and there is still lots of data cleaning to do.
I'm going on a short holiday tomorrow so even better excuses arrive.
#coderslife #womenintech #womenwhocode

### R1D61

No coding today.

### R1D62

R1D62 #100DaysOfCode: At least minimal progress on my RESTful #Node.js #Hapi #SSR #React project. I must say the decision to build a server-side rendering solution mostly got me into troubles :D
Oh and I need to catch up with all the cool #coder's newsletters I receive.

### R1D63

No coding today.

### R1D64

R1D64 #100DaysOfCode: Finally a productive day again, done some coding in the morning & evening and cleaned up my #MongoDB data mess. Also I introduced the awesome #dotenv lib in my project for managing environment variables.
Good night, folks!

### R1D65

R1D65 #100DaysOfCode: My app is somewhat ready for deployment but I'd like to finish the CI/CD chapter of @AndreiNeagoie's advanced #webdev course first. I need to explore build pipelines and related topics - should be exciting!

### R1D66

R1D66 #100DaysOfCode: Gosh, I'm so tired. Berlin's heat is making me dizzy. Almost no progress today 🐌 Happy coding to y'all!

### R1D67

No coding today.

### R1D68

R1D68 #100DaysOfCode: Oh well. Looks like some major accessibility issues to solve tomorrow! I again deployed a new app to @heroku though everybody seems to be rather excited about @Netlify currently. 🤔

### R1D69

No coding today.

### R1D70

R1D70 #100DaysOfCode: Don't neglect accessibility in your web app! #lessonslearned

### R1D71

R1D71 #100DaysOfCode: Freshed up my project and added some additional progressive web app features #pwa. This looks waaay better now:

### R1D72

No coding today.

### R1D73

So I'm coding at the most beautiful working place since the start of my #100DaysOfCode challenge (the Northern German seaside) and it's a bit hard to keep track of my plans (though the wi-fi is fine).

### RD1D74

R1D74 #100DaysOfCode: Let me introduce my new finished fun project I have been building the last weeks: The Lord of the Rings API provides book, movie, character and quote data - powered by #ssr #react and #hapijs.

### R1D75

Wow, 3/4 of my #100DaysOfCode challenge are done today! I was not able to code every single day, but I liked my journey very much so far!

The last days will be probably mostly about building a twitter bot & digging into serverless apps, AWS Lambda, React Hooks & CSS Styling.

### R1D76

For the 3rd time I will be giving an introductory workshop in web development for women at the #InformaticaFeminale @UniBremen this August - in German (Registration is open here: https://www.informatica-feminale.de/eng/). Every year, I have to edit the course material heavily because web development is moving so fast!

### R1D77

R1D77 #100DaysOfCode: Sometimes it's the small things that is driving you mad, like adding a tiny @github corner logo onto your website. http://tholman.com/github-corners/

### R1D78

No coding today.

### R1D79

- notify me, when a new user registers on lotr api!
  AWS Services
- EC2: bare metal machine, e.g. Linux machine with Node preinstalled
- CloudFront: enhance distributions of static web files (like cdn / CloudFlare), html, css, js around the world
- S3: Object Storage Service: access it with id, e.g. image, json, .. (5GB max)
- Lambda: run single functions and scales: create a function through dashboard or serverless package..

Serverless

- npm install -g serverless
- serverless create -t aws-nodejs
- serverless invoke --function hello
- serverless invoke local --function hello (simulate the function locally)

### R1D80

R1D80 #100DaysOfCode: Not a lot of news today: i'm still working on @aws
lambda functions. I'd like to automatically send an e-mail to myself whenever somebody signs up on (link: https://the-one-api.herokuapp.com) the-one-api.herokuapp.com
Have a great weekend! 🐞

### R1D81

No coding today.

### R1D82

- CDN caching: service providers like CloudFlare offer CDN servers, so always the closest server replies to user request of a website, the original server provides the static files though; the speed improvements is done through caching; also there are security improvements and others
- gzip (quick way to make all served files smaller), brotli: even better alternative
- database performance improvements:
  - identify inefficient querys and building indexes on often used data
  - increase db memory
  - cache query solutions via redis or memchached
  - sharding (tough!) (cluser dbs like so: people younger than 30, peopler older than 30)
  - distribute request amount on multiple dbs; PostgreSQL is able to do that with multiple pools; or use a load balancer

Load Balancing
 - nginx.conf 
 worker_processes 1; // amount of CPUs
 events { worker_connections 1024; } // max of simultaneous connections of one worker
 http {
  upstream myapp1 {
    server web1:3000;
    server web2:3000;
    server web3:3000;
  }
 } // myapp1 for reference // 3 duplicate servers
 server {
    listen 80;
    location / {
      proxy_pass http://myapp1;
    }
 } // pass requests on :80 to myapp1

 Load Balancing Testing Libraries
  - loadtest
  - artillery
  - siege
  - wrk2


R1D82 #100DaysOfCode : A new week and a ton of things to learn about: cdn services like @Cloudflare, caching, load balancing and reverse proxy configs. I finally finished this superawesome @udemy course by @AndreiNeagoie

### R1D83

R1D83 #100DaysOfCode: Maybe I'm late discovering this but "30 seconds of code" is a great resource for #javascript developers with hundreds of snippets that can be of use in a wide range of situations.💡

### R1D84

OMG. Finally a tool for really lazy developers (like me): Generate a superpretty README file in just seconds: https://github.com/kefranabg/readme-md-generator … #coding #webdev #webdesign

### R1D85

R1D85 #100DaysOfCode: This was fun! I finished the friendly fem tech bot that retweets topics with hashtags like #girlswhocode #womenintech, and others. Follow @femtech_ for news from the community. I wrote a tutorial for the Twitter bot: https://rike.dev/2019/06/26/how-to-build-a-twitter-bot-with-node-js-fast

### R1D86
