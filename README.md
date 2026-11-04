<div align="center">

# Praveen 👋

*Debugging systems that break under pressure, one cache miss at a time.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/praveen-tmr)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tmrpraveen2005@gmail.com)

</div>

---

I like knowing why things are slow. Most of my projects started with a question like "where does the time actually go?" and ended with me reading way more kernel docs than I planned to.

Right now I'm poking at memory management in distributed query engines, lock-free data structures, and whether LLMs can be made to admit when they don't know something.

---

### 🔧 Things I've built

**[Limit Order Book](https://github.com/TMR2005/Limit-Order-Book)**: a C++17 matching engine that does ~9.8M orders/sec. Got there by deleting every heap allocation from the hot path and arguing with `std::map` until it gave up.

**[Elekki](https://github.com/TMR2005)**: an online Verilog judge. Throw 1000 untrusted submissions at it and it still resolves all of them. Docker workers do the scary part.

**[MLinux](https://github.com/TMR2005)**: a telemetry daemon that reads `/proc` and `/sys` directly, so it stays under 2% CPU. Useful for figuring out whether your GPU is actually the bottleneck or just the excuse.

**[Smart Compiler](https://github.com/TMR2005/AI-Augumented-Smart-Compiler)**: MiniC to MIPS, with an LLM that rewrites three-address code when register pressure gets ugly.

**[Brain Tumor Segmentation](https://github.com/TMR2005/Multimodal-Fusion-for-Medical-Image-Segmentation)**: MRI plus radiology text through a vision-language model. 0.87 Dice, which I'm still a little proud of.

---

### 🏁 Off-hours

Competitive programming. Codeforces peak of 1514, and a few hundred problems across Codeforces, LeetCode, and AtCoder. Mostly because I like the moment a solution clicks.

---

### 📊 

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=TMR2005&show_icons=true&theme=algolia&hide_border=true" alt="GitHub Stats" height="170"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=TMR2005&layout=compact&theme=algolia&hide_border=true&langs_count=8" alt="Top Languages" height="170"/>
</div>

---

Say hi if you want to talk about caches, compilers, or why your queue is full at 3 AM.
