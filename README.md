# 3rdPartyLib

This is simply a repository of commonly used 3rd party js / css files that may be easily linked to.
(some repositories may reference files in this library)

including:
* standard jquery files
* bootstrap files + some bootstrap plugins (eg dataTables)
* angular files

Example of usage:

clone this repository into a base directory called 'lib':

eg:
> cd /home/node
> clone <git_url> lib

For node.js using sails:
> cd /home/node/thisProject

check to see if assets/js/dependencies/ contains links to files in the lib directory
(current repositories may already include this link)

If not already defined, or using a project not already utilizing these links, you can create them yourself:

eg:
> cd assets/js/dependencies
> ln -s ./../../../../lib/lodash.min.js lodash.min.js

