# setup microk8s

## installed with ubuntu

## replace microk8s kubectl by k
    - add alias k="microk8s kubectl" to ~/.bashrc
    - reload configuration with source ~/.bashrc
    - run sudo usermod -a -G microk8s alexis
    - run newgrp microk8s
