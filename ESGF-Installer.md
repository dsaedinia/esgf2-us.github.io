# ESGF Installer

## New and returning installations

Regardless of whether you have installed and administered an ESGF node previously, please read the following document on ESGF policies, as this should influence what type on installation you should do:

http://esgf.llnl.gov/media/pdf/ESGF-Policies-and-Guidelines-V1.0.pdf

## ESGF Docker Installation

ESGF has adopted the use of containers for new node installations and upgrades, please see:

https://github.com/esgf/esgf-docker

Specific instructions for deployment methods are linked at the bottom of the README.

## Installation
To setup a 'devel' install 
 
    cd /usr/local/bin
    wget -O esg-bootstrap http://distrib-coffee.ipsl.jussieu.fr/pub/esgf/dist/devel/esgf-installer/2.5/esg-bootstrap --no-check-certificate  
    chmod 555 esg-bootstrap  
    ./esg-bootstrap --devel   
 
To setup a 'master' install  
 
    wget -O esg-bootstrap http://distrib-coffee.ipsl.jussieu.fr/pub/esgf/dist/esgf-installer/2.5/esg-bootstrap --no-check-certificate  
    chmod 555 esg-bootstrap  
    ./esg-bootstrap
    
More detailed installation instructions can be found on the [wiki](https://github.com/ESGF/esgf-installer/wiki)

## Support

Please [open an issue](https://github.com/ESGF/esgf-installer/issues/new) for support.
Please follow the [Issue Tracking Guidelines](https://github.com/ESGF/esgf-installer/wiki/ESGF-Installer-Issue-Tracking-Guidelines) when opening a new issue.


## Contributing

Please contribute using [Github Flow](https://guides.github.com/introduction/flow/). Create a branch, add commits, and [open a pull request](https://github.com/ESGF/esgf-installer/compare).
