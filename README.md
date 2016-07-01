Vagrant Box trusty64
=========

A standard Ubuntu 14.04 LTS 64 bit box. It has pre-installed nginx, php7.0 and some other php extentions 

  - PHP 7.0
  - Apache 2
  - MySQL (By running provision)
  - curl
  - GIT
  - Composer
  

How Download and Install Vagrant
-----------
* [Download] - download vagrant from their officail website
* [Installation] - follow thier official  installation tutorial
* [Tutorial] - A nice tutorial on setting up dev environment

How to use it
--------------
To intigrate to your project, run following command

```sh
bash < <(curl -s -S -L https://raw.githubusercontent.com/eftakhairul/trusty64/master/installer)
```

With provision

```sh
vagrant provision
```

Add IP to your local /etc/host once in developing life circle
```sh
echo "192.168.33.10   local.backend" >> /etc/hosts
```


Access vagrant
```sh
vagrant ssh
```

Password
--------------

```sh
Username : vagrant
Password : vagrant
```

Version
----
1.0

Donate to this project
----
[Donate] - Donate through paypal or credit card

License
----
Apache LICENSE-2.0




[Download]:http://www.vagrantup.com/downloads.html
[Installation]:http://docs.vagrantup.com/v2/installation/index.html
[Tutorial]:http://eftakhairul.com/setting-up-development-enviroment-with-vagrant/

[Donate]:https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=eftakhairul%40gmail%2ecom&lc=CA&item_name=Eftakhairul%20world&item_number=web_product&currency_code=CAD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted
