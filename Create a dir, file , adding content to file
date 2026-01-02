name: my-playbook
hosts: all
become: true
tasks :
name: creating-directory
file:
path: /root/ansible-test
state: directory

- name: creating-file
file:
path: /root/ansible-test/myfile
state: touch

- name: adding content
copy :
dest: /root/ansible-test/myfile
content:
today is friday ..
