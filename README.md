# Structural Determinants of Indigenous Health Disparities in Canada 🦄

![GitHub](https://img.shields.io/badge/R-Statistical%20Analysis-blue)
![GitHub](https://img.shields.io/badge/Health%20Equity-Indigenous%20Health-orange)
![GitHub](https://img.shields.io/badge/Methods-MFA→SEM→ML→Bayesian-green)
![GitHub](https://img.shields.io/badge/Policy-Territorial%20Organizations-purple)

## 🚀 Project Overview

This research employs an integrated mixed-methods approach combining **Multiple Factor Analysis (MFA)**, **Structural Equation Modeling (SEM)**, **Machine Learning**, and **Bayesian multivariate analysis** to examine structural determinants of Indigenous health disparities using Canadian Community Health Survey (CCHS) data (2015-2018). 

### 🎯 The Punchline
Mental health disparities (4.81× higher odds) operate through healthcare access barriers, while diabetes reflects historical trauma pathways—requiring completely different policy solutions! 🎯

## 🧩 The Methodological Magic Show

### Our Statistical Arsenal 🔬
```mermaid
graph TD
    A[MFA<br>🕵️ Structural Detective] --> B[SEM<br>🛣️ Pathway Explorer];
    B --> C[ML<br>🎯 Predictor Ranker];
    C --> D[Bayesian<br>🎲 Complexity Wizard];
    
    A --> E[56.4% Variance Explained];
    B --> F[CFI = 0.998];
    C --> G[92.9% Accuracy];
    D --> H[4.81× Mental Health Odds];
```

### Why This Rocks 🎸
- **Bayesian wizardry**: Regularizing priors that handle sample imbalance like a boss
- **ML that actually works**: 92.9% accuracy in spotting patterns humans miss
- **SEM with style**: Pathway diagrams that don't make your eyes bleed
- **MFA magic**: Seeing structural patterns in high-definition

## 📊 The Big Reveal: What We Found

### The Odds Are Not in Their Favor 🎲
| Health Pattern | Indigenous Odds | 95% Credible Interval | The Story |
|----------------|----------------|---------------------|-----------|
| 🧠 Mental Health Only | 4.81× | (4.48-5.15) | **Access barrier crisis** |
| 🧠⚕️ Both Conditions | 3.31× | (2.82-3.92) | **Complex care vortex** |
| ⚕️ Diabetes Only | 1.83× | (1.73-1.94) | **Historical trauma legacy** |

### The Pathway Puzzle 🧩
- **Mental Health**: 49% mediated through healthcare access (β = -0.040)
- **Diabetes**: Direct historical trauma effects (β = -0.023)  
- **Structural Roots**: 56.4% of variance from access barriers

## 🖼️ The Evidence Gallery

### Figure 1: Structural Patterns Revealed 🎨
![MFA Analysis](figures/mfa_analysis.png)
*MFA shows clear separation between Indigenous and non-Indigenous groups along healthcare access dimensions*

### Figure 2: Causal Pathways Unraveled 🛣️
![SEM Pathways](figures/sem_pathways.png)  
*SEM reveals divergent pathways: healthcare access mediation for mental health vs. direct effects for diabetes*

### Figure 3: Predictor Power Rankings 🏆
![Feature Importance](figures/feature_importance.png)
*Machine learning identifies mental health as the strongest differentiator (Gini = 26.3)*

### Figure 4: Multivariate Complexity 🎲
![Bayesian Analysis](figures/multivariate_bayesian.png)
*Bayesian modeling reveals dramatic odds ratios for mental health conditions*



### 🏛️ Why Policy Makers Should Care

**The code doesn't lie. But the data doesn't tell the whole story. 🔍**

Ran the numbers. Then ran them again with fancier math. The signal is unignorable.

*   **🧠 Mental Health = The System Failure**
    *   **4.81x higher odds** of poor mental health.
    *   Our model: shattered odds if you can't access a doctor.
    *   **Not a personal failure. A system failure.**
    *   **The Fix?** Indigenous-led models. Like the **First Nations Health Authority (FNHA)** in BC—rewriting the source code, integrating culture directly into care.

*   **🩺 Diabetes = The Legacy Code Bug**
    *   Disparity isn't just about today's clinic access.
    *   Our model picked up a **direct effect**—points to something deeper.
    *   **A bug in the historical code:** legacy of trauma, disrupted food systems.
    *   **Community Debugging:** The **Sioux Lookout Meno Ya Win Health Centre** (ON) serves traditional foods (wild game, fish) *in its hospital*. Directly addressing the historical disruption.

*   **📊 The Data Blind Spot 🚨**
    *   Our data (CCHS) **excludes on-reserve populations**.
    *   Our staggering findings? Likely a **conservative estimate**.
    *   Like debugging with only half the log files.
    *   **Solution:** Support Indigenous data sovereignty (e.g., First Nations Information Governance Centre's Regional Health Survey). Give communities the tools to diagnose their own systems.

**Bottom Line:** We provided the statistical trace. The stack lead points to two different bugs. The patches exist—they're being written by Indigenous communities. The question is: will policymakers allocate the resources to deploy them?

## 🛠️ Under the Hood: Technical Wizardry

### The Data Stack 📚
- **Sample**: CCHS 2015-2018 (N = 184,555)
- **Indigenous**: 12,986 brave souls sharing their stories
- **Methods**: The statistical A-team (MFA, SEM, ML, Bayesian)

### The Code Magic 🔮
```r
# The secret sauce
mfa_result <- MFA(health_domains)          # Pattern detective
sem_fit <- sem(access_pathways)            # Pathway explorer
rf_model <- randomForest(predictors)       # Importance ranker  
bayesian_model <- brm(health_patterns)     # Complexity wizard
```

### Bayesian Brilliance 🎲
- **Regularizing priors**: Making imbalance data behave
- **Multivariate modeling**: Because health is complicated
- **Credible intervals**: Honest uncertainty estimates

## 🚀 Let's Get This Party Started

### Prerequisites 🎒
```r
# The tool belt
install.packages(c(
  "tidyverse", "FactoMineR", "lavaan", 
  "randomForest", "brms", "cmdstanr"
))
```

### Execution 🏃‍♂️
```r
# One command to rule them all
rmarkdown::render("final_indigenous_health_analysis.Rmd")
```

## 📁 What's in the Box?

```
indigenous-health-disparities-analysis/
├── final_indigenous_health_analysis.Rmd     # The main event
├── indigenous_health_analysis.pdf          # The finished masterpiece
├── data/                                   # The raw materials
├── figures/                                # The art gallery
│   ├── mfa_analysis.png                    # 🎨 Structural patterns
│   ├── sem_pathways.png                    # 🛣️ Causal pathways  
│   ├── feature_importance.png              # 🏆 Predictor rankings
│   └── multivariate_bayesian.png           # 🎲 Complexity revealed
└── README.md                               # You are here! 🎯
```

## 📚 Intellectual Roots

- Truth and Reconciliation Commission Calls to Action
- United Nations Declaration on the Rights of Indigenous Peoples  
- First Nations Information Governance Centre OCAP® principles
- Reading & Wien historical trauma pathways
- Cultural safety as non-negotiable

## 📫 Let's Connect

- **LinkedIn**: [Timothy Leung](linkedin.com/in/timothy-leung-3928ba234)
- **GitHub**: [panpen-tim](https://github.com/panpen-tim)  
- **Email**: leungty@myumanitoba.ca

---

**Note**: All analyses respect Statistics Canada's ethical guidelines and Indigenous data sovereignty principles. The responsibility for data interpretation rests with the author.

*This research proves that advanced statistics and ethical engagement can dance together—honoring Indigenous self-determination while delivering rigorous health equity evidence.* 🎯🦄📊

Ready to push this to GitHub? The quirky emojis strike a nice balance - professional enough for academia but showing personality that makes your work memorable! 🚀
