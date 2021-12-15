# ansible_desktop
Ansible playbooks for desktop config

git clone --recursive https://github.com/isavitsky/ansible_desktop

sudo pacman -S ansible
sudo pacman -S --needed base-devel

ansible-playbook -K local-install.yml
ansible-setup -K local-install.yml

