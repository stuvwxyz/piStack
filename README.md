# piStack
Notes on building my k8s cluster on rasberry PI




## Sites I used for initial research
https://viktorvan.github.io/kubernetes/kubernetes-on-raspberry-pi/#4-setup-nfs-share  
https://medium.com/@alexellisuk/walk-through-install-kubernetes-to-your-raspberry-pi-in-15-minutes-84a8492dc95a  
https://opensource.com/article/20/6/kubernetes-raspberry-pi  
https://ubuntu.com/tutorials/how-to-kubernetes-cluster-on-raspberry-pi#1-overview

### Second try
https://medium.com/@alexellisuk/walk-through-install-kubernetes-to-your-raspberry-pi-in-15-minutes-84a8492dc95a

#### Notes
 - Enable ssh  
 https://linuxize.com/post/how-to-enable-ssh-on-raspberry-pi/
 - Split memory  
 https://kalitut.com/memory-split-on-raspberry-pi/
 - Adding in cgroup to /boot/cmdline.txt  
 https://github.com/k3s-io/k3s/issues/2067


### This is the one I initially used.  Had really slow response times and commands kept timing out.  Tried tuning but kept running into timeout issues.
https://ubuntu.com/tutorials/how-to-kubernetes-cluster-on-raspberry-pi#1-overview
- Fix ubuntu for pi 4  
https://www.raspberrypi.org/forums/viewtopic.php?t=274554

Cgroups   
https://microk8s.io/docs/install-alternatives#heading--arm

## Postgres - try once pistack is working consistently
https://kb.objectrocket.com/postgresql/how-to-install-and-set-up-postgresql-on-a-raspberry-pi-part-2-1165#:~:text=to%20the%20network.-,PostgreSQL%20on%20Raspberry%20Pi,power%20the%20single%2Dboard%20device.

## Microk8s commands  
https://microk8s.io/docs/commands

https://microk8s.io/docs/install-alternatives#heading--arm