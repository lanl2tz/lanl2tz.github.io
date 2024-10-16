<?php
function listDirectory($dir, $prefix = '') {
    $files = scandir($dir);
    foreach ($files as $key => $value) {
        if (!in_array($value, array('.', '..'))) {
            $path = realpath($dir . DIRECTORY_SEPARATOR . $value);
            if (is_dir($path)) {
                echo $prefix . '<strong>' . $value . '</strong><br>';
                listDirectory($path, $prefix . '&nbsp;&nbsp;&nbsp;');
            } else {
                echo $prefix . $value . '<br>';
            }
        }
    }
}
?>
<!DOCTYPE html>
<html>

<head>
    <meta charset="UTF-8">
    <title>Server Directory Structure</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        strong {
            color: #2a7ae2;
        }
    </style>
</head>

<body>
    <h1>Server Directory Structure</h1>
    <?php
        // Change the parameter of listDirectory() to the directory you want to start from
        listDirectory(__DIR__);
    ?>
</body>

</html>