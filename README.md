# Ansible-Cobalt-Strike
An Ansible roll to install cobalt-strike on debian architectures.

## Variables
This role has the following variables

|Variable   	|Default Value | Description   	|
|:-:	        |:-:	         |:-:             |
|open_jdk_version| openjdk-14-jdk | The open JDK version to be installed on the system (Cobalt-Strike needs a JDK)
|cs_download_location | /home/ec2-user/ | The directory where Cobalt-Strike will be located|
|cs_license | N.A | Your Cobalt-Strike License|

## Testing
you can test out the role using the example playbook **Don't forget to add your license to the example play** (will install Cobalt-Strike on localhost in /tmp)

```
ansible-playbook example_playbook.yml 
```
