# NATOK · ![GitHub Repo stars](https://img.shields.io/github/stars/natokay/go-natok-server) ![GitHub Repo stars](https://img.shields.io/github/stars/natokay/go-natok-cli)

<div align="center">
  <!-- Snake Code Contribution Map 贪吃蛇代码贡献图 -->
  <img src="https://cdn.jsdelivr.net/gh/sun0225SUN/sun0225SUN/profile-snake-contrib/github-contribution-grid-snake-dark.svg" />
<p/>
</div>


* 🌱 natok是一个将局域网内个人服务代理到公网可访问的内网穿透工具。基于tcp协议、支持udp协议, 支持任何tcp上层协议（列如: http、https、ssh、telnet、data base、remote desktop....）。
* 🤔 目前市面上提供类似服务的有: 花生壳、natapp、ngrok等等。当然, 这些工具都很优秀; 但是免费提供的服务都很有限, 想要有比较好的体验都需要支付一定的套餐费用, 由于数据包会流经第三方, 因此总归有些不太友好。
* 🚀 natok-server与natok-cli都基于GO语言开发, 先天并发支持; 运行时的内存开销也很低, 一般在二十M左右 **。**
* 🔥 安全升级：可自定义访问白名单，热更新可随时修改；自定义监听范围，global=可全局访问，local=仅本地访问（`127.0.0.1:port`通过nginx等代理域名转发）。


**👋 服务端与客户端下载**


| 服务                     |支持系统| 下载地址                                               |
| ------------------------|----- | ------------------------------------------------------ |
| natok-cli | linux/windows | [download](https://github.com/natokay/go-natok-cli/releases) |
| natok-server| linux/windows | [download](https://github.com/natokay/go-natok-server/releases) |



<!--
**natokay/natokay** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

### NATOK平台界面预览

登录页面
![image-20250303220714-r1kbi0b](https://github.com/user-attachments/assets/49e963e1-0062-4e2b-89d2-8309472e9fe7)

统计概览
![image-20250303220743-etmceyf](https://github.com/user-attachments/assets/cba87be9-e6d0-4ab2-8fbe-222397c4a06a)

代理管理
![image-20250303220953-vz1hjpb](https://github.com/user-attachments/assets/bc42a243-c1fc-4fa3-adfd-23c6175f9166)
![image-20250303221323-a0q00lk](https://github.com/user-attachments/assets/ff38b0a3-d578-4342-a68c-98e4775c5021)

端口映射
![image-20250303221053-j7b3tsy](https://github.com/user-attachments/assets/4f65aea5-5f97-42dc-94a0-0e3af73d4bef)
![image-20250303221456-pkfl4wt](https://github.com/user-attachments/assets/3692fce0-6104-47ee-b2b5-fcafd78366ec)

标签名单
![image-20250303221123-zl9f76j](https://github.com/user-attachments/assets/02262934-f260-43da-8435-45fdd35c1793)
![image-20250303221545-9n2vwqs](https://github.com/user-attachments/assets/14ddd49a-fdcc-49d0-ae8e-071a9962ac4c)


