# changeSecuritySaltCakePHP3

Creating a command in Shell to create a SECURITY_SALT or modifying them with the default hash256 of CakePHP3

Follow these steps:

* In the terminal you enter your project "cd [name_proyecto]"
* In the terminal you execute: bin/cake bake shell Salt
* Open the generated file in the folder src/Shell
* Once inside the file copies the contents of the file of this repository
* That is all.

In the terminal now you have these two options

* bin/cake salt ( What it does is to generate a salt in case it does not exist )
* bin/cake salt reset ( What it does is replace the salt it has with a new one )

I hope it is of great help to you that like me in CakePHP we did not find something like Laravel does "php artisan key:generate".