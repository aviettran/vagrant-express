From git bash (Run as Administrator):
vagrant up
vagrant ssh

vagrant up will take some time. There may be some scary warnings -- can safely ignore them.

Then enter:

cd /vagrant
express <project_name>
cd <project_name> && npm install
DEBUG=myapp ./bin/www

You can also reach your project from your host machine in the folder <project_name>