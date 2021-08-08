
      ///                                                               ///     
      ///                                                               ///     
      ///                                                               ///     
      ///      ///////////  /////// /////////// ///     /// //////////  ///     
      ///     ///      ///  ///    ///      ///  ///   /// ///////////  ///     
      ///     ///      ///  ///    ///      ///   /// ///  ///          ///     
      ////////  //////////  ///      //////////    /////     ////////   ///     

# vagrant-laravel-ansible
 (c) Chris Oguntolu 2021

## Maintainer Contact
Chris Oguntolu <c.oguntolu (at) gmail (dot) com>

## Content
A Vagrant VM with a Laravel sandbox fulled by Ansible.

For reference of the Laravel framework visit [laravel.com](https://laravel.com/)

### VM Enviroment
* ubuntu 20.04
* apache 2.4.41
* php 7.4.22
* mysql 8.0.25-15
* nodejs 12.22.4

## Usage

### Configuration
* Rename the config.yml.example file into config.yml.
* Edit the config file acording to your requirements.

### Run
```
vagrant up
```

### Test
* Default: ip: 192.168.12.34 domain: laravel.box
* MySQL db: laravel, user: laravel, password: laravel.
* Open [laravel.box](http://laravel.box) in your favourite browser.
* Open [phpmyadmin](http://laravel.box/phpmyadmin) user: laravel, password: laravel.
* Edit the .env file accordingly.
