# dev-env-cpp
Tools and environment definitions for local EOEPCA service development activities for C++

## Usage
1. Download and install [VirtualBox](https://www.virtualbox.org/) 

2. Download and install the appropriate [Vagrant package for your OS](https://www.vagrantup.com/downloads.html).

3. Download EOEPCA development environment template for c++ 
    
    wget https://github.com/EOEPCA/dev-env-cpp/archive/develop.zip'

4. To build and instantiate the EOEPCA development environment run the following command:

    vagrant up --provision

5. To access the development environment via ssh

    vagrant ssh

6. To access the development environment with CentOs GUI open VirtualBox select the running the dev-env-cpp VM then click on the Show button.

