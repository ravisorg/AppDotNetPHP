AppDotNetPHP
============

Preliminary PHP library for the App.net platform

NOTE:
This library has not been tested, nor has it implemented any OAuth authentication measures. Itis a preliminary model to help guide future     App.net platform development with PHP

Example usage:
<pre>
<?php

require ('AppDotNet.php');

$app = new AppDotNet();

// Retrieve a Stream of all public Posts on App.net
$result = $app->getPublicPosts();

$code = $result['code'];
$response = $result['res'];

?>
</pre>