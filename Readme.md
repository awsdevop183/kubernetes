# Deployments #
Applications do not have any dependencies with Pod names or count.


# Daemonsets #

Some applications have some requirements such as at any given time one Pod has to be run on every node. For instance to collect metrics from nodes we have to run Node Exporter Pod on every node. In this case we can use Daemonsets

# Statefullsets #

Wherever the hostname must be same at any given time and it follows an ordinal index. For instance Databases such as MongoDB or MySQL etc.

for instance pod-name: mysql-0, mysql-1 etc