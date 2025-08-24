# 🌲 Welcome to the Cyber Forest CTF Challenge! 🌲
![Uploading Lucid_Origin_A_fullbody_shot_of_a_confident_stylish_elite_male_0.jpg…]()

## 🎯 Your Mission

You are a cyber explorer lost in a digital forest. Your goal is to navigate through a complex filesystem and find **four hidden flags**. But beware: this forest is full of traps! Some files are malicious and will temporarily disable your terminal if you open them.

**Can you find all the flags without getting infected?**

---

## 🕹️ How to Play

1.  **Click on the website link** provided by your instructor to start the challenge.
2.  You will see a **terminal interface** in your web browser.
3.  Use the following commands to explore the filesystem:

| Command | Example | What it does |
| :--- | :--- | :--- |
| `ls` | `ls` or `ls Documents/` | Lists files in the current (or specified) directory |
| `cd` | `cd Documents/` | Changes to a different directory |
| `cat` | `cat note.txt` | Displays the contents of a file |
| `file` | `file mystery.exe` | Reveals the true type of a file |
| `clear` | `clear` | Clears your terminal screen |
| `help` | `help` | Shows available commands |
| `unzip` | `unzip file.zip` | Extract archive contents (unlocked during gameplay) |
| `decrypt` | `decrypt file.txt` | Decrypt protected files (unlocked during gameplay) |

---

## 🏁 The Flags

There are **four flags** hidden in the system. Each flag is a string that looks like this: **`CTF{something_here}`**.

*   **Flag 1:** Hidden in a file most people ignore.
*   **Flag 2:** In a place where documents are stored.
*   **Flag 3:** Hidden within metadata.
*   **Flag 4:** Protected by encryption (requires multiple steps to unlock)

The scoreboard at the bottom of the screen will track your progress.

---

## 🏆 Leaderboard & Competition

Compete against other players for the top spot on the leaderboard! Your score is calculated based on:

- **250 points** for each flag found
- **Time bonus** for faster completion (up to 1000 points)
- **Total score** = (Flags × 250) + (1000 - time/2)

The leaderboard displays the top players with their completion times and scores.

---

## ☠️ WARNING: Traps!

Some files are **malicious**! If you open them, your terminal will be **disabled for 10 seconds** and you'll see a scary (but harmless) virus animation.

*   **Think before you `cat`!** Always use the `file` command first to check what type of file you're dealing with.
*   Be especially careful with files in the `Downloads/` and `bin/` directories.
*   Files with `.exe` extension might be dangerous!

---

## 🔓 Advanced Challenges

This CTF includes advanced challenges that require multiple steps:

1.  **ZIP Extraction**: Find and extract a password-protected archive
2.  **Decryption**: Use a discovered password to decrypt the final flag
3.  **Command Unlocking**: Some commands are only available after finding specific files

---

## 🆘 Need Help?

If you get stuck, try these strategies:
1.  Use `ls -a` to see hidden files (those starting with a `.`)
2.  Explore deeply nested directories - some flags are buried deep
3.  The `file` command is your best friend for avoiding traps
4.  Check file contents carefully - some contain hints for other flags
5.  Look for patterns - flags are often in predictable locations

**Pro Tip:** The fourth flag requires you to find a ZIP file, extract it, read the instructions, and then decrypt the final flag.

**Remember:** This is a simulation. No real systems are being harmed.

---

## 📊 After Completing

When you find all four flags:
1.  Enter your name to submit your score to the leaderboard
2.  Compare your time with other players
3.  Try to improve your time for a better score!

---

Good luck, explorer! The forest awaits... 🌲💻

**Live Challenge:** 🌐 [Play Now](https://cyber-forest-ctf-chapter-02.vercel.app/)  
**Source Code:** 💻 [GitHub Repository](https://github.com/SERGEON-network/cyber-forest-ctf-chapter-02/edit/main/README.md)
