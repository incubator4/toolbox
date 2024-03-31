# 个人工具箱（2024.03.26）

## 前言

fork by [yu-tools](https://github.com/pseudoyu/yu-tools)

> 注：下文所提及的所有软件服务不保证全部都是正版,但也绝不全是盗版

## 主要设备

<!-- ![yu_new_desk_setup](https://image.pseudoyu.com/images/yu_new_desk_setup.jpg) -->

### :computer: 电脑及配件

- **Apple MacBook Pro (14-inch, 2021) 银色，M1 Pro，32GB RAM，1T SSD**，2021 年初代的 M1 Pro,首发买到,到现在还是很能打,主力工作机.
- **戴尔 U4924DW 显示器**，49 寸超宽显示器，主要用来做多任务分屏，比较适合写作和编程
- **戴尔 U2718Q 显示器**，27 寸 4K 显示器，竖屏使用,主要用来浏览网页
- **iQunix F96 无线机械键盘**，蓝牙连接，樱桃轴，主力键盘，打字手感很好，而且有线无线两种连接方式
- **Logitech MX Master 3S 鼠标，白色**，主力鼠标，手感和侧键功能都很棒
- **Apple Magic Trackpad 2**，在用 Master 3S 之前用的,由于习惯使用中指,用久了手指容易疼
- **i9 9900K + 2080Ti + 32GB + 970 EVO Plus** ,19 年组装的旗舰 PC,到现在玩游戏一直还是很够用,没有想换的东西
- **戴尔 U3219Q**,32 寸 4K 显示器，虽然不是高刷,但是不怎么玩竞技游戏,屏幕大体验很好
- **Filco 忍者 2 代 侧刻 104 键 键盘**,17 年还在读大学的时候买的键盘,到现在位置还很好用,Cherry 红轴.
- **罗技 G502 wireless 鼠标**，主力鼠标，手感很好，而且无线，充电的时候也能用,手感和重量对我来说刚好

### :iphone: 手机及平板

- **Apple iPhone 15 钛合金蓝色，256GB**，主要手机,图个省事和全家桶
- **Apple iPhone 13 绿色，256GB**，换 15 Pro 之前的手机
- **OnePlus 6 8GB + 256GB**，上学的时候用的手机，现在作为备用机,跑一些安卓的 app 或者测试,除了 845 芯片其他都还很够用
- **Apple iPad Pro 2021 128GB**，主要用来睡前看看视频,玩玩游戏,和临时 debug 用的工具.

### :package: 存储设备

- **C2000Pro，1TB**，一块拆下来的 m2 2280 固态硬盘,装了个 type-c 的硬盘盒
- **seagate 移动硬盘 512GB**，用来备份重要数据的硬盘

### 🎮 休闲娱乐

- **Nintendo Switch 日版**，主要玩一些 JRPG,八方旅人 异度之刃 之类的系列
- **Steam Deck 512G 港版**，今年过年买的,躺下的时候玩玩很有意思,解决了不用坐在电脑玩 steam 游戏的问题
- **Nintendo Switch Pro 手柄，异度之刃 2 配色**，体验感比自带的 Joy-Con 好多了
- **PlayStation 4&5 港版**, 主要玩一些独占的游戏,比如地平线,女神异闻录 5 ,最终幻想系列等(虽然已经不是独占了)
- **Xbox Series X 日版**，其实是凑数买的,只是为了凑齐御三家,结果发现完全没什么用(但是造型是最喜欢的)

## 软件工具

### 🛠 系统拓展

- **CleanMyMac X**，电脑管家，主要用来清理缓存和软件卸载
- **Raycast**，另一款强大的快捷启动工具，主要提供了一些多应用拓展支持，与 Alfred 4 配合使用
- **Bartender 4**，菜单栏管理工具，主要隐藏一些软件服务菜单栏图标
- **iStat Menus**，系统状态显示，主要显示 CPU、内存和网络等状态
- **Logi Options+**，罗技配置工具，配置鼠标功能按键用的，不过基本上用的默认值

### 📁 文件管理

- **iCloud**，200GB 空间，主要用于照片备份与软件数据同步
- **自建 NAS**, 8 \* 10TB 硬盘, 采用 ZFS raidz2, 用来存储一些媒体文件,和一些备份数据

### 🔐 安全工具

- **Enpass**，密码管理工具，免费使用,多端同步有限额,所以开了会员.大部分密码和 OTP 还有银行卡都存在这儿.好处是 Backend 完全可以自托管,支持主流 iCloud/OneDrive/Google Drive/Dropbox 等,也支持 WebDAV,国内环境我使用的坚果云免费的配额,适合对托管有疑虑的用户

### 🌏 网络工具

> TODO: 网络拓朴简单介绍的链接

- **Asus RAX-57**, WIFI6 路由器,主要负责家庭网络,支持 AiMesh,所以可以扩展网络
- **iKuai Router OS**, 主路由,主要负责管理 wan 口拨号和 DHCP,以及主 DNS 服务, DDNS 配置公网 IP,支持 alicloud/cloudflare 等. 最近支持 DoH DNS,所以直接用了
- **Openwrt**,旁路由,主要负责装一些插件
  - **Shadowsocks server**, 用来访问内网用的,在路由器上跑一个 ss server,可以在 Clash 里用策略分流访问家庭内网
  - **WireGuard**, 用来访问内网和构建多地内网连接互通
  - **OpenClash**, 用来管理 Clash 配置,主要是访问国内外网站的策略分流
- **ClashX**，网络代理工具,有一些付费节点和自建,以及上面说到的内网访问用的
- **Vivaldi**，最近刚更换为 Arc，使用体验很好，Chrome 迁移没什么成本

  - **MetaMask**，钱包插件
  - **Enpass**，自动填充密码
  - **RSSHub Radar**，检测当前页面 RSSHub 链接
  - **ModHeader**，修改请求头,现在可以在网页上 debug 查看请求和内存使用状态了,很不错的小工具
  - **Tempmonkey**, 一个油猴脚本管理插件,主要用来安装优化的脚本,和一些简单屏蔽广告用的脚本
  - **Vimium**, VIM 风格的网页快捷键插件,主要用来快速翻页和跳转
  - **IE Tab**, 用来打开一些 IE 内核的网页,比如一些银行网站
  - **Save to Notion**, 方便把一些文档博客同步到 Notion

- **Safari**，主要用来解决一些 Chormium 内核打不开的备用方案,还有一些临时的清除 cache 的解决方案

### 🧰 实用工具

- **Free Download Manager**，下载工具，主要用来下载一些大文件，支持断点续传
- **Rime 鼠须管**，定制化输入法，体验很好且数据本地保存，安全稳定
- **Time Machine**，备份工具，主要给 Mac Studio 作实时备份用
- **brew**，Homebrew 安装工具，基本上开发有关的都用 brew 装了，方便管理升级
- **TestFlight**，尝鲜一些测试版软件用
- **Rufus**, 用来制作启动盘,主要是用来装 windows 的,虽然现在很少用
- **Etcher**, 更通用的制作启动盘的工具,主要装 Linux 用的
- **Playcover**, 一个可以在 M 系列芯片的 MacOS 上运行 ipad 应用的工具

### 👨🏻‍💻 开发工具

- 编辑器

  - **JetBrains GoLand**，主力工作 Go 开发 IDE
    - **GitHub Copilot**，代码 AI 补全
    - **WakaTime**，用来记录编码项目、语言和所用时间
    - **Kubernetes**, 自动补全 kubernetes yaml 模板,并且能生成 CRD 相关提示,对 helm 和 kustomize 也非常友好
    - **Terraform** HashiCorp Terraform 和 Hcl 的补全插件,主要用于基建部署
  - **VS Code**，代码编辑工具，辅助开发

    - **GitHub Copilot**，代码 AI 补全
    - **GitLens**，增加 Git 提交状态提示及拓展其他功能
    - **rust-analyzer**，实时编译和分析 Rust 代码，提示代码中的错误，并对类型进行标注
    - **better toml**，语法高亮，并展示 toml 文件中的错误
    - **WakaTime**，用来记录编码项目、语言和所用时间

  - **Fleet**，轻量工具,但是没有插件不是很好用

- 终端
  - **Warp**，主力终端工具，提示很好, ssh 连接之后还有一部分功能
  - **NeoVim**，使用 [kickstart](https://github.com/incubator4/kickstart.nvim) 配置
- 服务器管理
  - **ssh**，配合 Warp 和 iTerm2 的 Profile 来连接服务器用
- 数据库管理
  - **TablePlus**，主力数据库管理工具，可以连 MySQL 和 PostgreSQL，支持多种数据库，界面好看，比较方便
  - **JetBrains DataGrip**，主要通过 Groovy 脚本来自动导出数据库的 Markdown 文件，很方便写文档
- 接口调试
  - **Postman**，接口调试工具,最好的功能是直接能生成一个代码的实例
  - **curl**，命令行工具，即使是一个非常简单的工具,但是用的最多
- 容器
  - **Colima**，一个容器工具，以命令行的形式来管理容器，方便且占用资源少,优点是可以启动 M1 原生的 lima 虚拟机支持,不用开启 rosseta
  - **Docker Desktop**，~~虽然占资源很高，但是确实方便。原本弃用了，但是由于使用项目使用 docker 的 Buildx 特性还是恢复使用了~~,Colima 替代了
- Kubernetes
  - **Lens**，Kubernetes 管理工具，可以管理多个集群，查看资源使用情况，查看日志等,非常好用的 GUI 工具
  - **Kubectx**，Kubernetes 上下文管理工具，可以快速切换上下文
  - **kubecm**，Kubernetes 配置管理工具，可以快速切换配置文件
  - **kind**，Kubernetes in Docker，用来快速搭建本地 Kubernetes 集群,多用于 helm 测试
  - **ArgoCD**，Kubernetes 部署工具，可以通过 GitOps 的方式来管理应用,无论是自己用还是公司多个项目管理都很好用
  - **Traefik**，Kubernetes Ingress 控制器，可以通过 CRD 的方式来管理 Ingress,支持 Let's Encrypt 自动证书申请
  - **Kustomize**，Kubernetes 配置管理工具，可以通过 overlay 的方式来管理配置文件
  - **Helm**，Kubernetes 包管理工具，可以通过 Chart 来管理应用

### 📮 邮件管理

- **Mail**，Apple 自带邮件客户端，回归原生了

### 📨 信息管理

- 域名及个人网站
  - **GitHub Pages**，配合 GitHub Action 实现自动部署
  - **Cloudflare**，采用 terraform 来管理,主要用来管理域名解析和 CDN
  - **阿里云**，主要用来管理~~域名~~和服务器

### 💬 通讯社交

- **微信&QQ**，腾讯的国民社交软件,主要用来和家人朋友聊天
- ~~**钉钉&飞书**，工作沟通,卸载了~~，
- **Slack**，最开始因为 Github 上很多社区用的是这个，后来工作 IM 也是用的这个

### 🎸 影音娱乐

- **IINA**，主要是用来当播放器顺遂
- **Infuse**，视频播放及媒体管理工具，全平台可用且支持格式很多，配合 Plex 这些媒体服务器可以建立自己本地的动漫、电影和剧集库
- **Plex Media Server**，流媒体管理服务器，可以指定本地目录自动获取元数据进行媒体库管理
- **Auto bangumi**,订阅动漫更新用的,可以订阅番剧,并且可以自动更新到 Plex
- **sonarr**,自动下载管理剧集,并且可以自动更新到 Plex
- **jackett**, 元数据 indexer,提供给 sonarr
- **Apple Music**，主要听歌软件，比起网易云 QQ 音乐等,一些专辑和 OST 非常全,订阅价格不是很贵

### 🚗 载具相关

- **Kawasaki ZX-4R**,2023 年新车,主要用来激情驾驶,四缸 400cc,动力充沛,操控性好,外观也很好看,是我喜欢的风格
- **Yamaha MT-03**,街车,双缸 322cc,坐姿很舒服,打算用来练习金卡纳,因为比较轻,操控性好,也不会太快,适合练习
- **大疆 Action 3**,主要用来记录骑行的视频,虽然很多都没发,有的时候说走就走的骑行都会没带上
- **大疆 Mini 2**,无人机,主要用来拍摄一些风景,虽然也没怎么用,但是确实很方便
