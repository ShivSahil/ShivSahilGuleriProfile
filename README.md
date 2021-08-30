# Building From Sources
To build project from sources you first need to have a working `docker`, `docker-compose`, and `git` 
installed on your system. After installing the requirements, you open a terminal window (i.e., a command prompt) and 
type the following:

    git clone https://github.com/ShivSahil/ShivSahilGuleriProfile.git
    cd ShivSahilGuleriProfile
  
  ## Build and run your app with Compose
  From your project directory, start up your application by running
  
    docker-compose up
   If you want to run your services in the background, you can pass the -d flag (for “detached” mode) to docker-compose up.
   
  ## Access the site
  Enter http://0.0.0.0:4000/ShivSahilGuleriProfile/ in a browser to see the application running.
  
  ## Make Changes
  Now, feel free to customize the theme however you like (don't forget to change the name!). After you are done, commit your final changes.
  
  Make the change in the project directory using any text editor and check the live updates refershing the site.
    
  ## Stop the application
 Either by running 
 
    docker-compose stop
    
 from within your project directory in the second terminal, or by hitting `CTRL+C` in the original terminal where you started the app.
 
 ## Removing the containers entirely
 You can bring everything down, removing the containers entirely, with the `down` command.
 Pass `--volumes` to also remove the data volume used by the container:
 
    docker-compose down --volumes
