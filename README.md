O2O Worldwide Store
=====================

[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)

[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)




This seed is simple and to the point.
If you want something more fancy and complicated, I recommend you to check out AngularJS generator for Yeoman.

#### Key features. ####

 1. **Gulp** - Use Gulp to minify and build project files and watch for changes while you code.
 2. **AngularJS Structure** - Structure that makes sense and is used by the AngularJS community.
 3. **AngularJS Filters** - Built-in filters that I find useful.
 3. **Bower** - Utilize Bower to have your JS libraries under control.
 4. **Bootstrap** - Bootstrap front-end framework and including bootstrap directives ([http://angular-ui.github.io/bootstrap/]) for AngularJS.
 5. **Icons** - FontAwesome and Ionic awesomeness to use with your Bootstrap front-end.
 6. **Helpers** - Libraries that is a must for every major web application: Moment, Underscore and jQuery Core.
 7. **Sass** - Allows to use Sass as a project styling preprocessor. Sass is built with gulp-sass nodeJS package.

#### Prerequisites ####

- node.js [http://nodejs.org/]
- npm [http://www.npmjs.org/]
- bower [http://bower.io/]
- gulp.js [http://gulpjs.com/]

#### Installation and Usage ####

First of all you need to have [Node.js] (http://nodejs.org/).

Install bower globally
```
npm install -g bower
```

Install requirements
```
npm install
```

Install bower requirements (AngularJS, jQuery etc.)
```
bower install
```

Build project and watch for changes.
```
gulp
```

Build project.
```
gulp build
```

Watch for changes and build when occurred.
```
gulp watch
```

# AngularJS Project Structure

This seed proposes the following structure.

```
.
+-- app
¦   +-- app.js
¦   +-- css
¦   +-- fonts
¦   +-- images
¦   +-- js
¦       +-- controllers
¦       ¦   +-- controller_example.js
¦       +-- directives
¦       ¦   +-- directive_example.js
¦       +-- factories
¦       |   +-- factory_example.js
¦       +-- filters
¦       |   +-- filterX.js
|       +-- services
|           +-- service_example.js
|           +-- cache
|           ¦   +-- Cache1.js
|           ¦   +-- Cache2.js
|           +-- models
|               +-- Model1.js
|               +-- Model2.js
+-- build
|   +-- assets
|   +-- views
|   index.html
+-- test
+-- gulpfile.js
+-- bower.json
+-- package.json
```

# Other

Pull request gladly accepted. :)

