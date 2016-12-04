if after the install kube is not connecting to the api server copy the following folders from the master :

/etc/kubernetes/
azure.json,certs
to the same location on the node.

after that restart kube 
systemctl restat kube


