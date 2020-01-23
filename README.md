this is a simple library for your codeigniter project

copy this files into application folder
add the following into config/autoload.php

$autoload['libraries'] = array('session','database');
$autoload['helper'] = array('url');

Open config/facebook.php and change it by adding your credentials 

$config['facebook_app_id']                = 'Insert_your_Facebook_App_ID';
$config['facebook_app_secret']            = 'Insert_your_Facebook_App_Secret';

