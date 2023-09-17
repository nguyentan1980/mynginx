Hi, I'm a DevOps engineer. I created this repository to keep my K8s recipes. 

But you're free to use and contribute all Helm charts here.

Usage
Some common Helm commands for you

# Add repo before using
$ helm repo add nguyentan1980 https://raw.githubusercontent.com/nguyentan1980/mynginx/master/
"nguyentan1980" has been added to your repositories

# Search for charts, or list all the charts by repo's name
$ helm search repo nguyentan1980
NAME                    CHART VERSION   APP VERSION     DESCRIPTION
nguyentan1980/mynginx   0.1.0           1.16.0          A Helm chart for Kubernetes

# Get configurations (values file)
$ helm show values nguyentan1980/mynginx > myvalues.yaml

# Install chart with your configurations
$ helm install mynginx-demo nguyentan1980/mynginx
