# 🌲 Cyber Forest CTF Challenge  

![Cyber Forest Banner](https://media.giphy.com/media/26AHONQ79FdWZhAI0/giphy.gif)  

Welcome to the **Cyber Forest CTF**!  
A hacker-themed filesystem exploration game where you must find **three hidden flags** and avoid malicious traps.  

---

## 🎮 Challenge Overview
> You are a **cyber explorer** lost in a digital forest.  
> Navigate the maze of files, uncover **3 flags**, and beware of **infected traps** that disable your terminal for 10 seconds!  

⚠️ **Malicious files detected in `Downloads/` and `bin/` directories**  
![Warning Animation](https://media.giphy.com/media/26xBukh9bQqny71Yw/giphy.gif)  

---

## 🚀 How to Play
🔗 **Start here:** [Cyber Forest CTF](https://cyber-forest-ctf.vercel.app/)  

### Available Commands
| Command | Example | Description |
|---------|---------|-------------|
| `ls`    | `ls Documents/` | Lists files in the current directory |
| `cd`    | `cd Documents/` | Changes directory |
| `cat`   | `cat note.txt` | Displays file contents |
| `file`  | `file mystery.exe` | Reveals the file type |
| `clear` | `clear` | Clears the screen |
| `help`  | `help` | Shows available commands |

---

## 🏁 The Flags
There are **3 hidden flags** shaped like `CTF{...}`  

📍 **Flag 1** → Hidden in a file most people ignore  
💡 *Hint: Use `ls -a` to reveal hidden files*  

📍 **Flag 2** → In a place where documents are stored  
💡 *Hint: Explore `Documents/` carefully*  

📍 **Flag 3** → Hidden within an image’s metadata  
💡 *Hint: Use the right tools (`file`, `exiftool`, etc.)*  

![Flag Animation](https://media.giphy.com/media/3oEjHYl4R5UuDmp6ko/giphy.gif)  

---

## ⚡ Avoiding Traps
- ⚠️ Don’t open random files in **Downloads/** or **bin/**  
- ✅ Use `file <filename>` before `cat`  

> 💡 **Pro Tip:** Think like a hacker — where would *you* hide something valuable?  

---

## 🔍 Example Exploration
```bash
$ ls -a
.  ..  .hidden_file  Documents  Downloads

$ file .hidden_file
.hidden_file: ASCII text

$ cat .hidden_file
CTF{hidden_in_plain_sight}
