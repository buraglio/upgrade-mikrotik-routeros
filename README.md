# mikrotik-upgrade
## What?
Ansible playbook to set the software channel and update mikrotik devices

## Why?
Why not? This is super simple and was a fun start to using the routeros module. It's also better to automate anything you need to do more than once, take humans out of the loop of repetitive tasks, and generally be more efficient. I couldn't find anything else using the routeros module that did this, either. Use it until something better comes along. 

## How?
Install ansible. Clone the repo and adjust the variables, accounting for your own file hierarchy. 
Then run the command: `ansible-playbook /etc/ansible/playbooks/mikrotik-upgrade.yml`

## To Do
Make this work serially down the list.

## other stuff
*Use anything I write at your own peril.* 

Thanks to [Sam Oehlert](https://github.com/soehlert) for helping teach me the fundamentals. 

Sometimes I put stuff on my [website](https://www.forwardingplane.net). You can contact me via [email](mailto:buraglio@forwardingplane.net) or [Twitter](https://www.twitter.com/buraglio) or [LinkedIN](https://www.linkedin.com/in/buraglio/). I'm not always responsive in a timely manner and probably won't be able to help you do ansible stuff, but generally do eventually reply.   

