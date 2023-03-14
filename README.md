- 👋 Hi, I’m @stavrosfilippidis a cloud and security engineer that worked extensively in the 
startup scene in Berlin. 

- 🌱 I’m currently learning about Data engineering & Security.

- 💞️ I’m looking to collaborate on platform & security related projects to support in achieving business critical missions.

- My public key: 

```
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQCiXT2UHq+pTQnRqGOD0Em+DirSDRVgJ2Uw3wy74NThFokMNISPtv+WeFyY1s6M7F0dPd5kksNyRUhl446lb0hcC5W43LuBE4NxSuM/VeHlnehwSw8mnoKuHeSdK/53bA+x0ZAtt2VwvSOJyMkTDA5a6gEgs8A7YmC6DPbjfXR9uydSjh0SUsDDZKZ0Hv8yz1FEnDm9oA+ZpwRAcdTLIny+aBl4ll6RuMXbwcbyUniu9eXOl9Tb3gTu2sWpzLTorAsz9Kupbha9UGPN8SrQ6p0Xx4YCZZ4P7yX+upvoKDW9A962DI58u+IMoQ9zJbOhGKkSzIv7oL9G51Gs64ib15KCzuQ4LAvj30sEmZhI18mXZjyCarybJPo1Cp4iM90zT+H9cj2XTQH92bgK5PhCB2ZGxziYJB7HONbvmtfTuwbAbgtbGOv5OOw+Vxde8gjWJgSLIU4BLjxrZB/t6575icqSTtj/LzCYmmsWU7xD/FTRJtminbpX4YasXrbvQqe65b0= stavros@fedora
```

### A bit Open Source

While working at previous companies, I identified the recurring need for  
adjacent infrastructure and tooling.  
Common use cases are Monitoring, Observability and a VPN Bastion Host.  
The following modules leverage modern open source technology and provide  
a starting point for platform engineers who need the aforementioned cases.  

The modules are built using Terraform as IaaC tool and can  
be easily customized or extended for different contexts.  
Feel free to reach out in case you discover bugs. 

  - [Observability Hub](https://github.com/stavrosfilippidis/tf_aws_observability_hub) a cluster based on Grafana and AWS EC2 that provides monitoring visualization. 
  - [Metrics Hub](https://github.com/stavrosfilippidis/tf_aws_metrics_collector) a cluster leveraging Prometheus to scrap metrics from endpoints and expose them for further usage. 
  - [Bastion Host](https://github.com/stavrosfilippidis/tf_aws_wireguard_vpn) a Virtual Private Network powered by AWS EC2 and Wireguard for lowering the attack surfaces in networks. 
  - [Terraform Remote Backend](https://github.com/stavrosfilippidis/tf_aws_s3_remote_terraform_backend) a Terraform module creating the infastructure needed for collaboration and remote state.


  
