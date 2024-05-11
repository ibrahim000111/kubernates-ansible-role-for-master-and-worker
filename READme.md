#system requiremnt

RAM: 2GB  cpu: 2vcpu

#run playbook

ansible-playbook -i inventory main.yml

#run regenrate token command at master node
"kubeadm token create --print-join-command" 

#past output of token comand at worker node
