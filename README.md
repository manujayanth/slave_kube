# slave_kube

To create the Kubernetes slave nodes over aws using ansible

1. Create the key and value pair(tag_name) for Masternode such as --Name:MasterKube

2. Create the key and value pair(tag_name) for Slavenodes such as --Name:SlaveKube

3. Run the master.yml playbook and will generate the token automatically and store in /root directory

4.Run the slave.yml playbook and it will automatically use the token generated by master

Note: Run the Masternode playbook before ruuning the slavenode playbook
