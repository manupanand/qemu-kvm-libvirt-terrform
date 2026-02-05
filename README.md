# qemu-kvm-libvirt-terrform
terrform module to create vm and on linux servers
--
anisble
ansible-playbook -i inventory.ini playbook.yml \
  -e "role_name=installkvm" \
  -e "ansible_user=$USER" \
  --ask-become-pass
  
  