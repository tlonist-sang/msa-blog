
clusterIP : sets up an easy to remember URL to access a pod
Node Port : makes a pod accessible from outside the cluster
Load Balancer : **proper way** makes a pod accessible from outside the cluster
External Name


among nodes, you can commnicate by meta names.
outside of node, you have to run k get services, get nodeport and access a node from there.

k describe pods [podname]


/etc/hosts edit
