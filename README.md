# Hi there, I'm Bhawana Singh 👋

### Computer Science Student • Full-Stack Developer • Competitive Programmer

I'm a ** B.Tech Computer Science student** passionate about building web applications, solving algorithmic problems, and exploring modern software technologies. I enjoy learning by building projects and continuously improving my problem-solving skills.

---

## 🚀 About Me

- 💻 Building full-stack web applications with the MERN stack
- 🌱 Currently learning AI-powered applications and modern web technologies
- 🧩 Regularly solving Data Structures & Algorithms problems
- 🎯 Always exploring new technologies and best practices

---

## 🛠️ Tech Stack

**Languages**

`C++` `JavaScript` `Python` `HTML` `CSS`

**Frameworks & Technologies**

`React` `Node.js` `Express.js` `MongoDB` `RAG`

**Tools**

`Git` `GitHub` `VS Code`

---

## 🏆 Competitive Programming

- **Codeforces:** [bhawana83](https://codeforces.com/profile/bhawana83)
- **LeetCode:** [Bhawana83](https://leetcode.com/Bhawana83)
- Passionate about improving problem-solving and algorithmic thinking.

---

## 📌 Featured Projects

### 📚 Book Store Analyst
Python • BeautifulSoup • Pandas

A data analysis project that collects, cleans, and analyzes book data to uncover pricing trends and useful insights.


---
## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Bhawana83&show_icons=true&theme=github_dark&hide_border=true&rank_icon=github" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Bhawana83&layout=compact&theme=github_dark&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=Bhawana83&theme=github-dark-blue&hide_border=true" />
</p>


---

## 🤝 Connect with Me

- 📧 **Email:** bhawanasingh8318@gmail.com
- 💼 **LinkedIn:** *(https://www.linkedin.com/in/bhawana-singh-80826a32a?utm_source=share_via&utm_content=profile&utm_medium=member_ios)*

---


<details>
<summary><b>📖 Read my latest essay: The Ultimate Plot Twist in My 1-Year DSA Journey</b></summary>
<br>

# 🚀 The Ultimate Plot Twist in My 1-Year DSA Journey: Taming the Enemy

> 💡 **A Quick Reflection on the Placement Grind**
> After nearly a year of grinding Data Structures and Algorithms (DSA), solving hundreds of problems, and staring down competitive programming screens, I had a realization this week that completely blew my mind. 

If you are a computer science student or a developer prepping for placements, you’ll know exactly how this story starts.

---

## 🛑 Day 1: The Nightmare of the TLE

Think back to the very beginning of your coding journey. You sit down, tackle a problem, and write a functional solution using nested loops. You hit submit, feeling invincible, only for the screen to flash a bright, red error: `TLE (Time Limit Exceeded)`.

From that day on, you are told that nested loops are the ultimate enemy. Your professors, seniors, and every YouTube tutorial tell you to run away from them. 

So, you go down the rabbit hole. For months, you stretch your brain to master **Two Pointers**, **Sliding Windows**, **Binary Search**, and complex **Recursion trees**. You learn how to avoid the "naive" brute-force approach at all costs. 

But then, you finally reach the final boss of interview preparation: **Dynamic Programming (DP).**

You look at a Bottom-Up Tabulation solution for the first time, and your jaw drops. What is staring back at you? **Nested loops.** 

---

## 🌀 The Illusion of the Flat Circle

When I first noticed this, I felt like I was the punchline of a massive cosmic joke. I spent a whole year running away from nested loops, only to find them waiting for me at the finish line! It felt like a complete, frustrating circle. 

But as I sat with my code, I realized it’s not a circle at all. **It’s a spiral.** I was standing at the same coordinates, but at a much higher level. 

There is a world of difference between the loops you write on Day 1 and the loops you write in DP:

| Execution State | Beginner Nested Loops | Bottom-Up DP Loops |
| :--- | :--- | :--- |
| **Logic Type** | Blind Brute Force | Intelligent State Machine |
| **Time Complexity** | O(N²) recalculating every branch | O(N × W) utilizing constant-time O(1) math |
| **Memory Control** | Blindly thrashing the stack | Systematic, predictive memory access |

```cpp
// A DP nested loop looks backward to grab a pre-calculated answer instantly
for(int i = 1; i <= items; i++) {
    for(int w = 1; w <= capacity; w++) {
        dp[i][w] = max(val[i-1] + dp[i-1][w-wt[i-1]], dp[i-1][w]);
    }
}


⛰️ Standing at the Peak
Mastering DP feels like the ultimate milestone because it forces you to conquer
 the core trade-off of computer science: balancing Time and Memory.
 You have to understand recursion, arrays, and even how the computer manages its
 tiny Stack memory versus the massive RAM warehouse to
 keep your code from crashing.

Looking back at my last year of coding, I’m proud of how far the logic has evolved.
 I went from writing uncontrolled code that triggered
 TLEs to building fast, deterministic state machines.

If you are currently in the thick of the placement grind and
 feel like you're going in circles—hang in there.
Look closer at your code.
You aren't where you started; you're just leveling up to beat
the final boss.

Let's keep grinding! 🚀
