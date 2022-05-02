# Wordpress-Mysql-Helm
Wordpress connect with Mysql using Helm

# Firstly start the minikube 
minikube start

# Need to download & install the Helm in your System and set the environment
https://get.helm.sh/helm-v3.8.2-windows-amd64.zip

# After that use the below commands

git clone https://github.com/TinkalShakya09/Wordpress-Mysql-Helm.git

cd Wordpress-Mysql-Helm

helm install <type-release-name> Wordpress_mysql/

