# Ansible Practice Questions

## 1. Creating Users:
- Create a playbook to create three users (user1, user2, user3) on all hosts in your inventory.
- Ensure that each user has a home directory and a default shell of `/bin/bash`.

## 2. Installing Packages:
- Write a playbook that installs `nginx` on all web_servers.
- Ensure that `nginx` is started and enabled to start on boot.

## 3. Managing Files and Directories:
- Create a playbook that creates a directory `/var/www/html` on all hosts.
- Copy an `index.html` file from your local machine to the `/var/www/html` directory on all hosts.

## 4. Service Management:
- Write a playbook to stop the `firewalld` service on all web_servers.
- Ensure that the service is disabled and will not start at boot.

## 5. Using Loops:
- Create a playbook to install a list of packages (`httpd`, `php`, `mysql-server`) on all web_servers.
- Use the loop keyword to iterate over the list of packages.

## 6. Handling Variables and Templates:
- Write a playbook that uses a template file (`nginx.conf.j2`) to configure `nginx` on all web_servers.
- Use variables in the template to set the server name and document root.

## 7. Conditionals and Handlers:
- Create a playbook to install `httpd` on all hosts.
- Restart the `httpd` service only if the installation task changes anything.

## 8. Gathering Facts:
- Write a playbook to gather system facts from all hosts.
- Use the gathered facts to print the hostname and IP address of each host.

## 9. Tags and Includes:
- Create a playbook with multiple tasks for installing and configuring `nginx` and `mysql`.
- Use tags to run only the `nginx` related tasks.

## 10. Using Roles:
- Create a role named `webserver` to install and configure `nginx`.
- Use the role in a playbook to apply the webserver configuration to all web_servers.
