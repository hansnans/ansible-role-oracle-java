Role Name
=========

THIS IS NOT A PPA INSTALLATION!!
This role will download oracle java server jre (tar.gz) to /opt/ folder, extract it there and set the alternatives.
You can adjust the version in the defaults/main.yml file.
The tar.gz will be downloaded from original Oracle Server. Because of Licence agreement, you can't directly download the file.For this purpose there is the header cookie.

Role Variables
--------------
build: the build number of the java version
version: the java version number (without build)
file_name: the extracted folder name. Contains Version and build number but the format is different.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: hansnans.oracle-java }

License
-------
OpenGPL

Author Information
------------------
Author of the role: me (hansnans)


Oracle site cookies found on https://ivan-site.com/2012/05/download-oracle-java-jre-jdk-using-a-script/

