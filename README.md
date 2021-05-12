# ansible
test
https://github.com/javahometech/
ansible-playbook -i hosts pull_docker_image.yaml --extra-vars="ansible_python_interpreter=/usr/bin/python3"

- name: pull an image
  docker_image:
    name: pacur/centos-7
    source: pull
