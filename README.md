<!-- ═══════════════════════════════════════════════════════════════════════════
     KouchaLab · amber neon — nested-HTML profile
     theme color : #ff9e64  |  bg : #0a0c12  |  accent : #00d9ff
     nerd font   : Nerd Fonts (JetBrains Mono / FiraCode Nerd) recommended
     ═══════════════════════════════════════════════════════════════════════════ -->

<div align="center">

<br/>

<!-- ░░░ outer frame ░░░ -->
<div style="
  border:1px solid #ff9e64;
  border-radius:18px;
  background:
    radial-gradient(1200px 300px at 50% -80px, rgba(255,158,100,.16), transparent 70%),
    linear-gradient(180deg,#0d1018 0%,#0a0c12 100%);
  padding:34px 42px 30px 42px;
  max-width:960px;
  box-shadow:0 0 0 1px rgba(255,158,100,.15), 0 12px 60px -12px rgba(255,158,100,.25);
  font-family:'JetBrains Mono','FiraCode Nerd','Cascadia Code',monospace;">

  <!-- corner ticks -->
  <div style="font-size:11px;color:#ff9e64;letter-spacing:3px;opacity:.55;
    border-top:1px dashed rgba(255,158,100,.35);
    border-bottom:1px dashed rgba(255,158,100,.35);
    padding:6px 0;margin-bottom:22px;">
    ▓▒░ &nbsp; K O U C H A L A B &nbsp; — &nbsp; S Y S T E M &nbsp; P R O F I L E &nbsp; ░▒▓
  </div>

  <!-- ░░░ header block ░░░ -->
  <div style="display:flex;flex-direction:column;gap:14px;">

    <div style="font-size:46px;letter-spacing:2px;
      background:linear-gradient(90deg,#ffb887,#ff9e64 40%,#00d9ff);
      -webkit-background-clip:text;background-clip:text;color:transparent;
      font-weight:800;">
      󰕿 TakanashiKoucha
    </div>

    <div style="font-size:15px;color:#9aa7bd;letter-spacing:1px;">
      <span style="color:#ff9e64;">▐</span> Fake World <span style="opacity:.4;">///</span>
      Embedded <span style="opacity:.4;">·</span> NLP <span style="opacity:.4;">·</span>
      Self-hosted Lab <span style="color:#00d9ff;">▌</span>
    </div>

    <!-- status line, fastfetch-inspired -->
    <div style="font-size:12px;color:#67748e;
      border:1px solid rgba(103,116,142,.35);border-radius:8px;
      padding:7px 12px;background:rgba(255,255,255,.02);">
      <span style="color:#4ade80;">●</span>&nbsp; fedorAAA :
      <span style="color:#9aa7bd;">Fedora 44 · KDE 6.7 · kernel 7.1.10</span> &nbsp;│&nbsp;
      <span style="color:#ff9e64;">󰻠</span> 9900X @ 5.75&nbsp;GHz &nbsp;│&nbsp;
      <span style="color:#00d9ff;">󰈭</span> R9700 32&nbsp;GB &nbsp;│&nbsp;
      <span style="color:#c084fc;">󰓡</span> 30&nbsp;GiB DDR5
    </div>

  </div>

  <br/>

  <!-- ░░░ AI hero — the focus ░░░ -->
  <div style="
    border:1px solid rgba(0,217,255,.4);border-radius:14px;
    background:linear-gradient(135deg,rgba(0,217,255,.08),rgba(255,158,100,.06));
    padding:22px 26px;margin-top:6px;">

    <div style="display:flex;align-items:baseline;gap:12px;margin-bottom:14px;">
      <span style="font-size:26px;">󰚩</span>
      <span style="font-size:19px;font-weight:700;color:#e8eef9;letter-spacing:1px;">
        AI · Compute Stack
      </span>
      <span style="font-size:11px;color:#00d9ff;letter-spacing:2px;
        border:1px solid rgba(0,217,255,.4);border-radius:999px;padding:2px 10px;">
        RDNA 4 · ROCm 7
      </span>
    </div>

    <!-- nested GPU card -->
    <div style="
      border:1px solid rgba(255,158,100,.45);border-radius:12px;
      background:rgba(10,12,18,.6);padding:18px 20px;margin-bottom:14px;">

      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:10px;">
        <span style="color:#ff9e64;font-weight:700;font-size:15px;">
          󰈭 &nbsp;Radeon™ AI PRO R9700
        </span>
        <span style="font-size:11px;color:#67748e;">Navi 48 · 32 GB GDDR6 · PCIe 5.0</span>
      </div>

      <!-- nested metric grid -->
      <div style="display:grid;grid-template-columns:repeat(4,1fr);gap:10px;">

        <div style="border-left:3px solid #ff9e64;padding:6px 10px;background:rgba(255,158,100,.06);">
          <div style="font-size:10px;color:#67748e;letter-spacing:1px;">AI TOPS</div>
          <div style="font-size:20px;font-weight:800;color:#ff9e64;">766</div>
        </div>

        <div style="border-left:3px solid #ffb887;padding:6px 10px;background:rgba(255,158,100,.05);">
          <div style="font-size:10px;color:#67748e;letter-spacing:1px;">FP32 TFLOPS</div>
          <div style="font-size:20px;font-weight:800;color:#ffb887;">383</div>
        </div>

        <div style="border-left:3px solid #ffd9c0;padding:6px 10px;background:rgba(255,158,100,.04);">
          <div style="font-size:10px;color:#67748e;letter-spacing:1px;">MEMORY</div>
          <div style="font-size:20px;font-weight:800;color:#ffd9c0;">32 GB</div>
        </div>

        <div style="border-left:3px solid #00d9ff;padding:6px 10px;background:rgba(0,217,255,.05);">
          <div style="font-size:10px;color:#67748e;letter-spacing:1px;">ROCm</div>
          <div style="font-size:20px;font-weight:800;color:#00d9ff;">READY</div>
        </div>

      </div>

      <!-- nested tagline -->
      <div style="margin-top:12px;font-size:12px;color:#9aa7bd;font-style:italic;
        border-top:1px dashed rgba(255,158,100,.3);padding-top:10px;">
        “ Great capabilities for local AI inference, development, and other
        memory-intensive workloads ”
      </div>

    </div>

    <!-- nested CPU AI card -->
    <div style="
      border:1px solid rgba(0,217,255,.35);border-radius:12px;
      background:rgba(10,12,18,.6);padding:18px 20px;">

      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:10px;">
        <span style="color:#00d9ff;font-weight:700;font-size:15px;">
          󰻠 &nbsp;Ryzen™ 9 9900X
        </span>
        <span style="font-size:11px;color:#67748e;">12C / 24T · Zen 5 · 64 MB L3</span>
      </div>

      <div style="display:grid;grid-template-columns:repeat(3,1fr);gap:10px;">

        <div style="border-left:3px solid #00d9ff;padding:6px 10px;background:rgba(0,217,255,.05);">
          <div style="font-size:10px;color:#67748e;letter-spacing:1px;">BOOST</div>
          <div style="font-size:20px;font-weight:800;color:#00d9ff;">5.75 GHz</div>
        </div>

        <div style="border-left:3px solid #67e8f9;padding:6px 10px;background:rgba(0,217,255,.04);">
          <div style="font-size:10px;color:#67748e;letter-spacing:1px;">AVX-512</div>
          <div style="font-size:20px;font-weight:800;color:#67e8f9;">+ BF16</div>
        </div>

        <div style="border-left:3px solid #a5f3fc;padding:6px 10px;background:rgba(0,217,255,.03);">
          <div style="font-size:10px;color:#67748e;letter-spacing:1px;">VNNI · FP16</div>
          <div style="font-size:20px;font-weight:800;color:#a5f3fc;">INT8</div>
        </div>

      </div>

      <div style="margin-top:12px;font-size:12px;color:#9aa7bd;font-style:italic;
        border-top:1px dashed rgba(0,217,255,.3);padding-top:10px;">
        “ Incredibly Powerful Processor — gaming, streaming &amp; local inference ”
      </div>

    </div>

  </div>

  <br/>

  <!-- ░░░ pipeline / data-flow visual ░░░ -->
  <div style="font-family:'JetBrains Mono',monospace;font-size:12px;color:#9aa7bd;
    border:1px solid rgba(103,116,142,.35);border-radius:10px;
    background:rgba(10,12,18,.55);padding:14px 18px;line-height:1.9;">

    <div style="color:#67748e;letter-spacing:2px;font-size:10px;margin-bottom:6px;">
      ▚▚ LOCAL AI PIPELINE ▞▞
    </div>

    <div style="display:flex;align-items:center;gap:8px;flex-wrap:wrap;">

      <span style="border:1px solid #ff9e64;border-radius:6px;padding:4px 10px;color:#ff9e64;">
        󰡨 tokenizer
      </span>
      <span style="color:#4a5568;">──▶</span>

      <span style="border:1px solid #ff9e64;border-radius:6px;padding:4px 10px;color:#ff9e64;">
        󰻠 CPU · AVX-512 BF16
      </span>
      <span style="color:#4a5568;">──▶</span>

      <span style="border:1px solid #00d9ff;border-radius:6px;padding:4px 10px;color:#00d9ff;
        background:rgba(0,217,255,.06);">
        󰈭 ROCm · 766 TOPS
      </span>
      <span style="color:#4a5568;">──▶</span>

      <span style="border:1px solid #c084fc;border-radius:6px;padding:4px 10px;color:#c084fc;">
        󰓡 32 GB VRAM
      </span>
      <span style="color:#4a5568;">──▶</span>

      <span style="border:1px solid #4ade80;border-radius:6px;padding:4px 10px;color:#4ade80;">
        󰓄 sample · RVC · TTS
      </span>

    </div>

  </div>

  <br/>

  <!-- ░░░ badges ░░░ -->
  <div style="display:flex;gap:8px;justify-content:center;flex-wrap:wrap;">

    <a href="https://github.com/Takanashikoucha?tab=followers">
      <img src="https://img.shields.io/github/followers/Takanashikoucha?label=Followers&color=00afdd&style=for-the-badge" alt="followers" />
    </a>
    <a href="https://github.com/stars/Takanashikoucha?tab=followers">
      <img src="https://img.shields.io/github/stars/Takanashikoucha?label=Stars&color=e15a4c&style=for-the-badge" alt="stars" />
    </a>
    <a href="https://github.com/Takanashikoucha?tab=repositories">
      <img src="https://img.shields.io/github/repos/Takanashikoucha?label=Repos&color=30a46c&style=for-the-badge" alt="repos" />
    </a>
    <a href="https://blog.kouchalab.win/">
      <img src="https://img.shields.io/badge/Blog-%E7%BA%A2%E8%8C%B6%E9%A6%86-FF9E64?style=for-the-badge&logo=rss&logoColor=white" alt="blog" />
    </a>
    <a href="https://github.com/Takanashikoucha?tab=stargazers">
      <img src="https://komarev.com/ghpvc/?username=Takanashikoucha&style=for-the-badge&color=ff9e64" alt="views" />
    </a>

  </div>

</div>

<br/>

</div>

<!-- ═══════════════════════════════════════════════════════════════════════════ -->
<div align="center">
  <div style="color:#67748e;font-size:12px;letter-spacing:4px;margin-bottom:18px;">
    ▚▚ &nbsp; S Y S T E M &nbsp; S P E C S &nbsp; ▞▞
  </div>
</div>

<div align="center">

<div style="
  border:1px solid rgba(255,158,100,.25);border-radius:16px;
  background:linear-gradient(180deg,rgba(13,16,24,.9),rgba(10,12,18,.9));
  max-width:900px;padding:26px 30px;
  font-family:'JetBrains Mono','FiraCode Nerd',monospace;">

  <!-- nested grid: 2 columns -->
  <div style="display:grid;grid-template-columns:1fr 1fr;gap:14px;">

    <!-- CPU -->
    <div style="border:1px solid rgba(0,217,255,.3);border-radius:10px;
      background:rgba(0,217,255,.03);padding:16px 18px;">
      <div style="color:#00d9ff;font-weight:700;font-size:14px;margin-bottom:8px;">
        󰻠 &nbsp;CPU
      </div>
      <div style="color:#e8eef9;font-size:13px;font-weight:600;margin-bottom:10px;">
        AMD Ryzen 9 9900X
      </div>
      <table style="width:100%;font-size:11px;color:#9aa7bd;border-collapse:collapse;">
        <tr><td style="color:#67748e;padding:2px 0;">Cores / Threads</td><td style="text-align:right;color:#e8eef9;">12C / 24T</td></tr>
        <tr><td style="color:#67748e;padding:2px 0;">Max Boost</td><td style="text-align:right;color:#00d9ff;">5.75 GHz</td></tr>
        <tr><td style="color:#67748e;padding:2px 0;">Cache</td><td style="text-align:right;color:#e8eef9;">12 MB L2 · 64 MB L3</td></tr>
        <tr><td style="color:#67748e;padding:2px 0;">ISA</td><td style="text-align:right;color:#ff9e64;">AVX-512 · BF16 · VNNI</td></tr>
      </table>
    </div>

    <!-- GPU -->
    <div style="border:1px solid rgba(255,158,100,.35);border-radius:10px;
      background:rgba(255,158,100,.03);padding:16px 18px;">
      <div style="color:#ff9e64;font-weight:700;font-size:14px;margin-bottom:8px;">
        󰈭 &nbsp;GPU · AI PRO
      </div>
      <div style="color:#e8eef9;font-size:13px;font-weight:600;margin-bottom:10px;">
        Radeon AI PRO R9700
      </div>
      <table style="width:100%;font-size:11px;color:#9aa7bd;border-collapse:collapse;">
        <tr><td style="color:#67748e;padding:2px 0;">Architecture</td><td style="text-align:right;color:#e8eef9;">RDNA 4 · Navi 48</td></tr>
        <tr><td style="color:#67748e;padding:2px 0;">AI Performance</td><td style="text-align:right;color:#ff9e64;">766 TOPS</td></tr>
        <tr><td style="color:#67748e;padding:2px 0;">FP32</td><td style="text-align:right;color:#ffb887;">383 TFLOPS</td></tr>
        <tr><td style="color:#67748e;padding:2px 0;">Memory</td><td style="text-align:right;color:#e8eef9;">32 GB GDDR6 · PCIe 5.0</td></tr>
      </table>
    </div>

    <!-- Memory -->
    <div style="border:1px solid rgba(192,132,252,.3);border-radius:10px;
      background:rgba(192,132,252,.03);padding:16px 18px;">
      <div style="color:#c084fc;font-weight:700;font-size:14px;margin-bottom:8px;">
        󰓡 &nbsp;MEMORY
      </div>
      <div style="color:#e8eef9;font-size:13px;font-weight:600;margin-bottom:10px;">
        32 GB DDR5 + 39 GB zram
      </div>
      <div style="font-size:11px;color:#67748e;line-height:1.7;">
        <div style="display:flex;justify-content:space-between;margin-bottom:4px;">
          <span>system RAM</span><span style="color:#c084fc;">30 GiB</span>
        </div>
        <div style="height:8px;background:rgba(192,132,252,.15);border-radius:4px;overflow:hidden;">
          <div style="width:51%;height:100%;background:linear-gradient(90deg,#c084fc,#ff9e64);"></div>
        </div>
        <div style="display:flex;justify-content:space-between;margin-top:8px;margin-bottom:4px;">
          <span>zram swap</span><span style="color:#c084fc;">39 GiB</span>
        </div>
        <div style="height:8px;background:rgba(192,132,252,.15);border-radius:4px;overflow:hidden;">
          <div style="width:100%;height:100%;background:rgba(192,132,252,.35);"></div>
        </div>
      </div>
    </div>

    <!-- Storage -->
    <div style="border:1px solid rgba(74,222,128,.3);border-radius:10px;
      background:rgba(74,222,128,.03);padding:16px 18px;">
      <div style="color:#4ade80;font-weight:700;font-size:14px;margin-bottom:8px;">
        󰌁 &nbsp;STORAGE
      </div>
      <div style="color:#e8eef9;font-size:13px;font-weight:600;margin-bottom:10px;">
        1 TB WD_BLACK SN7100
      </div>
      <div style="font-size:11px;color:#67748e;line-height:1.7;">
        <div style="display:flex;justify-content:space-between;margin-bottom:4px;">
          <span>NVMe PCIe 4.0 · btrfs</span><span style="color:#4ade80;">929 GB</span>
        </div>
        <div style="height:8px;background:rgba(74,222,128,.15);border-radius:4px;overflow:hidden;">
          <div style="width:13%;height:100%;background:#4ade80;"></div>
        </div>
      </div>
    </div>

  </div>

  <!-- OS / Kernel / Display — full-width nested row -->
  <div style="margin-top:14px;border:1px solid rgba(255,158,100,.3);border-radius:10px;
    background:rgba(255,158,100,.02);padding:14px 18px;
    display:flex;justify-content:space-between;gap:18px;flex-wrap:wrap;">

    <div>
      <div style="color:#67748e;font-size:10px;letter-spacing:1px;margin-bottom:4px;">OS / KERNEL</div>
      <div style="color:#e8eef9;font-size:13px;font-weight:600;">
        󰊠 &nbsp;Fedora 44 · KDE Plasma 6.7
      </div>
      <div style="color:#9aa7bd;font-size:11px;margin-top:2px;">
        kernel 7.1.10-200.fc44 · x86_64
      </div>
    </div>

    <div>
      <div style="color:#67748e;font-size:10px;letter-spacing:1px;margin-bottom:4px;">DISPLAY</div>
      <div style="color:#e8eef9;font-size:13px;font-weight:600;">
        󰍿 &nbsp;1920 × 1080 @ 60 Hz
      </div>
      <div style="color:#9aa7bd;font-size:11px;margin-top:2px;">
        HDMI-A-1 · 32"
      </div>
    </div>

    <div>
      <div style="color:#67748e;font-size:10px;letter-spacing:1px;margin-bottom:4px;">STACK</div>
      <div style="color:#ff9e64;font-size:13px;font-weight:600;">
        󰚩 &nbsp;Full AMD — kernel → GPU
      </div>
      <div style="color:#9aa7bd;font-size:11px;margin-top:2px;">
        self-managed · ROCm 7
      </div>
    </div>

  </div>

</div>

<br/>

</div>

<!-- ═══════════════════════════════════════════════════════════════════════════ -->
<div align="center">
  <div style="color:#67748e;font-size:12px;letter-spacing:4px;margin:26px 0 18px;">
    ▚▚ &nbsp; A B O U T &nbsp; ▞▞
  </div>
</div>

> <b style="color:#ff9e64;">Fake World</b> — building real things in it.

- 🛠️ 嵌入式与 MCU 指令级仿真（Renesas RH850 → WASM），中日 NLP 与平行语料，以及把一切能 self-host 的服务都搬回家。
- 🌱 Rust + WASM 交叉编译、CPU 仿真器异常/FPU 路径、语音克隆（RVC）与 TTS。
- 🧰 Python 打底，Rust / Go / C 按需深入；zsh + polybar 终端流；Fedora KDE 桌面。
- ☕ 自托管栈（DNS / 反代 / 文件同步 / PAM）、OpenWrt、车载电子（AUTOSAR / CAN / ESP32-CAN）、日语学习工具。

<br/>

<!-- ═══════════════════════════════════════════════════════════════════════════ -->
<div align="center">
  <div style="color:#67748e;font-size:12px;letter-spacing:4px;margin:26px 0 18px;">
    ▚▚ &nbsp; T E C H &nbsp; S T A C K &nbsp; ▞▞
  </div>
</div>

<p align="center">
  <img src="https://skillicons.dev/icons?i=python" height="32" alt="Python"/>
  <img src="https://skillicons.dev/icons?i=rust" height="32" alt="Rust"/>
  <img src="https://skillicons.dev/icons?i=go" height="32" alt="Go"/>
  <img src="https://skillicons.dev/icons?i=cpp" height="32" alt="C++"/>
  <img src="https://skillicons.dev/icons?i=typescript" height="32" alt="TypeScript"/>
  <img src="https://skillicons.dev/icons?i=html" height="32" alt="HTML"/>
  <img src="https://skillicons.dev/icons?i=lua" height="32" alt="Lua"/>
  <img src="https://skillicons.dev/icons?i=bash" height="32" alt="Bash"/>
  <img src="https://skillicons.dev/icons?i=sql" height="32" alt="SQL"/>
  <img src="https://skillicons.dev/icons?i=vue" height="32" alt="Vue"/>
  <img src="https://skillicons.dev/icons?i=wasm" height="32" alt="WASM"/>
  <img src="https://skillicons.dev/icons?i=flask" height="32" alt="Flask"/>
  <img src="https://skillicons.dev/icons?i=docker" height="32" alt="Docker"/>
  <img src="https://skillicons.dev/icons?i=nginx" height="32" alt="Nginx"/>
  <img src="https://skillicons.dev/icons?i=ffmpeg" height="32" alt="FFmpeg"/>
  <img src="https://skillicons.dev/icons?i=git" height="32" alt="Git"/>
  <img src="https://skillicons.dev/icons?i=fedora" height="32" alt="Fedora"/>
  <img src="https://skillicons.dev/icons?i=kde" height="32" alt="KDE"/>
  <img src="https://skillicons.dev/icons?i=linux" height="32" alt="Linux"/>
</p>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════════════ -->
<div align="center">
  <div style="color:#67748e;font-size:12px;letter-spacing:4px;margin:26px 0 18px;">
    ▚▚ &nbsp; R E S E A R C H &nbsp; &amp; &nbsp; L E A R N I N G &nbsp; ▞▞
  </div>
</div>

> 方向从 136 个 ★ 聚类而来

| Direction | Focus |
|:---|:---|
| 🛠️ **Embedded & MCU** | FreeRTOS · ESP32-CAN · AUTOSAR · RH850 仿真器 |
| 🧠 **NLP / 中日双语** | 语料采集 · 多语言词向量 · ginza · CS224n |
| 🌐 **Self-hosting & Network** | DNS · 反代 · Alist · JumpServer · OpenWrt |
| 🔬 **Systems & RE** | Ghidra · 汇编阅读 · 模拟器 |
| 🎵 **Audio & Voice** | RVC · TTS · 实时变声 |

<br/>

<!-- ═══════════════════════════════════════════════════════════════════════════ -->
<div align="center">
  <div style="color:#67748e;font-size:12px;letter-spacing:4px;margin:26px 0 18px;">
    ▚▚ &nbsp; C O N T A C T &nbsp; ▞▞
  </div>
</div>

<p align="center">
  <a href="https://blog.kouchalab.win/">
    <img src="https://img.shields.io/badge/Blog-%E7%BA%A2%E8%8C%B6%E9%A6%86-%E5%85%8B%E5%8A%9B%E8%8C%B6?style=for-the-badge&logo=firefox&logoColor=white&color=ff9e64" alt="blog" />
  </a>
  <a href="https://github.com/Takanashikoucha">
    <img src="https://img.shields.io/badge/GitHub-Takanashikoucha-black?style=for-the-badge&logo=github" alt="github" />
  </a>
</p>

<br/>

<p align="center">
  <sub>⚡ <b>theme</b>: KouchaLab amber neon · <b>last update</b>: 2026-08-26 · <b>render</b>: Nerd Fonts</sub>
</p>
