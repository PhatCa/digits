<img src="doc/digit.png">

## Digit Application
Clone down the project then run command:

```
$ meteor npm install
```
Once the dependencies already downloaded run command to start project:
```
$ meteor npm run start
```

Go to http://localhost:3000/list to preview the application.

* username: john@foo.com
* password: changeme
* username: admin@foo.com
* password: changeme

User will be able to create list of contacts by going to add Contact on the navbar.
User will be able to view/edit their list of contacts in the Lists contact on the navbar.


[//]: # (![]&#40;https://github.com/ics-software-engineering/meteor-application-template-react/raw/main/doc/landing-page.png&#41;)

[//]: # ()
[//]: # (meteor-application-template-react is a sample Meteor 2.9 application that illustrates: )

[//]: # ()
[//]: # (  * A standard directory layout using 'imports/' as recommended in the [Meteor Guide]&#40;https://guide.meteor.com/structure.html&#41;)

[//]: # (  * [Bootstrap 5 React]&#40;https://react-bootstrap.github.io/&#41; for user interface.)

[//]: # (  * [Uniforms]&#40;https://uniforms.tools/&#41; for form development.)

[//]: # (  * [alanning:roles]&#40;https://github.com/alanning/meteor-roles&#41; to implement a special "Admin" user.)

[//]: # (  * Authorization, authentication, and registration using built-in Meteor packages.)

[//]: # (  * Initialization of users and data from a settings file.)

[//]: # (  * Alerts regarding success or failure of DB updates using [Sweet Alert]&#40;https://sweetalert.js.org/&#41;.)

[//]: # (  * Quality assurance using [ESLint]&#40;http://eslint.org&#41; with packages to partially enforce the [Meteor Coding Standards]&#40;https://guide.meteor.com/code-style.html&#41; and the [AirBnB Javascript Style Guide]&#40;https://github.com/airbnb/javascript&#41;.)

[//]: # ()
[//]: # (The goal of this template is to help you get quickly started doing Meteor development by providing a reasonable directory structure for development and deployment, a set of common extensions to the core framework, and boilerplate code to implement basic page display, navigation, forms, roles, and collection manipulation.)

[//]: # ()
[//]: # (To keep this codebase simple and small, some important capabilities are intentionally excluded from this template:)

[//]: # ()
[//]: # (  * Unit Testing.)

[//]: # (  * Security &#40;meteor-application-template-react enables the insecure packages&#41;)

[//]: # (  * Deployment)

[//]: # ()
[//]: # (Examples of the these capabilities will be provided elsewhere.)

[//]: # ()
[//]: # (## Installation)

[//]: # ()
[//]: # (First, [install Meteor]&#40;https://www.meteor.com/install&#41;.)

[//]: # ()
[//]: # (Second, go to [https://github.com/ics-software-engineering/meteor-application-template-react]&#40;https://github.com/ics-software-engineering/meteor-application-template-react&#41;, and click the "Use this template" button. Complete the dialog box to create a new repository that you own that is initialized with this template's files.)

[//]: # ()
[//]: # (Third, go to your newly created repository, and click the "Clone or download" button to download your new GitHub repo to your local file system.  Using [GitHub Desktop]&#40;https://desktop.github.com/&#41; is a great choice if you use MacOS or Windows.)

[//]: # ()
[//]: # (Fourth, cd into the app/ directory of your local copy of the repo, and install third party libraries with:)

[//]: # ()
[//]: # (```)

[//]: # ($ meteor npm install)

[//]: # (```)

[//]: # ()
[//]: # (## Running the system)

[//]: # ()
[//]: # (Once the libraries are installed, you can run the application by invoking the "start" script in the [package.json file]&#40;https://github.com/ics-software-engineering/meteor-application-template-react/blob/master/app/package.json&#41;:)

[//]: # ()
[//]: # (```)

[//]: # ($ meteor npm run start)

[//]: # (```)

[//]: # ()
[//]: # (The first time you run the app, it will create some default users and data. Here is the output:)

[//]: # ()
[//]: # (```)

[//]: # ( meteor npm run start )

[//]: # ()
[//]: # (> meteor-application-template-react@ start /Users/carletonmoore/GitHub/ICS314/meteor-application-template-react/app)

[//]: # (> meteor --no-release-check --exclude-archs web.browser.legacy,web.cordova --settings ../config/settings.development.json)

[//]: # ()
[//]: # ([[[[[ ~/GitHub/ICS314/meteor-application-template-react/app ]]]]])

[//]: # ()
[//]: # (=> Started proxy.                             )

[//]: # (=> Started HMR server.                        )

[//]: # (=> Started MongoDB.                           )

[//]: # (I20220529-12:09:18.384&#40;-10&#41;? Creating the default user&#40;s&#41;)

[//]: # (I20220529-12:09:18.389&#40;-10&#41;?   Creating user admin@foo.com.)

[//]: # (I20220529-12:09:18.453&#40;-10&#41;?   Creating user john@foo.com.)

[//]: # (I20220529-12:09:18.515&#40;-10&#41;? Creating default data.)

[//]: # (I20220529-12:09:18.515&#40;-10&#41;?   Adding: Basket &#40;john@foo.com&#41;)

[//]: # (I20220529-12:09:18.599&#40;-10&#41;?   Adding: Bicycle &#40;john@foo.com&#41;)

[//]: # (I20220529-12:09:18.600&#40;-10&#41;?   Adding: Banana &#40;admin@foo.com&#41;)

[//]: # (I20220529-12:09:18.601&#40;-10&#41;?   Adding: Boogie Board &#40;admin@foo.com&#41;)

[//]: # (I20220529-12:09:18.773&#40;-10&#41;? Monti APM: completed instrumenting the app)

[//]: # (=> Started your app.)

[//]: # ()
[//]: # (=> App running at: http://localhost:3000/)

[//]: # (```)

[//]: # ()
[//]: # (Periodically, you might see `Error starting Mongo &#40;2 tries left&#41;: Cannot run replSetReconfig because the node is currently updating its configuration` after the `=> Started HMR server.`. It doesn't seem to be a problem since the MongoDB does start.)

[//]: # ()
[//]: # (### Viewing the running app)

[//]: # ()
[//]: # (If all goes well, the template application will appear at [http://localhost:3000]&#40;http://localhost:3000&#41;.  You can login using the credentials in [settings.development.json]&#40;https://github.com/ics-software-engineering/meteor-application-template-react/blob/main/config/settings.development.json&#41;, or else register a new account.)

[//]: # ()
[//]: # (### ESLint)

[//]: # ()
[//]: # (You can verify that the code obeys our coding standards by running ESLint over the code in the imports/ directory with:)

[//]: # ()
[//]: # (```)

[//]: # (meteor npm run lint)

[//]: # (```)

[//]: # ()
[//]: # (## Walkthrough)

[//]: # ()
[//]: # (The following sections describe the major features of this template.)

[//]: # ()
[//]: # (### Directory structure)

[//]: # ()
[//]: # (The top-level directory structure is:)

[//]: # ()
[//]: # (```)

[//]: # (.github     # holds the GitHub Continuous Integration action and Issue template.)

[//]: # (app/        # holds the Meteor application sources)

[//]: # (config/     # holds configuration files, such as settings.development.json)

[//]: # (doc/        # holds developer documentation, user guides, etc.)

[//]: # (.gitignore  # don't commit IntelliJ project files, node_modules, and settings.production.json)

[//]: # (```)

[//]: # ()
[//]: # (This structure separates documentation files &#40;such as screenshots&#41; and configuration files &#40;such as the settings files&#41; from the actual Meteor application.)

[//]: # ()
[//]: # (The app/ directory has this structure:)

[//]: # ()
[//]: # (```)

[//]: # (.deploy/)

[//]: # (  .gitignore     # don't commit mup.js or settings.json)

[//]: # (  mup.sample.js  # sample mup.js file used for deploying the application)

[//]: # (  settings.sample.json # sample settings file)

[//]: # (  )
[//]: # (client/)

[//]: # (  main.html      # The boilerplate HTML with a "root" div to be manipulated by React.)

[//]: # (  main.js        # import startup files.)

[//]: # ()
[//]: # (imports/)

[//]: # (  api/           # Define collections)

[//]: # (    stuff/       # The Stuffs collection definition)

[//]: # (  startup/       # Define code to run when system starts up &#40;client-only, server-only, both&#41;)

[//]: # (    client/)

[//]: # (    server/)

[//]: # (  ui/)

[//]: # (    components/  # Contains page elements, some of which could appear on multiple pages.)

[//]: # (    layouts/     # Contains top-level layout &#40;<App> component&#41;.)

[//]: # (    pages/       # Contains components for each page.)

[//]: # ()
[//]: # (node_modules/    # managed by npm)

[//]: # ()
[//]: # (public/          # static assets &#40;like images&#41; can go here.)

[//]: # ()
[//]: # (server/)

[//]: # (   main.js       # import the server-side js files.)

[//]: # (   )
[//]: # (tests/           # testcafe acceptance tests.)

[//]: # (```)

[//]: # ()
[//]: # (### Import conventions)

[//]: # ()
[//]: # (This system adheres to the Meteor guideline of putting all application code in the imports/ directory, and using client/main.js and server/main.js to import the code appropriate for the client and server in an appropriate order.)

[//]: # ()
[//]: # (### Application functionality)

[//]: # ()
[//]: # (The application implements a simple CRUD application for managing "Stuff", which is a Mongo Collection consisting of a name &#40;String&#41;, a quantity &#40;Number&#41;, a condition &#40;one of 'excellent', 'good', 'fair', or 'poor'&#41; and an owner.)

[//]: # ()
[//]: # (By default, each user only sees the Stuff that they have created.  However, the settings file enables you to define default accounts.  If you define a user with the role "admin", then that user gets access to a special page which lists all the Stuff defined by all users.)

[//]: # ()
[//]: # (#### Landing page)

[//]: # ()
[//]: # (When you retrieve the app at http://localhost:3000, this is what should be displayed:)

[//]: # ()
[//]: # (![]&#40;https://github.com/ics-software-engineering/meteor-application-template-react/raw/main/doc/landing-page.png&#41;)

[//]: # ()
[//]: # (The next step is to use the Login menu to either Login to an existing account or register a new account.)

[//]: # ()
[//]: # (#### Login page)

[//]: # ()
[//]: # (Clicking on the Login link, then on the Sign In menu item displays this page:)

[//]: # ()
[//]: # (![]&#40;https://github.com/ics-software-engineering/meteor-application-template-react/raw/main/doc/signin-page.png&#41;)

[//]: # ()
[//]: # (#### Register page)

[//]: # ()
[//]: # (Alternatively, clicking on the Login link, then on the Sign Up menu item displays this page:)

[//]: # ()
[//]: # (![]&#40;https://github.com/ics-software-engineering/meteor-application-template-react/raw/main/doc/register-page.png&#41;)

[//]: # ()
[//]: # ()
[//]: # (#### Landing &#40;after Login&#41; page, non-Admin user)

[//]: # ()
[//]: # (Once you log in &#40;either to an existing account or by creating a new one&#41;, the navbar changes as follows:)

[//]: # ()
[//]: # (![]&#40;https://github.com/ics-software-engineering/meteor-application-template-react/raw/main/doc/landing-after-login-page.png&#41;)

[//]: # ()
[//]: # (You can now add new Stuff documents, and list the Stuff you have created. Note you cannot see any Stuff created by other users.)

[//]: # ()
[//]: # (#### Add Stuff page)

[//]: # ()
[//]: # (After logging in, here is the page that allows you to add new Stuff:)

[//]: # ()
[//]: # (![]&#40;https://github.com/ics-software-engineering/meteor-application-template-react/raw/main/doc/add-stuff-page.png&#41;)

[//]: # ()
[//]: # (#### List Stuff page)

[//]: # ()
[//]: # (After logging in, here is the page that allows you to list all the Stuff you have created:)

[//]: # ()
[//]: # (![]&#40;https://github.com/ics-software-engineering/meteor-application-template-react/raw/main/doc/list-stuff-page.png&#41;)

[//]: # ()
[//]: # (You click the "Edit" link to go to the Edit Stuff page, shown next.)

[//]: # ()
[//]: # (#### Edit Stuff page)

[//]: # ()
[//]: # (After clicking on the "Edit" link associated with an item, this page displays that allows you to change and save it:)

[//]: # ()
[//]: # (![]&#40;https://github.com/ics-software-engineering/meteor-application-template-react/raw/main/doc/edit-stuff-page.png&#41;)

[//]: # ()
[//]: # (#### Landing &#40;after Login&#41;, Admin user)

[//]: # ()
[//]: # (You can define an "admin" user in the settings.json file. This user, after logging in, gets a special entry in the navbar:)

[//]: # ()
[//]: # (![]&#40;https://github.com/ics-software-engineering/meteor-application-template-react/raw/main/doc/admin-landing-page.png&#41;)

[//]: # ()
[//]: # (#### Admin page &#40;list all users stuff&#41;)

[//]: # ()
[//]: # (To provide a simple example of a "super power" for Admin users, the Admin page lists all of the Stuff by all of the users:)

[//]: # ()
[//]: # (![]&#40;https://github.com/ics-software-engineering/meteor-application-template-react/raw/main/doc/admin-list-stuff-page.png&#41;)

[//]: # ()
[//]: # (Note that non-admin users cannot get to this page, even if they type in the URL by hand.)

[//]: # ()
[//]: # (### Collections)

[//]: # ()
[//]: # (The application implements a single Collection called "Stuffs". Each Stuffs document has the following fields: name, quantity, condition, and username.)

[//]: # ()
[//]: # (The Stuffs collection is defined in [imports/api/stuff/stuff.js]&#40;https://github.com/ics-software-engineering/meteor-application-template-react/blob/main/app/imports/api/stuff/stuff.js&#41;.)

[//]: # ()
[//]: # (The Stuffs collection is initialized in [imports/startup/server/Mongo.js]&#40;https://github.com/ics-software-engineering/meteor-application-template-react/blob/main/app/imports/startup/server/Mongo.js&#41;.)

[//]: # ()
[//]: # (### CSS)

[//]: # ()
[//]: # (The application uses the [React implementation of Bootstrap 5]&#40;https://react-bootstrap.github.io/&#41;. You can adjust the theme by editing the `app/client/style.css` file. To change the theme override the Bootstrap 5 CSS variables.)

[//]: # ()
[//]: # (```css)

[//]: # (/* Change bootstrap variable values.)

[//]: # ( See https://getbootstrap.com/docs/5.2/customize/css-variables/)

[//]: # ( */)

[//]: # (body {)

[//]: # (  --bs-light-rgb: 236, 236, 236;)

[//]: # (})

[//]: # ()
[//]: # (/* Define custom styles */)

[//]: # (.gray-background {)

[//]: # (  background-color: var&#40;--bs-gray-200&#41;;)

[//]: # (  color: var&#40;--bs-dark&#41;;)

[//]: # (  padding-top: 10px;)

[//]: # (  padding-bottom: 20px;)

[//]: # (})

[//]: # (```)

[//]: # ()
[//]: # (### Routing)

[//]: # ()
[//]: # (For display and navigation among its four pages, the application uses [React Router]&#40;https://reacttraining.com/react-router/&#41;.)

[//]: # ()
[//]: # (Routing is defined in [imports/ui/layouts/App.jsx]&#40;https://github.com/ics-software-engineering/meteor-application-template-react/blob/main/app/imports/ui/layouts/App.jsx&#41;.)

[//]: # ()
[//]: # ()
[//]: # (### Authentication)

[//]: # ()
[//]: # (For authentication, the application uses the Meteor accounts package.)

[//]: # ()
[//]: # (When the application is run for the first time, a settings file &#40;such as [config/settings.development.json]&#40;https://github.com/ics-software-engineering/meteor-application-template-react/blob/main/config/settings.development.json&#41;&#41; should be passed to Meteor. That will lead to a default account being created through the code in [imports/startup/server/accounts.js]&#40;https://github.com/ics-software-engineering/meteor-application-template-react/blob/main/app/imports/startup/server/accounts.js&#41;.)

[//]: # ()
[//]: # (The application allows users to register and create new accounts at any time.)

[//]: # ()
[//]: # (### Authorization)

[//]: # ()
[//]: # (Only logged in users can manipulate Stuff documents &#40;but any registered user can manipulate any Stuff document, even if they weren't the user that created it.&#41;)

[//]: # ()
[//]: # (### Configuration)

[//]: # ()
[//]: # (The [config]&#40;https://github.com/ics-software-engineering/meteor-application-template-react/blob/main/config&#41; directory is intended to hold settings files.  The repository contains one file: [config/settings.development.json]&#40;https://github.com/ics-software-engineering/meteor-application-template-react/blob/main/config/settings.development.json&#41;.)

[//]: # ()
[//]: # (The [.gitignore]&#40;https://github.com/ics-software-engineering/meteor-application-template-react/blob/main/.gitignore&#41; file prevents a file named settings.production.json from being committed to the repository. So, if you are deploying the application, you can put settings in a file named settings.production.json and it will not be committed.)

[//]: # ()
[//]: # (### Quality Assurance)

[//]: # ()
[//]: # (#### ESLint)

[//]: # ()
[//]: # (The application includes a [.eslintrc]&#40;https://github.com/ics-software-engineering/meteor-application-template-react/blob/main/app/.eslintrc&#41; file to define the coding style adhered to in this application. You can invoke ESLint from the command line as follows:)

[//]: # ()
[//]: # (```)

[//]: # ([~/meteor-application-template-react/app]-> meteor npm run lint)

[//]: # ()
[//]: # (> meteor-application-template-react@ lint /Users/philipjohnson/meteor-application-template-react/app)

[//]: # (> eslint --quiet ./imports)

[//]: # (```)

[//]: # ()
[//]: # (ESLint should run without generating any errors.)

[//]: # ()
[//]: # (It's significantly easier to do development with ESLint integrated directly into your IDE &#40;such as IntelliJ&#41;.)

[//]: # ()
[//]: # (## Screencasts)

[//]: # ()
[//]: # (For more information about this system, please watch one or more of the following screencasts. Note that the current source code might differ slightly from the code in these screencasts, but the changes should be very minor.)

[//]: # ()
[//]: # (  * [Walkthrough of system user interface &#40;6 min&#41;]&#40;https://youtu.be/48xu1hrqUi8&#41;)

[//]: # (  * [Data and accounts structure and initialization &#40;18 min&#41;]&#40;https://youtu.be/HZRjwrVBWp4&#41;)

[//]: # (  * [Navigation, routing, pages, components &#40;34 min&#41;]&#40;https://youtu.be/XztTdHpv6Jw&#41;)

[//]: # (  * [Forms &#40;32 min&#41;]&#40;https://youtu.be/8FyWR3gUGCM&#41;)

[//]: # (  * [Authorization, authentication, and roles &#40;12 min&#41;]&#40;https://youtu.be/9HX5vuXTlvA&#41;)
