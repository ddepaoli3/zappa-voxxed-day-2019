20 minuti di zappa e non ci pensi più
=====================================

[Repository della presentazione fatta al voxxed day a Milano il 13 aprile 2019](https://vxdmilan2019.confinabox.com/talk/AUX-3692/20_minuti_di_zappa_e_non_ci_pensi_piu)

[Slide](https://www.slideshare.net/DanielDepaoli1/20-minuti-di-zappa-e-non-ci-pensi-pi)

# Installare zappa
```sh
sudo apt update
sudo apt install --yes virtualenv virtualenvwrapper python-pip
echo source "/usr/share/virtualenvwrapper/virtualenvwrapper.sh" >> /home/ubuntu/.bashrc
echo export WORKON_HOME="/home/ubuntu/virtualenv" >> /home/ubuntu/.bashrc
source ~/.bashrc
```

# Local run
```sh
AWS_PROFILE=profile python upload.py
```
