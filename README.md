此模板修改自 JO2EY 的 surge2clash 模板（https://raw.githubusercontent.com/JO2EY/Rules/master/Clash/Surge2Clash.conf）
感谢 JO2EY！


进行了以下部分的修改：
- 将短链接展开
- 添加 Twitch、Telegram、Final 的策略组
- 精简了 Media（Streaming）策略组，具体的支持列表请自行查看：https://git.io/fjOXK
- Teamviewer、LAN 默认不走代理
- BBC 固定使用 Britain（英国）节点
- 区域 Auto 规则的一些修改
- Taiwan 节点默认使用中国国旗


部分规则引用自 ConnersHua 及 LHIE1，感谢！


本规则适用于 DlerCloud 家的 Silver 用户
JO2EY 的规则适用于尊贵的 Gold 用户


食用方法：
1. 请开动自己的脑筋！
1. 请自行将下文中的全部 QWERTYUIOP 替换成自己的托管 token
2. 因为 API 需要一个 URL 参数来获取配置文件，因此一种方法是将替换后的内容存放在 Gist 上（请设为私密），获取 Raw 链接即可
3. 例如，获取的远程链接为：https://git.io/fjOX5 ，可使用 0KABE 大佬的 ConfConvertor 脚本进行转换（项目地址:https://git.io/fjqRX）
4. clash 配置托管地址为：https://api.OKAB3.com/clash?url=https://git.io/fjOX5
