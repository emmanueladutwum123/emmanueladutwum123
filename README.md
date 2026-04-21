<!-- ANIMATED HEADER -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Emmanuel%20Adutwum&fontSize=50&fontColor=fff&animation=twinkling&fontAlignY=35&desc=Software%20Engineer%20%7C%20ML%20Engineer%20%7C%20Quantitative%20Researcher&descAlignY=55&descSize=20" width="100%" />
</div>

<!-- TYPING SVG ANIMATION -->
<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=26&duration=2800&pause=1000&color=4958E0&center=true&vCenter=true&random=false&width=750&lines=Full-Stack+Engineer+%7C+React+%2B+FastAPI+%2B+WebSocket;Distributed+Real-Time+Systems+Builder;Machine+Learning+%7C+Deep+Learning+%7C+NLP;Quantitative+Finance+%7C+Algorithmic+Trading;Kalman+Filter+%7C+GARCH+%7C+Kelly+Criterion;Neural+Nets+from+Scratch+%7C+C%2B%2B+%7C+PyTorch" alt="Typing SVG" />
  </a>
</div>

<!-- BADGES -->
<div align="center">
  <img src="https://img.shields.io/badge/Software_Engineering-%234958E0.svg?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Machine_Learning-%234958E0.svg?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Full--Stack_%28React+%2B+FastAPI%29-%234958E0.svg?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Quantitative_Finance-%234958E0.svg?style=for-the-badge&logoColor=white" />
</div>

<br/>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=emmanueladutwum123&label=Profile%20Views&color=4958E0&style=for-the-badge" />
  <img src="https://img.shields.io/github/followers/emmanueladutwum123?style=for-the-badge&color=4958E0" />
  <a href="https://emmanueladutwum123.github.io">
    <img src="https://img.shields.io/badge/Portfolio-4958E0?style=for-the-badge&logo=githubpages&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/emmanuel-adutwum/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🧮 About Me

```python
class EmmanuelAdutwum:
    def __init__(self):
        self.role       = "Software Engineer · ML Engineer · Quantitative Researcher"
        self.education  = {
            "university":       "Soka University of America",
            "major":            "Economics & Mathematics",
            "mit_micromasters": "Statistics & Data Science (MITx)"
        }
        self.experience = ["Wells Fargo", "CNO Financial Group", "CSIR Ghana"]

        self.software_engineering = [
            "Distributed real-time systems  (WebSocket, event-driven architecture)",
            "Full-stack development         (React, FastAPI, REST APIs, PostgreSQL)",
            "Systems design                 (scalability, low-latency, data pipelines)",
            "Object-oriented & functional   (Python, C++, Java, TypeScript)",
            "Cloud & DevOps                 (AWS, Azure, Docker, CI/CD)",
        ]

        self.machine_learning = [
            "Deep Learning    (LSTM, Transformers, Attention, YOLOv5, PointNet)",
            "Classical ML     (SVR, Random Forest, Gradient Boosting, Clustering)",
            "NLP & Vision     (sequence models, 3D point cloud processing)",
            "MLOps            (model serving, experiment tracking, deployment)",
        ]

        self.quantitative_finance = [
            "Signal processing  (Kalman Filter, OU Process, ADF stationarity test)",
            "Volatility models  (GARCH, Hurst Exponent, EWMA)",
            "Options pricing    (Black-Scholes, Greeks, Delta Hedging)",
            "HFT / Market Making (Avellaneda-Stoikov, limit order book dynamics)",
            "Position sizing    (Kelly Criterion, CVaR, Monte Carlo simulation)",
        ]

        self.passions   = ["Deep Learning Research", "Systems Engineering",
                           "Quantitative Finance", "Open-Source ML"]

    def say_hello(self):
        return "Hi — I engineer production systems, train models, and build at the intersection of code and mathematics."

me = EmmanuelAdutwum()
print(me.say_hello())
```

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🚀 Flagship Project — M3 Ultra Alpha Trading System

<div align="center">

> **A production distributed system: event-driven data pipeline → real-time WebSocket API → React SPA**
> with a quantitative signal engine running live on MetaTrader 5

</div>

<table>
  <tr>
    <td width="55%">
      <h3>Systems Engineering</h3>
      <ul>
        <li><strong>Event-driven architecture</strong> — 1-second polling loop publishes to all WebSocket subscribers</li>
        <li><strong>REST + WebSocket API</strong> — FastAPI serves both; single origin, zero CORS complexity</li>
        <li><strong>React SPA</strong> — component-driven UI with custom hooks, lazy chart rendering, responsive layout</li>
        <li><strong>Data pipeline</strong> — MT5 COM bridge → Python → Pandas analytics → JSON stream</li>
        <li><strong>Zero-config public deployment</strong> — Cloudflare Quick Tunnel; no DNS, no port-forwarding</li>
        <li><strong>Async alert system</strong> — Telegram Bot API, debounced with per-type cooldown state machine</li>
        <li><strong>TradingView Lightweight Charts v4</strong> — custom series overlays, dynamic markers, timeframe switching</li>
      </ul>
      <h3>Quantitative Signal Engine</h3>
      <ul>
        <li><strong>Kalman Filter</strong> — noise-filtered price trend (1D, mirrors MQL5 CKalmanFilter1D)</li>
        <li><strong>GARCH(1,1)</strong> — conditional volatility regime gating</li>
        <li><strong>Hurst Exponent</strong> — trend (H>0.6) vs. mean-reversion (H&lt;0.4) classifier</li>
        <li><strong>Ornstein-Uhlenbeck z-score + ADF test</strong> — stationarity-validated mean-reversion entries</li>
        <li><strong>Kelly Criterion</strong> — optimal fractional position sizing</li>
        <li>Instruments: <strong>EURUSD · GBPUSD · USDJPY · US30 · USTEC</strong></li>
      </ul>
    </td>
    <td width="45%" align="center">
      <h3>Tech Stack</h3>
      <img src="https://img.shields.io/badge/React_18-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" /><br/>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/WebSocket_(real--time)-010101?style=for-the-badge&logo=socketdotio&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Pandas_%2B_NumPy-150458?style=for-the-badge&logo=pandas&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/MQL5-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Cloudflare_Tunnel-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" />
    </td>
  </tr>
</table>

<div align="center">

```
System Design:
  MT5 COM Bridge (Windows)
        │  1s polling loop
        ▼
  FastAPI (async, uvicorn)
        ├── /ws  ──── WebSocket broadcast ──── React SPA (useWebSocket hook)
        ├── /api/ohlcv/{symbol}               CandlestickChart + Kalman overlay
        ├── /api/analytics/monthly            P&L calendar heatmap
        ├── /api/analytics/session            7×24 session heatmap
        ├── /api/analytics/correlation        Pearson matrix (Pandas pivot)
        └── /api/analytics/rolling            Rolling Sharpe & Sortino
                                                     │
                                              Telegram Bot API
                                         (alert state machine, 5-min cooldown)
```

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🏆 Achievements & Highlights

<div align="center">

<table>
  <tr>
    <td align="center" width="25%">
      <img src="https://img.shields.io/badge/%2425%2C000-Research_Grant-FFD700?style=for-the-badge&logo=academia&logoColor=black" /><br/>
      <strong>$25,000 Award</strong><br/>
      <sub>Competitive grant for cryptographic security research in FinTech — applied to blockchain-based authentication protocols</sub>
    </td>
    <td align="center" width="25%">
      <img src="https://img.shields.io/badge/Pi_Mu_Epsilon-2×_Published-4958E0?style=for-the-badge&logo=latex&logoColor=white" /><br/>
      <strong>Published Mathematician</strong><br/>
      <sub>Two accepted problem solutions in <em>Pi Mu Epsilon Journal</em> — USA's premier undergraduate mathematics journal (#1131, #1385)</sub>
    </td>
    <td align="center" width="25%">
      <img src="https://img.shields.io/badge/MITx-MicroMasters-A31F34?style=for-the-badge&logo=mit&logoColor=white" /><br/>
      <strong>MIT MicroMasters</strong><br/>
      <sub>Statistics & Data Science — graduate-level program covering probability theory, inference, ML, and data analysis</sub>
    </td>
    <td align="center" width="25%">
      <img src="https://img.shields.io/badge/Live_System-Algorithmic_Trading-00C853?style=for-the-badge&logo=chartdotjs&logoColor=white" /><br/>
      <strong>Production Trading System</strong><br/>
      <sub>M3 Ultra Alpha runs live on MT5 across 5 instruments — Kalman, GARCH, Hurst, Kelly all operating in real markets</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="25%">
      <img src="https://img.shields.io/badge/0.788_R²-SVR_ML_Model-4958E0?style=for-the-badge&logo=scikit-learn&logoColor=white" /><br/>
      <strong>ML Benchmark Result</strong><br/>
      <sub>0.788 R² on California Housing via optimised SVR — systematic kernel & hyperparameter search outperforming standard baselines</sub>
    </td>
    <td align="center" width="25%">
      <img src="https://img.shields.io/badge/Wells_Fargo_%7C_CNO_%7C_CSIR-Industry_Experience-1565C0?style=for-the-badge&logo=briefcase&logoColor=white" /><br/>
      <strong>Industry Experience</strong><br/>
      <sub>Financial services & research across Wells Fargo, CNO Financial Group, and CSIR Ghana — real-world quantitative & engineering work</sub>
    </td>
    <td align="center" width="25%">
      <img src="https://img.shields.io/badge/HFT_Engine-C%2B%2B_LOB-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" /><br/>
      <strong>HFT Market Making Engine</strong><br/>
      <sub>Built Avellaneda-Stoikov market maker in C++ with live limit order book, inventory risk management, and spread optimisation</sub>
    </td>
    <td align="center" width="25%">
      <img src="https://img.shields.io/badge/Ghana_Cocoa-Options_Pricing_Tool-4CAF50?style=for-the-badge&logo=chartdotjs&logoColor=white" /><br/>
      <strong>Real-World Finance Tool</strong><br/>
      <sub>Black-Scholes delta hedging simulator for Ghana Cocoa Board — live demo with volatility surface, Greeks, and AI price forecasting</sub>
    </td>
  </tr>
</table>

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 💡 What I Bring to Software Engineering Roles

<div align="center">

| Area | Demonstrated Through |
|:-----|:--------------------|
| **Distributed Systems** | M3 dashboard: WebSocket pub/sub, async FastAPI, event-driven data pipeline with real-time state management |
| **API Design** | RESTful endpoints with FastAPI (OHLCV, analytics, health); clean separation of transport and business logic |
| **Frontend Engineering** | React 18 SPA with custom hooks (`useWebSocket`), TradingView chart integration, component-driven architecture |
| **Data Pipelines** | MT5 → Python bridge → Pandas analytics → JSON → UI; handles OHLCV, trade history, account state |
| **Algorithms & Math** | Published Pi Mu Epsilon journal solver; Kalman filter, Hurst, Kelly Criterion from first principles in Python |
| **Low-Level Systems** | HFT market making engine in C++; limit order book, Avellaneda-Stoikov spread optimisation |
| **ML Engineering** | SVR (0.788 R²), LSTM, Transformers, YOLOv5/PointNet for Tesla sensor fusion — model training to deployment |
| **Cross-language** | Production code in Python · C++ · MQL5 · JavaScript/React · R · Java — pick up any stack quickly |

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 📊 Featured Projects

<div align="center">
  <table>
    <tr>
      <td width="50%">
        <h3 align="center">🧠 Neural Net Engine — C++17 from Scratch</h3>
        <div align="center">
          <a href="https://github.com/emmanueladutwum123/neural-net-cpp" target="_blank">
            <img src="https://img.shields.io/badge/CODE-121011?style=for-the-badge&logo=github&logoColor=white" />
          </a>
        </div>
        <p align="center">
          <strong>C++17 · Zero ML libs · Adam · BatchNorm · Dropout · ~97% MNIST</strong><br/>
          Full deep learning framework from scratch — custom matrix engine, backpropagation,
          Adam/SGD optimizers, BatchNorm, Dropout. Google Test suite + GitHub Actions CI.
        </p>
        <p align="center">
          <img src="https://img.shields.io/badge/C%2B%2B17-00599C?style=flat&logo=c%2B%2B&logoColor=white" />
          <img src="https://img.shields.io/badge/CMake-064F8C?style=flat&logo=cmake&logoColor=white" />
          <img src="https://img.shields.io/badge/Google_Test-4285F4?style=flat&logo=google&logoColor=white" />
        </p>
      </td>
      <td width="50%">
        <h3 align="center">⚡ GPT Transformer — PyTorch from Scratch</h3>
        <div align="center">
          <a href="https://github.com/emmanueladutwum123/gpt-from-scratch" target="_blank">
            <img src="https://img.shields.io/badge/CODE-121011?style=for-the-badge&logo=github&logoColor=white" />
          </a>
        </div>
        <p align="center">
          <strong>Multi-head causal attention · Weight tying · Top-k/p sampling · Cosine LR</strong><br/>
          Complete GPT architecture built from first principles — no HuggingFace.
          Trains on Shakespeare; generates coherent text with nucleus sampling.
        </p>
        <p align="center">
          <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" />
          <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
          <img src="https://img.shields.io/badge/Transformers-FF6F00?style=flat&logo=huggingface&logoColor=white" />
        </p>
      </td>
    </tr>
    <tr>
      <td width="50%">
        <h3 align="center">👁️ ResNet-18 + C++ ONNX Inference Pipeline</h3>
        <div align="center">
          <a href="https://github.com/emmanueladutwum123/cv-resnet-pipeline" target="_blank">
            <img src="https://img.shields.io/badge/CODE-121011?style=for-the-badge&logo=github&logoColor=white" />
          </a>
        </div>
        <p align="center">
          <strong>92%+ CIFAR-10 · ONNX Export · C++ Runtime · &lt;1ms inference</strong><br/>
          ResNet-18 from scratch in PyTorch → exported to ONNX → C++ ONNX Runtime inference.
          Benchmark shows sub-millisecond latency with full p50/p95/p99 profiling.
        </p>
        <p align="center">
          <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" />
          <img src="https://img.shields.io/badge/C%2B%2B17-00599C?style=flat&logo=c%2B%2B&logoColor=white" />
          <img src="https://img.shields.io/badge/ONNX-005CED?style=flat&logo=onnx&logoColor=white" />
        </p>
      </td>
      <td width="50%">
        <h3 align="center">QuantLab Pro — Quant Finance Calculator</h3>
        <div align="center">
          <a href="https://emmanueladutwum123.github.io/quantlab-pro" target="_blank">
            <img src="https://img.shields.io/badge/LIVE_WEB_APP-4958E0?style=for-the-badge&logo=googlechrome&logoColor=white" />
          </a>
          <a href="https://github.com/emmanueladutwum123/quantlab-pro" target="_blank">
            <img src="https://img.shields.io/badge/CODE-121011?style=for-the-badge&logo=github&logoColor=white" />
          </a>
        </div>
        <p align="center">
          <strong>Black-Scholes · Avellaneda-Stoikov HFT · Kelly · GARCH · Hurst · OU · Cocoa Derivatives</strong><br/>
          Institutional-grade quantitative finance calculator. All models run client-side in TypeScript.
          iOS · Android · Web — single Expo React Native codebase.
        </p>
        <p align="center">
          <img src="https://img.shields.io/badge/React_Native-20232A?style=flat&logo=react&logoColor=61DAFB" />
          <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white" />
          <img src="https://img.shields.io/badge/Expo-000020?style=flat&logo=expo&logoColor=white" />
        </p>
      </td>
      <td width="50%">
        <h3 align="center">Ghana Cocoa Options & Delta Hedging</h3>
        <div align="center">
          <a href="https://emmanueladutwum123.github.io/ghana-cocoa-hedging/" target="_blank">
            <img src="https://img.shields.io/badge/LIVE_DEMO-4958E0?style=for-the-badge&logo=github&logoColor=white" />
          </a>
          <a href="https://github.com/emmanueladutwum123/black-scholes-delta-hedging" target="_blank">
            <img src="https://img.shields.io/badge/CODE-121011?style=for-the-badge&logo=github&logoColor=white" />
          </a>
        </div>
        <p align="center">
          <strong>Black-Scholes · Delta Hedging · Real-time Greeks · Commodity Finance</strong><br/>
          Options pricing & dynamic delta hedging simulator for Ghana Cocoa Board.
          Includes volatility surface, P&L scenarios, and AI price forecasting.
        </p>
        <p align="center">
          <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
          <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" />
          <img src="https://img.shields.io/badge/Chart.js-FF6384?style=flat&logo=chartdotjs&logoColor=white" />
        </p>
      </td>
      <td width="50%">
        <h3 align="center">HF Market Making Simulator</h3>
        <div align="center">
          <a href="https://github.com/emmanueladutwum123/High-Frequency-Market-Making-Simulation" target="_blank">
            <img src="https://img.shields.io/badge/CODE-121011?style=for-the-badge&logo=github&logoColor=white" />
          </a>
        </div>
        <p align="center">
          <strong>Avellaneda-Stoikov · Limit Order Book · Inventory Risk · Market Microstructure</strong><br/>
          Real-time HFT market making engine with LOB visualisation, spread optimisation,
          and multi-strategy backtesting framework.
        </p>
        <p align="center">
          <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=c%2B%2B&logoColor=white" />
          <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
          <img src="https://img.shields.io/badge/WebSocket-010101?style=flat&logo=socketdotio&logoColor=white" />
        </p>
      </td>
    </tr>
    <tr>
      <td width="50%">
        <h3 align="center">SVR California Housing Prediction</h3>
        <div align="center">
          <a href="https://github.com/emmanueladutwum123/SVR-on-California-Housing-Dataset" target="_blank">
            <img src="https://img.shields.io/badge/CODE-121011?style=for-the-badge&logo=github&logoColor=white" />
          </a>
        </div>
        <p align="center">
          <strong>SVR · Feature Engineering · Hyperparameter Tuning · 0.788 R²</strong><br/>
          Optimised Support Vector Regression achieving 0.788 R² on California Housing —
          outperforming standard ML baselines through systematic kernel & C/ε tuning.
        </p>
        <p align="center">
          <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
          <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white" />
          <img src="https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white" />
        </p>
      </td>
      <td width="50%">
        <h3 align="center">Cryptography & FinTech Research</h3>
        <div align="center">
          <a href="https://github.com/emmanueladutwum123?tab=repositories" target="_blank">
            <img src="https://img.shields.io/badge/RESEARCH-4958E0?style=for-the-badge&logo=google-scholar&logoColor=white" />
          </a>
        </div>
        <p align="center">
          <strong>Cryptography · Blockchain · Financial Security · $25,000 Grant</strong><br/>
          Award-winning research on cryptographic protocols for fintech security,
          including blockchain-based transaction authentication systems.
        </p>
        <p align="center">
          <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
          <img src="https://img.shields.io/badge/Research-FF6B6B?style=flat&logo=academia&logoColor=white" />
        </p>
      </td>
    </tr>
  </table>
</div>

<div align="center">
  <a href="https://github.com/emmanueladutwum123?tab=repositories">
    <img src="https://img.shields.io/badge/VIEW_ALL_PROJECTS-4958E0?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 📚 Publications & Research

<div align="center">

| Publication | Venue | Link |
|:------------|:------|:----:|
| **Can SVR with optimized feature engineering achieve 0.788 R² on California housing prices?** | In Progress | [![View](https://img.shields.io/badge/View-4958E0?style=flat)](https://github.com/emmanueladutwum123) |
| **Equilateral Triangle Geometry Problem** | Pi Mu Epsilon Journal #1131 | [![PDF](https://img.shields.io/badge/PDF-FF6B6B?style=flat)](https://pme-math.org/wp-content/uploads/2025/10/PME2025_Fall_NewProbSolns.pdf) |
| **Continued Fractions, α-Fibonacci Numbers, and the Middle b-Noise** | Pi Mu Epsilon Journal #1385 | [![PDF](https://img.shields.io/badge/PDF-FF6B6B?style=flat)](https://pme-math.org/wp-content/uploads/2023/08/PME2022_Fall_NewProbSolns.pdf) |

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 📈 GitHub Analytics

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=emmanueladutwum123&show_icons=true&theme=transparent&title_color=4958E0&icon_color=4958E0&text_color=ccd6f6&bg_color=0a192f&hide_border=true&count_private=true&include_all_commits=true" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=emmanueladutwum123&layout=compact&langs_count=8&theme=transparent&title_color=4958E0&text_color=ccd6f6&bg_color=0a192f&hide_border=true" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=emmanueladutwum123&theme=transparent&hide_border=true&stroke=4958E0&ring=4958E0&fire=4958E0&currStreakNum=ccd6f6&sideNums=ccd6f6&currStreakLabel=4958E0&sideLabels=ccd6f6&dates=8892b0" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=emmanueladutwum123&bg_color=0a192f&color=4958E0&line=4958E0&point=ccd6f6&area=true&hide_border=true" width="100%" />
</div>

<!-- GITHUB TROPHIES -->
<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=emmanueladutwum123&theme=discord&no-frame=true&no-bg=true&margin-w=8&column=7" width="100%" />
</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🛠️ Technology Stack

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![MQL5](https://img.shields.io/badge/MQL5-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

### Frontend & UI
![React](https://img.shields.io/badge/React_18-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Backend, APIs & Databases
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### Machine Learning & AI
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

### Cloud, DevOps & Tools
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🌐 Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/emmanuel-adutwum/)
[![Portfolio](https://img.shields.io/badge/Portfolio-4958E0?style=for-the-badge&logo=githubpages&logoColor=white)](https://emmanueladutwum123.github.io)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/c/emmanuelsoneuclid)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/fx_emmanueldx)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:emmanuelsoneuclid10@gmail.com)

</div>

<!-- FOOTER -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer&animation=twinkling" width="100%" />
  <sub>Emmanuel Adutwum · Updated April 2026</sub>
</div>
