# Yii2 Migratraion Generator

## Installation

Preferred way to install is through composer
```
composer require rocketfirm/yii2-migration-generator
```

## Usage

Add following line of code to your ```main-local.php``` config file
```
$config['modules']['gii']['generators']['sanzhikee-gii-migration'] = 'rocketfirm\generator\migration\Generator';
```
