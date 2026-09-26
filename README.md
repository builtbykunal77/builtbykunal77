<p align="center">
<img src="https://raw.githubusercontent.com/builtbykunal77/builtbykunal77/main/banner.svg" width="100%" alt="Kunal Rajput — learning C++ and Swift. Build. Break. Understand. Repeat." />
</p>
<p align="center"><b>CURIOSITY → CODE → SMALL WINS</b><br/><sub>C++ learner · Swift explorer · Developer in the making</sub></p>

---

### 👋 Player one

I’m **Kunal Rajput**. I’m learning **C++ and Swift**, starting with the fundamentals and working toward small projects I can understand, explain, and improve.

This is where I share that journey: the experiments, the bugs, and the moments when it finally clicks.

> **The goal:** write a little better code than yesterday.

### ⚡ Quest log

<table>
<tr><td width="50%" valign="top">

**01 / C++ FOUNDATIONS**

My current learning focus: logic, loops, functions, and problem-solving.

`Learn → Practice → Debug`

</td><td width="50%" valign="top">

**02 / EXPLORING SWIFT**

Getting comfortable with Swift syntax and taking the first steps toward building apps.

`Explore → Experiment → Understand`

</td></tr>
</table>

<details>
<summary><b>🗺️ Open my next-level roadmap</b></summary>

- [ ] Build a small C++ console project.
- [ ] Write and explain my own Swift practice programs.
- [ ] Learn Git basics: commits, branches, and pull requests.
- [ ] Publish a project with clear setup instructions.

These are goals, not completed milestones. One step at a time.

</details>

### 🎮 The debug arcade

**LEVEL 01 · SPOT THE BUG**  
A tiny challenge for anyone passing through. Pick an answer to reveal the result.

```cpp
int score = 7;
if (score = 10) {
    std::cout << "Level unlocked!";
}
```

**Why does this print `Level unlocked!` even though the score started at 7?**

<details>
<summary>🅰️ The condition compares 7 with 10</summary>

**Try again.** Equality comparison in C++ uses `==`. Look closely at the operator in the condition.

</details>
<details>
<summary>🅱️ The condition assigns 10 to score</summary>

**LEVEL CLEARED! 🎉** `=` assigns `10` to `score`. The nonzero result is treated as `true`, so the message prints. Use `if (score == 10)` to compare instead.

</details>
<details>
<summary>🅲️ std::cout changes the score</summary>

**Try again.** `std::cout` only prints the message here. The assignment happens before the body runs.

</details>

---

<p align="center"><b>Small programs. Real understanding. Steady progress.</b><br/><sub>Thanks for stopping by — the next chapter is being written.</sub></p>
