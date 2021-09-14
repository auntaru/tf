# terraform examples

terraform examples on how to setup your local libvirt/qemu lab

## Terraform 0.13 - Libvirt 0.6.2 - Ubuntu 20.04 LTS

https://github.com/ebal/tf/tree/master/0.13/libvirt/0.6.2/ubuntu/20.04

## Terraform 0.15 - Libvirt 0.6.3 - Ubuntu 20.04 LTS

https://github.com/ebal/tf/tree/master/0.15/libvirt/0.6.3/ubuntu/20.04


https://balaskas.gr/blog/2020/09/12/vms-on-kvm-with-terraform/

https://www.digitalocean.com/community/tutorials/how-to-use-cloud-config-for-your-initial-server-setup

https://initx.dev/devops/terraform-libvirt/

https://computingforgeeks.com/how-to-provision-vms-on-kvm-with-terraform/

https://fedoramagazine.org/setting-up-a-vm-on-fedora-server-using-cloud-images-and-virt-install-version-3/

https://www.desgehtfei.net/en/quick-start-kvm-libvirt-vms-with-terraform-and-ansible-part-2/

https://fabianlee.org/2021/07/05/kvm-installing-terraform-and-the-libvirt-provider-for-local-kvm-resources/
https://fabianlee.org/2020/02/22/kvm-terraform-and-cloud-init-to-create-local-kvm-resources/
https://github.com/auntaru/terraform-libvirt-ubuntu-examples
https://github.com/fabianlee/terraform-libvirt-ubuntu-examples

https://yping88.medium.com/building-and-installing-terraform-provider-for-libvirt-a08a29f93135

https://blog.ruanbekker.com/blog/2020/10/08/using-the-libvirt-provisioner-with-terraform-for-kvm/

https://initx.dev/devops/terraform-libvirt/
Disable selinux :
sed -i 's/security_driver = "selinux"/security_driver = "none"/g' /etc/libvirt/qemu.conf
systemctl restart libvirtd


https://en.wikipedia.org/wiki/Open_vSwitch

