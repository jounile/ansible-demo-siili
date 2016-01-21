# Ansible demo

# Let´s play!
$ ansible-playbook -i inventory site.yml

# EC2 inventory across all regions
sudo /etc/ansible/ec2.py --list

# To see the complete list of variables available for an instance
$ sudo /etc/ansible/ec2.py --host <ip-address-here>
