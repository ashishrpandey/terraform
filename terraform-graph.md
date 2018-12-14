## Donwload yum repos 
    wget -O /etc/yum.repos.d/graphviz.repo http://www.graphviz.org/graphviz-fedora.repo


## Install graphviz

    yum --nogpgcheck localinstall gtkglext-devel-1.2.0-6.el5.x86_64.rpm
    yum --nogpgcheck localinstall gts-0.7.6-11.el5.x86_64.rpm
    yum --nogpgcheck localinstall graphviz-2.28.0-1.el5.x86_64.rpm
