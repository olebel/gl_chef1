### Links
* https://www.vagrantup.com/
* https://learn.chef.io/#/
* https://docs.chef.io/berkshelf.html

### Downloads
* https://www.virtualbox.org/wiki/Download_Old_Builds_5_1
* https://downloads.chef.io/
* https://www.vagrantup.com/downloads.html


---
### For GlobalLogick lab PCs:

* __VirtualBox__:
>* Download libqt:
```wget -O libqt.deb http://cz.archive.ubuntu.com/ubuntu/pool/universe/q/qtx11extras-opensource-src/libqt5x11extras5_5.5.1-3build1_amd64.deb```

>* Download virtualbox 5.1.30:
``` wget -O virtualbox.deb https://download.virtualbox.org/virtualbox/5.1.38/virtualbox-5.1_5.1.38-122592~Ubuntu~xenial_amd64.deb ```

>* Install:
``` sudo apt install ./libqt.deb ./virtualbox.deb ```

* __Chef Development Kit__:
>* Download Chef:
``` wget -O chef.deb https://packages.chef.io/files/stable/chefdk/1.4.3/ubuntu/16.04/chefdk_1.4.3-1_amd64.deb ```

>* Install:
``` sudo apt install ./chef.deb ```

* __Vagrant__:
>* Download Vagrant:
``` wget -O vagrant.deb https://releases.hashicorp.com/vagrant/1.9.7/vagrant_1.9.7_x86_64.deb```

>* Install:
``` sudo apt install ./vagrant.deb ```

* __Remove pkgs__:
``` rm vagrant.deb chef.deb virtualbox.deb libqt.deb vagrant.deb ```
