<h1 align="center">Memgin</h1>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?lines=%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%20%C2%B7%20%E8%BF%90%E7%AD%B9%E4%BC%98%E5%8C%96%20%C2%B7%20%E5%9C%B0%E7%90%86%E4%BF%A1%E6%81%AF%3B%E6%8A%8A%E8%AF%B4%E4%B8%8D%E6%B8%85%E7%9A%84%E9%97%AE%E9%A2%98%E6%8B%86%E6%88%90%E8%83%BD%E7%AE%97%E7%9A%84%E6%A0%B7%E5%AD%90&center=true&vCenter=true&width=560&height=44&size=20&pause=1400&repeat=false&color=9198A1">
    <img src="https://readme-typing-svg.demolab.com?lines=%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%20%C2%B7%20%E8%BF%90%E7%AD%B9%E4%BC%98%E5%8C%96%20%C2%B7%20%E5%9C%B0%E7%90%86%E4%BF%A1%E6%81%AF%3B%E6%8A%8A%E8%AF%B4%E4%B8%8D%E6%B8%85%E7%9A%84%E9%97%AE%E9%A2%98%E6%8B%86%E6%88%90%E8%83%BD%E7%AE%97%E7%9A%84%E6%A0%B7%E5%AD%90&center=true&vCenter=true&width=560&height=44&size=20&pause=1400&repeat=false&color=57606A" alt="数据分析 · 运筹优化 · 地理信息">
  </picture>
</p>

<p align="center">
  <sub>B.Sc. Data Science &amp; Big Data · Class of 2028 · Qingyuan / Shenzhen, CN · CDA Level I Analyst</sub>
</p>

<p align="center">
  <a href="#now--现在">Now</a> ·
  <a href="#selected-work--精选项目">Selected Work</a> ·
  <a href="#science--研究">Science</a> ·
  <a href="#stack--技术栈">Stack</a> ·
  <a href="#honors--荣誉">Honors</a> ·
  <a href="AWARDS.md">Awards</a> ·
  <a href="mailto:lanmangin@outlook.com">Email</a>
</p>

---

我在广东金融学院读数据科学与大数据技术，方向偏运筹优化和统计建模。课上学的是方法，课下我更喜欢把方法做成能跑起来的东西，所以做了地图、小程序，也做过选址和排班。

动手之前我通常会先问一句，这个结果最后要影响哪个决定。如果算完没有人会因此改变做法，那这个分析大概可以先放一放。

### Now / 现在

**清远社区共享地图** · `Cloudflare Pages + D1 + R2` `高德` `智谱`<br>
给清远做的一张社区地图，用户看到的是别人愿意分享的地点。底层是一套标签和权限结构，AI 向导 Lumina 按地点之间的关系给出路线，应急图层单独留了一个入口。Web、HarmonyOS 客户端和后台共用同一套数据模型，改一处三端都生效。<br>
[Memgin/qingyuan-community-map](https://github.com/Memgin/qingyuan-community-map) · [qymap.pages.dev](https://qymap.pages.dev/)

**悉数 Xishu** · `微信小程序` `云开发` `Node.js`<br>
个人的资产记录与分析工具，管多币种账户、汇率、风险敞口和目标进度。AI 的部分只负责一件事，从流水里看出趋势和异常。<br>
[Memgin/xishu](https://github.com/Memgin/xishu)

### Selected Work / 精选项目

**电动汽车充电站运营决策** · `运筹优化` `时空预测` `闭环协同`<br>
先预测各区域车辆到达的时间和空间分布，再把运营中积累的数据回灌到排程里，选址和调度放进同一个目标函数求解。分开做的时候，两边的结论经常互相打架。<br>
**2026 中国运筹学会运筹竞赛（本科组）· 国家一等奖 金奖** · *代码未公开（赛题约束）*

**长江渔业生态演化与人类活动效应评估** · `复杂网络` `动力学建模` `情景模拟`<br>
用多营养级食物网搭动力学模型，把捕捞强度和航运干扰作为可调的输入，看不同情景下各营养级的种群长期会稳定在什么水平。<br>
**广州高校数学建模竞赛 · 三等奖**

**正大杯市场调研（第 15 / 16 届）** · `问卷设计` `统计检验`<br>
十五届和十六届都参加了，负责团队的数据分析，从清洗、交叉分析一直做到把结果讲清楚。

**霓窗仔 · 岭南文化 IP 文创设计** · `文化转译` `视觉系统`<br>
从骑楼和满洲窗里提取图形元素，整理成一套可以反复使用的视觉语言，再做延展到实物上。

### Science / 研究

**Beyond Model Complexity: The Incremental Value of Volatility Features in Multi-Horizon Stock Risk Prediction**<br>
M. Lin · J. Bi · J. Hu · K. Yan, *School of Data Science and Artificial Intelligence, Guangdong University of Finance*<br>
文章讨论的是一个被默认很久的假设，即模型越复杂，风险预测就越准。我们在多个预测期限上做对照，把波动率特征带来的增益、加深加宽模型带来的增益分开度量，看提升究竟来自哪一边。<br>
*2026.12 待刊，预印本与 DOI 之后补上*

### Stack / 技术栈

<table align="center">
  <tr>
    <td align="center" width="380"><sub><b>数据 · Data</b></sub></td>
    <td align="center" width="380"><sub><b>构建 · Build</b></sub></td>
    <td align="center" width="380"><sub><b>平台 · Platform</b></sub></td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=py,sklearn,mysql,d3&theme=dark" height="40" alt="Python, scikit-learn, MySQL, D3"></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=js,nodejs,html,css&theme=dark" height="40" alt="JavaScript, Node.js, HTML, CSS"></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=cloudflare,workers,vercel,github&theme=dark" height="40" alt="Cloudflare, Workers, Vercel, GitHub"></td>
  </tr>
</table>

<p align="center">
  <img src="https://skillicons.dev/icons?i=vscode,git,latex,markdown,bash,powershell,npm&theme=dark" height="36" alt="VS Code, Git, LaTeX, Markdown, Bash, terminal, npm">
</p>

<p align="center">
  <sub>运筹优化 · 时空预测 · 网络动力学 · 情景模拟</sub>
</p>

### Experience / 经历

<table align="center">
  <tr>
    <td valign="top" width="134"><img src="https://img.shields.io/badge/2024.09--%E8%87%B3%E4%BB%8A-cf222e?style=flat-square" alt="2024.09 – 至今" height="20"></td>
    <td valign="top" width="800">
      <b>助理班主任 · 班级学习委员</b> @ <a href="https://www.gduf.edu.cn"><b>广东金融学院</b></a>
      <blockquote><i>第一次完整带一个班，从开学前的筹备做到学期中段。</i></blockquote>
      <ul>
        <li>组织破冰活动、班委搭建与学业规划，累计协助解决二十余件具体问题</li>
        <li>牵头组建学习小组，组内零挂科，成员绩点均在 3.0 以上</li>
        <li>综合测评 1/52、绩点 3.63；获校级「十佳助班」「优秀学生骨干」</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td valign="top" width="134"><img src="https://img.shields.io/badge/2026.01-0969da?style=flat-square" alt="2026.01" height="20"></td>
    <td valign="top" width="800">
      <b>文书</b> @ <b>清远市职教城党群服务中心</b>
      <blockquote><i>在基层单位写材料，写的东西当天就要发出去。</i></blockquote>
      <ul>
        <li>起草活动简报、工作总结、会议纪要，兼部分宣传材料编撰</li>
        <li>熟悉基层行政流程与公文规范，把话写清楚比写漂亮更要紧</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td valign="top" width="134"><img src="https://img.shields.io/badge/2025.06--07-8250df?style=flat-square" alt="2025.06 – 07" height="20"></td>
    <td valign="top" width="800">
      <b>深圳区域访问员</b> @ <b>中国社会科学院 · 中国社会状况综合调查（CSS）</b>
      <blockquote><i>入户之后才明白样本是怎么偏的。</i></blockquote>
      <ul>
        <li>入户访谈与数据采集，完成 82 份有效问卷的发放与核验</li>
        <li>在入户现场理解抽样偏差与数据核验的实际约束，而不是纸面上的定义</li>
      </ul>
    </td>
  </tr>
</table>

### Honors / 荣誉

> 🏅 **[View Awards →](AWARDS.md)**　完整奖项、证书和服务记录

- **2026**　中国运筹学会运筹竞赛（本科组）国家一等奖 · 金奖
- **2026**　第二十一届海峡两岸暨港澳地区大学生计算创新作品赛 · 三等奖
- **2026**　全国大学生数据分析科普竞赛 · 一等奖
- **2026**　校级「金融之星」· 「优秀共青团员」· 「十佳助班」
- **2025**　校级「优秀学生骨干」· 优秀学生一等奖学金 · 职业技能奖学金
- **2025**　广州高校数学建模竞赛 · 三等奖 · 「学风建设榜样青年讲师」

<sub>已取得 CDA 数据分析师一级、CET-6、全国计算机二级、银行从业资格和中国社会科学院访问员资格。</sub>

### Elsewhere / 别处

公开的仓库只有两个，过去一年提交一百多次，大部分时间花在地图和小程序上。零散的东西我没有搬到主页上，做出来的都放在仓库里。

我在找数据分析或者运筹优化方向的实习和研究机会。如果你手上有个说不清楚但感觉能算的问题，欢迎写信给我，**[lanmangin@outlook.com](mailto:lanmangin@outlook.com)**

---

<sub>最后更新 2026.11</sub>
