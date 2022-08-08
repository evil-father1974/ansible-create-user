# ansible-create-user
👋 Hi, I’m @evil-father1974
playbook.yml - Add the user 'sotan' with a specific uid and a primary group of 'admin'


### запуска ансибла 

``` /home/evil# ansible-playbook playbook.yml```


### вывод ансибла 

``` [WARNING]: provided hosts list is empty, only localhost is available. Note that the implicit localhost does not match 'all'

PLAY [Demo] ************************************************************************************************************************************

TASK [Gathering Facts] *************************************************************************************************************************
ok: [localhost]

TASK [Add user 'sotan'] ************************************************************************************************************************
ok: [localhost]

PLAY RECAP *************************************************************************************************************************************
localhost                  : ok=2    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0  ```
