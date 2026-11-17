# devops_program7_code
*/ ansible-playbook -i hosts.ini setup.yml --ask-become-pass
BECOME password: 

PLAY [Basic Server Setup] **********************************************************************************************************************************************

TASK [Gathering Facts] *************************************************************************************************************************************************
[WARNING]: Platform linux on host localhost is using the discovered Python interpreter at /usr/bin/python3.10, but future installation of another Python interpreter
could change the meaning of that path. See https://docs.ansible.com/ansible-core/2.17/reference_appendices/interpreter_discovery.html for more information.
ok: [localhost]

TASK [Display server information] **************************************************************************************************************************************
ok: [localhost] => {
    "msg": "Ansible playbook is working successfully"
}

PLAY RECAP *************************************************************************************************************************************************************
localhost                  : ok=2    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0   

/*
