# An Eclipse plugin to for Jerkar

As pure java tool, Jerkar does not need specific tooling to be used kindly in an IDE. Neverthless, some task as scaffolding or updating .classpath are welcome to be integrated in contextual menu for better user experience.

The plugin can be installed using site update : <i>http://project.jerkar.org/eclipsePlugin4Jerkar/site</i> .

For now, this plugin provides a "Jerkar" menu extension when right clicking on a project. The extension provides :

* Launch : open sub-menu for executing any build method on selected project.
* Update classpath : this will align Eclipse .classpath with the dependencies declared in Jerkar build class.
* Scaffold projects : this will create folder structure along a basic build class for starting up projects. It can be classic Java project or Spring Boot project.

Now the last methods executed with the plugin are kept in favorite at the top of the entry menu. To edit or delete it, press `ctrl` + left click on it.


<br/>
<br/>


<img src="http://project.jerkar.org/eclipsePlugin4Jerkar/img/screenshot.png"/>


## How to contribute ?

Both plugin and feature project are located in the master branch of this repository.
The site update is located in the gh-pages branch of this repository.

The plugin is at its early stage, the current code base is very small so it's really easy to get inside.

