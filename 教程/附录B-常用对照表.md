# 附录 B · 常用对照表

> 把全教程散落的"必背表格"集中到这里，方便打印随身记。

---

## 一、ITU / NATO 语音字母表（字母解释法）

> 对应 §2.1.2。报呼号、拼术语必用。**数字读英文（One/Two…），斜杠 `/` 读 "Portable"。**

| 字母 | 读法 | 字母 | 读法 | 字母 | 读法 |
|---|---|---|---|---|---|
| A | **Alfa** | J | **Juliett** | S | **Sierra** |
| B | **Bravo** | K | **Kilo** | T | **Tango** |
| C | **Charlie** | L | **Lima** | U | **Uniform** |
| D | **Delta** | M | **Mike** | V | **Victor** |
| E | **Echo** | N | **November** | W | **Whiskey** |
| F | **Foxtrot** | O | **Oscar** | X | **Xray** |
| G | **Golf** | P | **Papa** | Y | **Yankee** |
| H | **Hotel** | Q | **Quebec** | Z | **Zulu** |
| I | **India** | R | **Romeo** | | |

**示例**：`BH1XYZ` → Bravo Hotel One Xray Yankee Zulu；`K3TRX/VE6` → Kilo Three Tango Romeo Xray **Portable** Victor Echo Six。

---

## 二、中国业余呼号结构与分区号

### 呼号四段结构（§1.4）

```
   B          (G/H/I/D/A/B/C/E/F/K/L | J | R)        (0~9)        (1~4位)
 前缀=B            电台种类字母                       分区号        后缀
```

- **种类字母**：`G H I D A B C E F K L`=一般台；`J`=空间台；`R`=中继/信标台；`S T Y Z`=保留。
- **后缀**：1~4 位字母；`SOS`/`XXX`/`TTT`/`QOA~QUZ` 等禁用。

### 分区号对照表（0–9）

| 分区 | 省 / 自治区 / 直辖市 |
|:---:|---|
| **0** | 新疆、西藏 |
| **1** | 北京 |
| **2** | 黑龙江、吉林、辽宁 |
| **3** | 天津、内蒙古、河北、山西 |
| **4** | 上海、山东、江苏 |
| **5** | 浙江、江西、福建 |
| **6** | 安徽、河南、湖北 |
| **7** | 湖南、广东、广西、海南 |
| **8** | 四川、重庆、贵州、云南 |
| **9** | 陕西、甘肃、宁夏、青海 |

> 记忆：**1 北京（首都单列）、2 东北三省、0 新藏（最西）**；空间台分区号固定为 **1**。

---

## 三、频段（波段）命名表

> 对应 §1.7.4。给频率判断波段，中英文都要会。

| 缩写 | 英文全称 | 中文 | 波段俗称 | 频率范围 | 业余典型 |
|---|---|---|---|---|---|
| VLF | Very Low Frequency | 甚低频 | 甚长波 | 3–30 kHz | — |
| **LF** | Low Frequency | 低频 | 长波 | 30–300 kHz | 135.7 kHz |
| **MF** | Medium Frequency | 中频 | 中波 | 300 kHz–3 MHz | 160 m |
| **HF** | High Frequency | 高频 | **短波** | 3–30 MHz | 80/40/20/15/10 m |
| **VHF** | Very High Frequency | 甚高频 | 米波 | 30–300 MHz | 6 m、**2 m** |
| **UHF** | Ultra High Frequency | 特高频 | 分米波 | 300 MHz–3 GHz | **70 cm**、23 cm |
| **SHF** | Super High Frequency | 超高频 | 厘米波 | 3–30 GHz | 5.6 GHz、10 GHz |
| **EHF** | Extremely High Frequency | 极高频 | 毫米波 | 30–300 GHz | 241–250 GHz |
| THF | Tremendously High Frequency | 至高频 | 丝米波/亚毫米波 | 300 GHz–3 THz | — |

---

## 四、中国业余频段与业务地位（A 类重点 VHF/UHF）

> 对应 §1.7.2。**专用=业余独占；主要=共用但优先；次要=共用且让步。**

| 俗称 | 频率 | 波段 | 业务地位 | A 类可用 |
|---|---|---|---|:---:|
| 2200 m | 135.7–137.8 kHz | LF | 次要 | ✗ |
| 160 m | 1.8–2.0 MHz | MF | 主要 | ✗ |
| 80 m | 3.5–3.9 MHz | HF | 主要 | ✗ |
| 40 m | 7.0–7.2 MHz | HF | **专用** | ✗ |
| 30 m | 10.1–10.15 MHz | HF（WARC） | 次要 | ✗ |
| 20 m | 14.0–14.35 MHz | HF | 专用/主要 | ✗ |
| 17 m | 18.068–18.168 MHz | HF（WARC） | 主要 | ✗ |
| 15 m | 21.0–21.45 MHz | HF | **专用** | ✗ |
| 12 m | 24.89–24.99 MHz | HF（WARC） | 主要 | ✗ |
| 10 m | 28–29.7 MHz | HF | **专用** | ✗ |
| **6 m** | **50–54 MHz** | VHF | **主要** | ✅ |
| **2 m** | **144–148 MHz** | VHF | **144–146 唯一主要；146–148 共用主要** | ✅ |
| **70 cm** | **430–440 MHz** | UHF | **次要**（主要业务=无线电定位+航空导航） | ✅ |
| 13 cm | 2300–2450 MHz | UHF | 次要 | ✅ |
| — | 5650–5850 MHz | SHF | 次要 | ✅ |
| 最高 | 241–250 GHz | EHF | 唯一主要 | ✅ |

**本地联络应避让的卫星子段**：144 MHz 避 144–144.035 / 145.8–146；430 MHz 避 431.9–432.24 / 435–438。
**中继标准频差**：144 MHz → 0.6 MHz；430 MHz → 5 MHz。

---

## 五、发射类别（emission designator）

> 对应 §2.5.1。三个符号 = 载波调制 + 调制信号性质 + 信息类型。

| 第 1 位（载波调制） | 第 2 位（调制信号） | 第 3 位（信息类型） |
|---|---|---|
| **A** 双边带调幅 | **0** 无调制 | **A** 人工电报（莫尔斯听抄） |
| **J** 单边带抑制载波 | **1** 数字、无副载波 | **B** 自动电报（机器收） |
| **F** 调频 | **2** 数字、有副载波 | **E** 电话（语音） |
| **G** 调相 | **3** 模拟（单通道） | **F** 电视/图像 |

**常考组合**：

| 符号 | 含义 |
|---|---|
| **A1A** | CW（莫尔斯电报） |
| **J3E** | SSB 单边带话 |
| **F3E** | FM 调频话 |
| **F3F** | FM 图像（ATV/SSTV） |
| **F2B** | FM 上的数据/RTTY |

---

## 六、RST 信号报告制

| 字母 | 含义 | 范围 | 用于 |
|---|---|---|---|
| **R** | 可辨度（Readability） | 1–5 | 所有方式 |
| **S** | 信号强度（Strength） | 1–9 | 所有方式 |
| **T** | 音调纯度（Tone） | 1–9 | **仅 CW** |

> 话音报两位（如 **59**），CW 报三位（如 **599**）。**S 表每升 1 格 ≈ 6 dB。**

---

## 七、dB 与功率速查

| 关系 | dB |
|---|---|
| ×2 | +3 dB |
| ×4 | +6 dB（= 1 个 S 格） |
| ×10 | +10 dB |
| ÷2 | −3 dB |

- **1 mW = 0 dBm**；**1 W = 30 dBm**；**5 W ≈ 37 dBm**。
- **dBi = dBd + 2.15**（半波偶极 = 0 dBd = 2.15 dBi）。
- 接收灵敏度：**1 μV @ 50 Ω（端电压）= −107 dBm = 0 dBμV**，电压翻倍 = +6 dB。

---

## 八、SI 单位词头

| T | G | M | k | m | μ | n | p |
|---|---|---|---|---|---|---|---|
| 10¹² 太 | 10⁹ 吉 | 10⁶ 兆 | 10³ 千 | 10⁻³ 毫 | 10⁻⁶ 微 | 10⁻⁹ 纳 | 10⁻¹² 皮 |

> ⚠️ **大写 M=兆（10⁶），小写 m=毫（10⁻³）**，最易混。

---

## 九、常被误传的"全称"（避坑清单）

下面这些缩写的全称/词源**最容易被网上资料写错**，本教程已逐一核实（来源：ITU《无线电规则》、ARRL、各官方文档）：

| 缩写 | ✅ 正确 | ❌ 常见错误 |
|---|---|---|
| **Q 简语**（QSL/QSO/QRZ/QRM…） | 国际约定三字母代码，**没有字母全称**，只有约定含义 | 各种自造"全称"（backronym）均为附会 |
| **FT8 / FT4** | **F**ranke-**T**aylor（两位作者姓氏）+ 8/4 电平 FSK | "Full Time" |
| **VOX** | Voice-Operated **eX**change（X 取自 eXchange） | "Voice Box" |
| **D-STAR** | Digital Smart **Technologies** for Amateur Radio（Technologies 复数） | "...Technology"（单数） |
| **YAGI** | 发明人**八木秀次**的姓，完整称 **Yagi-Uda**（八木-宇田），**非缩写** | 当作首字母缩略词去拆 |
| **CQ** | 普遍呼叫约定码，源自法语 *sécurité* | "Seek You"（民间附会） |
| **73 / 88** | 电报数字码（73=致意，88=爱与吻），**无英文词组全称** | 硬找英文短语 |
| **DE** | 源自**法语 de**（"来自"） | 当英文缩写 |
| **ES** | 源自美式摩尔斯电码里 "&" 的写法（=and） | "Et Sign"之类 |
| **UTC** | Coordinated Universal Time（字母序是英/法折中的中立选择，既非 CUT 也非 TUC） | 直接按英文 CUT |
| **AMSAT** | **R**adio **A**mateur **Sat**ellite Corporation（全称与字母不逐位对应） | 逐字母硬套 |
| **APRS** | Automatic Packet **Reporting** System | "...Position Reporting" |
| **ALC** | Automatic **Level** Control | "...Level Compensation" |
| **CTCSS** | Continuous **Tone-Coded** Squelch System | "...Tone Control" |
| **DTMF** | Dual-Tone **Multi-Frequency** | "...Multiple Frequency" |
| **截短键标**（SQL/PRE/PROC/ANT/VER/EL/BURO/RIG/BEAM） | 是英文单词的**截短**（squelch/preamp/processor/antenna…），**不是首字母缩略词** | 强行逐字母拆解 |

---

🏠 返回 [总目录 README](./README.md)
