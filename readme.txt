From git bash:
vagrant up
vagrant ssh

vagrant up will take some time. There may be some scary warnings -- can safely ignore them.

From the user directory:

express <project_name>
cd <project_name> && npm install
DEBUG=myapp ./bin/www