#   订阅生成器 SUB

----

## 🔑 变量说明
| 变量名 | 示例 | 备注 | 
|--------|---------|-----|
| TOKEN | `auto` | 快速订阅内置节点的订阅路径地址 /auto （支持多元素, 元素之间使用`,`或`换行`作间隔）| 
| HOST | `edgetunnel-2z2.pages.dev` | 快速订阅内置节点的伪装域名 （支持多元素, 订阅时随机获取, 元素之间使用`,`或`换行`作间隔） | 
| UUID | `b7a392e2-4ef0-4496-90bc-1c37bb234904` | 快速订阅内置VLESS节点的UUID （与变量`PASSWORD`冲突, 共存时优先使用`PASSWORD`） | 
| PASSWORD | `bpb-trojan` | 快速订阅内置Trojan节点的password （与变量`UUID`冲突, 共存时优先使用`PASSWORD`） | 
| PATH | `/?ed=2560` | 快速订阅内置节点的路径信息 | 
| ADD | `icook.tw:2053#官方优选域名` | 对应`addresses`字段 （支持多元素, 元素之间使用`,`或`换行`作间隔） | 
| ADDAPI | [https://raw.github.../addressesapi.txt](https://raw.githubusercontent.com/cmliu/WorkerVless2sub/main/addressesapi.txt) | 对应`addressesapi`字段 （支持多元素, 元素之间使用`,`或`换行`作间隔） |  
| ADDCSV | [https://raw.github.../addressescsv.csv](https://raw.githubusercontent.com/cmliu/WorkerVless2sub/main/addressescsv.csv) | 对应`addressescsv`字段 （支持多元素, 元素之间使用`,`或`换行`作间隔） | 
| DLS | `5000` |`addressescsv`测速结果满足速度下限 | 
| SUBAPI | `subapi.cmliussss.net` | clash、singbox等 订阅转换后端 | 
| SUBCONFIG | [https://raw.github.../ACL4SSR_Online_Full_MultiMode.ini](https://raw.githubusercontent.com/cmliu/ACL4SSR/main/Clash/config/ACL4SSR_Online_Full_MultiMode.ini) | clash、singbox等 订阅转换配置文件 | 
| SUBNAME | `优选订阅生成器` | 订阅生成器名称 |   
| PS | `【请勿测速】` | 节点名备注消息 | 
| COLOR | `1-10` | 不同颜色主题 |
| KV | `绑定KV空间` | KV空间键入NODE_CONFIG_LIST，存储HOST，UUID 变量|
| UUIDAPI | `生成UUID的链接` | 用API里的UUID作用到订阅里 |
| UUIDTIME | `有效时间，24小时=86400秒` | 给UUID设置有效的时间，搭配UUIDAPI，当设置此项，订阅节点第一个为到期时间提示，假的时间，真的时间必须与vless的时间相同 |
| SUB_LINKS | `订阅链接` | 直接提取订阅内节点的host和uuid |
----


