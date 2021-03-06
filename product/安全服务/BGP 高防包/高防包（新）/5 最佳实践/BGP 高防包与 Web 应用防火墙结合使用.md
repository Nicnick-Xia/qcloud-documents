DDoS 高防包支持联动 Web 应用防火墙，为用户提供全方位安全防护。
- DDoS 高防包一键提供上百 Gbps DDoS 防护能力，轻松应对 DDoS 攻击，保障业务稳定运行。
- Web 应用防火墙实时防护，有效拦截 Web 攻击行为，保障用户业务的数据和信息安全。

## 部署方案
![](https://main.qcloudimg.com/raw/5cf47d62a98ffd71bfa4e349ceae5d3d.png)
## 配置过程
### 配置 Web 应用防火墙
如需快速接入 Web 应用防火墙，详情请参见 [ Web 应用防火墙快速入门](https://cloud.tencent.com/document/product/627/18635)。
### 配置 DDoS 高防包
1. 登录 [DDoS 防护管理控制台](https://console.cloud.tencent.com/dayu/overview)，前往【高防包】。
2. 选择目的高防包实例所在地域，单击目的高防包实例所在行的操作项【设置防护对象】。
![高防包实例列表](_image/高防包实例列表.png)
3. 在【管理防护对象】页面，根据实际防护需求选择【关联设备类型】与【选择资源实例】。
  - 【关联设备类型】支持云主机，负载均衡，Web应用防火墙等公有云具有公网IP的资源。
  - 【选择资源实例】允许多选，【选择资源实例】数量不得超过【可绑定IP数】。
![设置防护对象](_image/管理防护对象.png)

4. 设置完成后，单击【确定】即可。
>?若是负载均衡型 Web 应用防火墙，在绑定界面选择【关联设备类型】为【负载均衡】，设置【选择关联机器】为对应负载均衡的公网 IP 地址。
