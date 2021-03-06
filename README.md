State, Props, and Forms - React Music App
In this project, you will work with using state, props, and forms to create an application that shares the song you are listening to or suggesting to other users.

To help you with the AJAX request functionality, there are some functions to copy and paste included in the tinylasagna.js file in the starter_files.

Download Starter Files
tinylasagna.js.zip (1 KB)
Inside of the starter_files, you'll find one file.

tinylasagna.js: this file contains functions that will need to be pasted into the corresponding components to help the functionality of your application.
Objectives  
You will need to create a new React application using create-react-app.
You will need to create styles and components folders and place the appropriate files in each, being sure to link the other files correctly to each other.
Your project will need to have the following components:
App.js
NavBar.js
PlayListForm.js
PlayList.js
PlayListItem.js
You can use Bootstrap 4 for styling of this project.

Bootstrap 4 Link
Simply add the <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/css/bootstrap.min.css" integrity="sha384-rwoIResjU2yc3z8GV/NPeZWAv56rSmLldC3R/AZzGRnGxQQKnKkoFVhFQhNUwEyJ" crossorigin="anonymous"> tag to your index.html file in your public directory.

If using Bootstrap, be sure to add a class="container" to your <div id="root"></div> tag in your index.html.
Adding the various class names will help automatically style many of your features.
This project is about managing state, props, lifecycles, and forms. The following should be true of your application:

Your PlayListcomponent should pass down the state in the form of props to your PlayListItem component which will render the actual play list entries. (Hint: PlayListItem should be imported in PlayList)

You App.js component should only have import statements for your NavBar, PlayList, and PlayListForm.
The state for your PlayListForm component should have userName, songArtist, songTitle, and songNotes in order to function properly with the fetch functions from the tinylasgna.js file that you will copy into the component. Follow the directions in that file.

The state for your PlayList should just have one key value pair, songs, in order to properly function with the fetch function from the tinylasagna.js file that you will copy into the PlayListComponent (follow the directions in that file).
The styling is up to you, but please make this a polished product!

Hints  
This will be structuring a working application. Be sure to link up everything properly and look through the Facebook React Docs to help answer any questions.

In order to deploy this application on gh-pages on GitHub checkout the following link: Deploying a Create React App. Skip to the portion about gh-pages and following along!

Don't forget how to handle input changes - here's a tasty example:

<input  onChange={this.handleUserName}
        type="text"
        className="form-control"
        id="user"
        placeholder="Name or User Name"
        value={this.state.userName}/>
        
Be sure to add the corresponding methods or expressions to your component. Look back over the lesson material for help.
