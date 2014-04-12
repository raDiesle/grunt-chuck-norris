grunt-chuck-norris
==================

A migration of the jenkins / hudson chuck norris plugin to the grunt build ci process



How to use:

1. Add to your package.json:
  "devDependencies": {
...
    "grunt-chuck-norris": "~0.0.1"
...
	},

2. In your Gruntfile.js add
   grunt.loadNpmTasks('grunt-chuck-norris');
3.Call grunt chuckNorris from Commandline or  
  extend your existing tasks like this:
 // Default task(s).
  grunt.registerTask('default', ['uglify']);





TODO: Add some fancy Text-Styling
