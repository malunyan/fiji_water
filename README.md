<?php

if (isset($_POST['signin'])) {
  $username = $_POST['username'];
  $password = $_POST['password'];
  echo $username . "<br>";
  echo $password . "<br>";
}

?>
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF=8">
  <title>新規登録画面</title>
</head>
<body>

<h1>新規登録画面</h1>
<form action="" method="POST">
  ユーザ名<input type="text" name="username" value=""><br>
  パスワード<input type="password" name="password" value=""><br>
  <input type="submit" name="signin" value="新規登録">
</form>

</body>
</html>
