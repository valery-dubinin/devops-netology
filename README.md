# devops-netology
devops-netology hw
first line


# gitignore для терраформа:

Игнорит следующие файлы или каталоги:


# Локальная папка тераформа с подпапками
**/.terraform/*

# .tfstate файлы  с состояниями машин
*.tfstate
*.tfstate.*

# Краш логи
crash.log
crash.*.log

# Переменные
*.tfvars
*.tfvars.json

# Перезаписываемые файлы
override.tf
override.tf.json
*_override.tf
*_override.tf.json

# Файлы настроек CLI
.terraformrc
terraform.r
