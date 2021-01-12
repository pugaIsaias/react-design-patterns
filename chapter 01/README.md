## Notes

- React uses a declarative approach to programming.

- The difference between imperative programming (step by step) and declarative programming (asking for the outcome).

- Declarative programming is easier to understand at first glance. And imperative takes more effort.

- React wants to have styles, templates, and JavaScript functionality on the same document. (Something that Vue takes on, as the youngest of the bunch.)

- It can be a little overwhelming or cause JavaScript Fatigue all the technologies, tools, packages managers, transpilers, module bundlres, and infinite list of different libraries.

---

### Breaking it down, to avoid fatigue.

- But a good way to to start for a simple UI, is use createElements.

- When it gets more complex. We can include a transpiler to enable JSX to convert it into JavaScript.

- As the app grows a bit more, we may need a router to handle different pages and views.

---<07/01/2021> at this time i don't understand completely vvv ---

- At some point, we may want to load data from some API endpoints, and if the application keeps growing, we will reach the point where we need some external dependencies to abstract complex operations. Only in that very moment, should we introduce a package manager.

--- <07/01/20201> Got no idea of why vvv ---

- Then the time will come to split out application into separeted modules and organize out files in the right way. At that point, we should start thinking about suing module bundler.

---

#### Using CLI to start a React App

`npm install -g create-react-app`

`create-react-app hello-world`

`npm start`
