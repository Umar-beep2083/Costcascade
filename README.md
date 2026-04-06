# CostCascade 🌊🌩️

> **Trace the cascading ripple effect of tariff shocks across the supply chain.**

**CostCascade** is a stunning, interactive simulation dashboard that maps out precisely how semiconductor tariff increases (like the US CHIPS Act or specific geopolitical embargoes) compound through varying supply chain stages—ultimately landing as massive Customer Acquisition Cost (CAC) spikes for fintech companies. 

## ✨ Features
- 🎨 **Premium Glassmorphic UI**: Rendered with deep mesh radial gradients, frosted glass cards, and immersive micro-animations.
- ⚡ **Real-Time Calculation Engine**: Instantly models four dynamic stages of cost inflation (Component Import -> Terminal Assembly -> Merchant Deploy -> Fintech CAC).
- 📈 **ML Cost Amplification Forecast**: Employs an Ordinary Least Squares (OLS) regression algorithm to dynamically project upper-bound cost spikes through 2028 with 90%+ R² confidence.
- 📊 **Dynamic Waterfall Rendering**: Calculates and visually renders exact dollar flow accumulation automatically onto an SVG waterfall chart.
- 📱 **Fully Responsive**: Beautiful, reactive UI built purely in native HTML/CSS/JS without heavy framework bloat.

## 🚀 The Underlying Math

Every slider adjust triggers the cascading formula:
```javascript
componentDelta = BaseCost × CostRatio × TariffRate × (1 - LocalAssemblyRate)
terminalDelta  = componentDelta × (1 + ImportDuty)
deployDelta    = terminalDelta × (1 + DeploymentOverhead)
finalCACDelta  = deployDelta × (1 - FintechSubsidy)
```
*A simple 25% component chip tariff creates an amplified x1.5+ final burden at the bottom of the supply chain.*

## 💻 Tech Stack
- **Structure:** HTML5 
- **Styling:** Vanilla CSS3 (Advanced custom properties, flex/grid, backdrop filters, animations)
- **Logic:** Vanilla ES6+ JavaScript
- **Fonts:** 'Outfit' & 'JetBrains Mono'

## 🏃 Getting Started
Because **CostCascade** is completely dependency-free, getting started takes literal seconds.
1. Clone this repository.
2. Double click `index.html` to open it in your favorite modern browser.
3. Start sliding to simulate global economic shocks!

---
*Built with precision and data-driven insights. Default benchmarks modeled on SBP FY25 POS terminal data.*

*Credits: Fawad Khan*
