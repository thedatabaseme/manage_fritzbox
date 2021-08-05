Manage_Fritzbox
=========

This Playbook enables you to Reboot your AVM Fritzbox or any AVM WLAN Repeater.
In the future, there are plans to add several other Playbooks.

Requirements
------------

- Ansible 2.7

Example Playbook run
----------------

An example Playbook Call looks like this. Ofcourse you may want to specify the Variables within your Playbook or within your Inventory:
You can specify a List of IP Adresses when calling the Playbook. Each of which will be rebootet.

    - ansible-playbook reboot_fritzbox.yml -e "fritzbox_user=myuser fritzbox_password=supersecret ip_list=192.168.178.2" -k -K -u <username>
    
Author Information
------------------

This Role is created by P. Haberkern (thedatabaseme)
