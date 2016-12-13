Role Name
=========

An Ansible role to install gradle


Dependencies
------------
Oracle Java

Role Variables
--------------
- `gradle_cache_dir`: (default: `/tmp/ansible-cache`) Cache folder for downloads
- `gradle_version`: (default: `2.10`) Gradle version to download
- `gradle_zipfile`: (default: `gradle-{{gradle_version}}-all.zip`) - Zip file to download
- `gradle_folder`:  (default: `gradle-{{gradle_version}}`) - Folder to extract the to


Example Playbook
----------------
    - hosts: servers
      roles:
         - { role: munkyjunky.gradle }


License
-------
MIT
