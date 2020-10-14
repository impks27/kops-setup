# kops-setup

https://stackoverflow.com/questions/37955942/vagrant-up-vboxmanage-exe-error-vt-x-is-not-available-verr-vmx-no-vmx-code

To turn Hypervisor off, run this from Command Prompt (Admin) (Windows+X):

bcdedit /set hypervisorlaunchtype off
and reboot your computer. To turn it back on again, run:

bcdedit /set hypervisorlaunchtype on
If you receive "The integer data is not valid as specified", try:

bcdedit /set hypervisorlaunchtype auto
