# bastion userdata

#!/bin/bash
yum install -y  https://dl.fedoraproject.org/pub/epel/epel-release-latest-8.noarch.rpm
yum install -y yum-utils http://rpms.remirepo.net/enterprise/remi-release-8.rpm
yum install -y mysql
yum install -y git
yum install -y ansible