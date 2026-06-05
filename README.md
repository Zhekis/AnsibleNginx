# AnsibleNginx
Автоматическое развертывание Nginx с помощью Ansible на WSL.

### Описание
Плейбук для установки nginx на целевые хосты и загрузки на них индексного файла с текстом "Hello from Ansible"

### Запуск плейбука
ansible-playbook playbook.yml -i inventory.ini
