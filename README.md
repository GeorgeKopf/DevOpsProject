# DevOpsProject


I launced two AWS servers.  One running tomcat and the other as the Ansible master.
There are two Ansible playbooks:
    DevOpsSetup.yaml - Configures Tomcat's server.xml, web.xml, keystore and the index.html, which only needs to be run once.
    DevOps.yaml - Runs every minute, pulls from git and updates the index.html file if there have been changes.
