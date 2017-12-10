Ambari Agent
=========

Installs and configures an Ambari Agent.

Requirements
------------


Role Variables
--------------
If you want to set the following parameters just overwrite those:

* ambari_repo_url
* ambari_agent_url_port
* ambari_agent_secured_url_port
* ambari_server_hostname

Dependencies
------------

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: hdp-ambari-agent }

License
-------

BSD

Author Information
------------------

Stefan Kupstaitis-Dunkler (stefan.dun@gmail.com)
