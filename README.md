# 🧠 V8 & Chrome Exploitation Researcher  

![Profile Views](https://img.shields.io/badge/Profile%20Views-1000-blue?style=for-the-badge)
![V8 Internals Badge](https://img.shields.io/badge/V8-Internals-blue?style=for-the-badge)
![CVE Research Badge](https://img.shields.io/badge/CVE-Research-red?style=for-the-badge)

---

## 👨‍💻 About Me  

Hi, I'm windz3r0day — a vulnerability researcher focused on browser exploitation, especially within the V8 JavaScript engine and Chromium.  

I specialize in discovering and analyzing memory corruption, type confusion, and JIT compiler flaws across different V8 versions.  

- ⚙️ Focus: V8 internals, Chrome sandbox, JIT abuse, ASAN/LSAN/UBSAN debugging.  
- 📚 Skills: Reverse engineering, binary instrumentation, exploit development, fuzzing.  
- 🧩 Goal: Contribute to securing modern browsers by responsibly disclosing high-impact vulnerabilities.  

---

## 🧬 Key CVEs & Research  

| CVE ID          | Component           | Type                 | Status     |
|-----------------|---------------------|----------------------|------------|
| CVE-2025-6554 | V8 (JIT)            | Memory Leak + TC     | ✅ 0day (Found pre-disclosure) |

I analyze vulnerabilities using ASAN, LSAN, UBSAN, trace-opt/deopt, and internal V8 debugging tools.

---

## 🧪 Tools & Techniques  

- 🧠 Debugging: d8, --trace-opt, --trace-deopt, --allow-natives-syntax, %DebugPrint(), %HeapObjectVerify().  
- 🔬 Sanitizers: ASAN, LSAN, UBSAN  
- 🧰 Tools: GDB, Frida, custom JIT shell harnesses  
- 📦 Building: gclient, autoninja, gn gen, git checkout + sync pipelines  
- 🛠️ PoC Strategy: JIT warm-up, object shape manipulation, speculative optimization abuse  

---

## 💻 GitHub Stats  

<div align="center">  
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=windz3r0day&show_icons=true&theme=algolia&include_all_commits=true&count_private=true"/>  
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=windz3r0day&layout=compact&langs_count=7&theme=algolia"/>  
</div>  

---

## ☢️ Disclaimer  

All research and proofs-of-concept are shared for academic and educational purposes only. Misuse of this information is prohibited and discouraged.

---

⭐️ Check out my CVE proofs-of-concept, reverse engineering writeups, and browser internals research.  
📎 GitHub: [https://github.com/windz3r0day](https://github.com/windz3r0day)
