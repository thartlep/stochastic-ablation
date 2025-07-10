# Beyond the Black Box: 
## Monte Carlo Ablation of Induction Heads in Pythia-160M

How do language models *actually* form circuits that repeat patterns and perform in-context learning?  
This repo uses a simple but powerful **Monte Carlo stochastic ablation** approach to probe which attention heads matter most in the Pythia-160M transformer — discovering not just known mover heads like **(5,0)** but also new suspects like **(3,2)**.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/thartlep/stochastic-ablation/blob/main/notebook.ipynb)
