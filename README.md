<h1 align="center">Hi 👋, I'm Humphrey</h1>
<h3 align="center">PhD Researcher in Programming Languages & Systems at the University of Kent</h3>

<p align="center">
  <img title="Profiler" alt="Man with glass" width="140px" src="https://github.com/HumphreyHCB/HumphreyHCB/blob/main/img/Profiler.png">
</p>

---

### 💡 About Me

I’m a PhD researcher in the **Programming Languages & Systems group** at the **University of Kent**, supervised by [Dr Stefan Marr](https://stefan-marr.de/).  
My research focuses on a long-standing challenge: **why Java profilers are so inaccurate, and why they disagree on what’s “hot.”**  
Sampling profilers can mislead developers, while traditional instrumentation can distort performance by **orders of magnitude**.

My work includes empirical studies of both sampling-based and instrumentation-based profilers. I have also developed a late compiler-stage instrumentation tool, **BuboC**, which avoids interfering with major compiler decisions, reducing overhead and minimising the observer effect.

<p align="center">
  <img alt="Overhead boxplot" width="420px" src="https://github.com/HumphreyHCB/HumphreyHCB/raw/main/img/Overhead-BoxPlot-Logarithmic-1.png">
</p>

I’m also designing **techniques to measure profiler accuracy itself**, introducing *controlled slowdowns* that reveal whether profilers can detect the *true* performance behaviour.

<p align="center">
  <img alt="Ground truth slowdown steps diagram" width="420px" src="https://github.com/HumphreyHCB/HumphreyHCB/raw/main/img/GroundTruthSteps.drawio-1.png">
</p>

Finally, I have developed a loop-centred instrumentation profiler inside the Graal compiler. This tool, **BuboL**, provides more accurate measurements of CPU time spent inside loops when compared with CPU sampling profilers.

<p align="center">
  <img alt="BuboL Accuracy plot" width="420px" src="https://github.com/HumphreyHCB/HumphreyHCB/raw/main/img/BuboL%20Accuracy.png">
</p>


> 🎯 **Goal**: Build profiling techniques that are accurate, practical, and measurable against ground truth.

---

### 📚 Selected Publications

- **Burchell, H., & Marr, S. (2025).**  
  *[Divining Profiler Accuracy: An Approach to Approximate Profiler Accuracy Through Machine Code-Level Slowdown.](https://doi.org/10.1145/3763180)*  
  *Proceedings of the ACM on Programming Languages (OOPSLA ’25).*  

- **Burchell, H., & Marr, S. (2025).**  
  *[Evaluating Candidate Instructions for Reliable Program Slowdown at the Compiler Level: Towards Supporting Fine-Grained Slowdown for Advanced Developer Tooling.](https://doi.org/10.1145/3759548.3763374)*  
  *17th ACM SIGPLAN International Workshop on Virtual Machines and Intermediate Languages (VMIL ’25), Singapore.*  

- **Burchell, H., Larose, O., & Marr, S. (2024).**  
  *[Towards Realistic Results for Instrumentation-Based Profilers for JIT-Compiled Systems.](https://doi.org/10.1145/3679007.3685058)*  
  *21st ACM SIGPLAN International Conference on Managed Programming Languages and Runtimes (MPLR ’24), Vienna.*  

➡️ [View all publications in KAR](https://kar.kent.ac.uk/102818/)

---

### 💬 Let’s Connect

If you’re interested in:
- Profilers and instrumentation  
- CPU sampling and performance analysis  
- Compiler-level slowdown  

Feel free to get in touch!

📫 **Email:** [humphreyburchell@gmail.com](mailto:humphreyburchell@gmail.com)

---

<p align="center">
  <sub>© 2026 Humphrey Burchell</sub>
</p>
