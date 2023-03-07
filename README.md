

ToDo Application

You can view the application use demo by viewing "Apptest_REC.mp4" also you can check the actual Ansible deployment by viewing "PlaybookDeploy_REC.mp4"

The remote Azure VM is a public VM and you can access it with RDP/xRDP (with LinuxVM1.rdp) or with ssh. Credentials are testuser/testpass for both methods. Start the application by opening a web browser (Firefox) and go to localhost:3000.

Application was deployed to remote Linux Azure VM by using Ansible playbook together with Docker Compose. You can inspect the Ansible playbook at "playbook.yml". Port for application was set with inventory config file called "inventory.ini". The Ansible file first makes sure that all prerequisites are installed - Then installs Docker and Docker Compose - and then builds the containers.

Don't hesitate to contact me at petcu95@gmail.com for any questions.
