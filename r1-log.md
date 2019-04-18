# #100DaysOfCode Log - Round 1 - Rika

The log of my #100DaysOfCode challenge. Started on [March 31, Sunday, 2019].

## Log

### R1D1 
* set up github (https://github.com/gitfrosh/100-days-of-code-projects) & logbook & twitter
* mini-code "when does the challenge finish?" (https://github.com/gitfrosh/100-days-of-code-projects/tree/master/timer)
* check out https://github.com/florinpop17/app-ideas
* collect projects:
    * dig into Javascript Grammar book
    * Vue.js introductory course
    * DevOps course
    * finish Smart Home tutorial
    * search an Open Source project and contribute
    * revamp ueberdiespree.de
    * https://www.frontendmentor.io/
    * build a Go Backend
    * build an Electron App
    * take tutorials on nodeschool
    * dig into typescript
    * Junior to Senior Udemy Course https://www.udemy.com/the-complete-junior-to-senior-web-developer-roadmap/
    * what to do with Firebase?
    * finish IF course

### R1D2
Reworked my #nodejs mini server app to a #go #golang powered app and realised how much I got used to javascript's lack of typesafety. Took me some time! (Never worked with Go before)

* go run start.go

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
