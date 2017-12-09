# pbs 命令
qmgr -c 'p s'  显示队列属性

qmgr -c "set queue batch max_running = 200"

pbsnodes 

qsub



#记录
/var/spool/torque

#重启
sudo service pbs_server restart
sudo service pbs_sched start
