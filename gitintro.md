n order to collaborate on Git projects, you must interact with remote repositories
, or online or network versions of the project.
 With it, read / write or read-only privileges can be obtained.
 Teams are allowed to use remote repositories to send information 
and pull data from them
cloned repositorise
cloned repositories, Git will automatically give the name “origin” to the server
 from which you cloned and the name “master” to your local branch.

ex:
git remote  ..to see short name such as "origin"
git remote-v  ..too see remote URLS ADDING short name

Adding Remotes
git remote add shortname url
ex: git remote add js "ttps:github.com/janesmith/project1"

Renaming/Removing Remotes
To rename a remote’s short name
$ git remote rename js jane2
$ git remote…