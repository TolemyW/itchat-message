2019/04/12 16:50:46:**蒙东明** : 今天 铲掉 VM ，多分配了/分区，同时hostname是小写，重安装 后，现在TOS 了，
*************************************************************************************
2019/04/12 16:50:56:**蒙东明** : ![图片如下](https://github.com/CorkiZhang/itchat-message/blob/master/sla2-860长亮科技manager安装问题/ATTACHMENT/1555059042.8868124.png)
*******************************************************************************
2019/04/12 16:53:31:**Dong Ming** : [root@odcpocser02 ~]# cat /var/log/transwarp-manager/agent/operations/tos-TOS_MASTER-odcpocser02-Start-2019-04-12_16*
Fri Apr 12 16:33:07 CST 2019 [Agent] execute command: systemctl daemon-reload
systemctl enable kubelet
systemctl start kubelet
sleep 2
systemctl status kubelet
● kubelet.service - kubelet: The Kubernetes Node Agent
   Loaded: loaded (/etc/systemd/system/kubelet.service; enabled; vendor preset: disabled)
  Drop-In: /etc/systemd/system/kubelet.service.d
           └─10-kubeadm.conf
   Active: activating (auto-restart) (Result: exit-code) since Fri 2019-04-12 16:33:09 CST; 162ms ago
     Docs: http://kubernetes.io/docs/
  Process: 29611 ExecStart=/usr/bin/kubelet $KUBELET_KUBECONFIG_ARGS $KUBELET_SYSTEM_PODS_ARGS $KUBELET_NETWORK_ARGS $KUBELET_DNS_ARGS $KUBELET_AUTHZ_ARGS $KUBELET_CADVISOR_ARGS $KUBELET_CGROUP_ARGS $KUBELET_CERTIFICATE_ARGS $KUBELET_EXTRA_ARGS (code=exited, status=255)
 Main PID: 29611 (code=exited, status=255)

Apr 12 16:33:09 odcpocser02 systemd[1]: Unit kubelet.service entered failed state.
Apr 12 16:33:09 odcpocser02 systemd[1]: kubelet.service failed.
Created symlink from /etc/systemd/system/multi-user.target.wants/kubelet.service to /etc/systemd/system/kubelet.service.
Fri Apr 12 16:33:09 CST 2019 [Agent] exit status: 3
Fri Apr 12 16:33:09 CST 2019 [Agent] The command is necessary but failed!
[root@odcpocser02 ~]# ll /etc/systemd/system/multi-user.target.wants/kubelet.service
lrwxrwxrwx 1 root root 35 Apr 12 16:33 /etc/systemd/system/multi-user.target.wants/kubelet.service -> /etc/systemd/system/kubelet.service
[root@odcpocser02 ~]#
*************************************************************************************
2019/04/12 16:54:29:**Dong Ming** : ![图片如下](https://github.com/CorkiZhang/itchat-message/blob/master/sla2-860长亮科技manager安装问题/ATTACHMENT/1555059255.8212137.png)
*******************************************************************************
