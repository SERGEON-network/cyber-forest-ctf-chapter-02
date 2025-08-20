# README Document for Cyber Forest CTF

I'll create a clean, professional README document for your CTF challenge that you can copy and paste directly into a GitHub repository.

html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cyber Forest CTF - README</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;
            line-height: 1.6;
            color: #24292e;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        
        h1, h2, h3 {
            color: #2c3e50;
            margin-top: 1.5em;
            margin-bottom: 0.5em;
        }
        
        h1 {
            font-size: 2em;
            padding-bottom: 0.3em;
            border-bottom: 1px solid #eaecef;
        }
        
        h2 {
            font-size: 1.5em;
            padding-bottom: 0.3em;
            border-bottom: 1px solid #eaecef;
        }
        
        h3 {
            font-size: 1.25em;
        }
        
        code {
            background-color: rgba(27,31,35,0.05);
            border-radius: 3px;
            font-size: 85%;
            margin: 0;
            padding: 0.2em 0.4em;
            font-family: SFMono-Regular, Consolas, 'Liberation Mono', Menlo, monospace;
        }
        
        pre {
            background-color: #f6f8fa;
            border-radius: 3px;
            font-size: 85%;
            line-height: 1.45;
            overflow: auto;
            padding: 16px;
        }
        
        pre code {
            background-color: transparent;
            padding: 0;
        }
        
        blockquote {
            border-left: 0.25em solid #dfe2e5;
            color: #6a737d;
            padding: 0 1em;
            margin-left: 0;
        }
        
        ul, ol {
            padding-left: 2em;
        }
        
        li {
            margin-bottom: 0.5em;
        }
        
        a {
            color: #0366d6;
            text-decoration: none;
        }
        
        a:hover {
            text-decoration: underline;
        }
        
        .header {
            text-align: center;
            margin-bottom: 2em;
        }
        
        .badges {
            margin: 1em 0;
        }
        
        .badge {
            display: inline-block;
            padding: 3px 6px;
            font-size: 12px;
            font-weight: 600;
            line-height: 1;
            color: #fff;
            background-color: #6c757d;
            border-radius: 2em;
            margin-right: 0.5em;
        }
        
        .badge-ctf {
            background-color: #28a745;
        }
        
        .badge-web {
            background-color: #17a2b8;
        }
        
        .badge-terminal {
            background-color: #6f42c1;
        }
        
        .warning {
            background-color: #fff3cd;
            border: 1px solid #ffeaa7;
            border-left: 4px solid #fdcb6e;
            padding: 16px;
            margin: 1em 0;
            border-radius: 4px;
        }
        
        .tip {
            background-color: #d1ecf1;
            border: 1px solid #bee5eb;
            border-left: 4px solid #0c5460;
            padding: 16px;
            margin: 1em 0;
            border-radius: 4px;
        }
        
        .command {
            background-color: #2d3748;
            color: #e2e8f0;
            padding: 12px 16px;
            border-radius: 4px;
            margin: 1em 0;
            font-family: SFMono-Regular, Consolas, 'Liberation Mono', Menlo, monospace;
        }
        
        .flag {
            background-color: #f8f9fa;
            border: 1px solid #e1e4e8;
            padding: 16px;
            margin: 1em 0;
            border-radius: 6px;
        }
        
        .flag-title {
            font-weight: 600;
            margin-bottom: 8px;
        }
        
        .flag-content {
            font-family: SFMono-Regular, Consolas, 'Liberation Mono', Menlo, monospace;
            color: #032f62;
        }
        
        .footer {
            margin-top: 2em;
            padding-top: 1em;
            border-top: 1px solid #eaecef;
            color: #6a737d;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>🌲 Cyber Forest CTF Challenge</h1>
        <div class="badges">
            <span class="badge badge-ctf">CTF</span>
            <span class="badge badge-web">Web-based</span>
            <span class="badge badge-terminal">Terminal</span>
        </div>
        <p>Navigate through a digital filesystem, find hidden flags, and avoid malicious files!</p>
    </div>

    <h2>📋 Challenge Overview</h2>
    <p>You are a cyber explorer lost in a digital forest. Your goal is to navigate through a maze of files and find three hidden flags. But beware: this forest is full of traps! Some files are malicious and will temporarily disable your terminal if you open them.</p>

    <div class="warning">
        <strong>⚠️ WARNING:</strong> Some files are malicious! If you open them, your terminal will be disabled for 10 seconds and you'll see a scary (but harmless) virus animation.
    </div>

    <h2>🎮 How to Play</h2>
    <p>Click on the website link provided by your instructor to start the challenge. You will see a terminal interface in your web browser.</p>

    <h3>Available Commands:</h3>
    <ul>
        <li><code>ls</code> - Lists files in the current or specified directory</li>
        <li><code>cd</code> - Changes to a different directory</li>
        <li><code>cat</code> - Displays the contents of a file</li>
        <li><code>file</code> - Reveals the true type of a file</li>
        <li><code>clear</code> - Clears your terminal screen</li>
        <li><code>help</code> - Shows available commands</li>
    </ul>

    <h2>🏁 The Flags</h2>
    <p>There are three flags hidden in the system. Each flag is a string that looks like this: <code>CTF{something_here}</code>.</p>

    <div class="flag">
        <div class="flag-title">Flag 1</div>
        <div class="flag-content">Hidden in a file most people ignore.</div>
        <p><em>Hint: Look for hidden files!</em></p>
    </div>

    <div class="flag">
        <div class="flag-title">Flag 2</div>
        <div class="flag-content">In a place where documents are stored.</div>
        <p><em>Hint: Check common document directories!</em></p>
    </div>

    <div class="flag">
        <div class="flag-title">Flag 3</div>
        <div class="flag-content">Hidden within an image's metadata.</div>
        <p><em>Hint: Use the right tools to examine files!</em></p>
    </div>

    <h2>⚠️ Avoiding Traps</h2>
    <p>Be careful with files in the <code>Downloads/</code> and <code>bin/</code> directories. These are more likely to contain malicious files.</p>

    <div class="tip">
        <strong>💡 Pro Tip:</strong> Use the <code>file</code> command before opening any file to check what type of file you're dealing with.
    </div>

    <h2>🏆 Winning the Challenge</h2>
    <p>The first player to find all three flags wins! The challenge tracks your completion time.</p>

    <div class="tip">
        <strong>💡 Pro Tip:</strong> The flags are not always in obvious places. Look for hidden files and think about where you might hide something valuable.
    </div>

    <h2>🆘 Need Help?</h2>
    <p>If you get stuck, try these strategies:</p>
    <ul>
        <li>Use <code>ls -a</code> to see hidden files (those starting with a <code>.</code>)</li>
        <li>The <code>file</code> command is your best friend for avoiding traps</li>
        <li>Check everywhere—even where it seems obvious</li>
        <li>Remember: This is a simulation. No real systems are being harmed.</li>
    </ul>

    <h3>Example Exploration:</h3>
    <pre><code>$ ls -a
. .. .hidden_file Documents Downloads

$ file .hidden_file
.hidden_file: ASCII text

$ cat .hidden_file
CTF{hidden_in_plain_sight}</code></pre>

    <h2>🚀 Getting Started</h2>
    <p>To play the Cyber Forest CTF challenge:</p>
    <ol>
        <li>Visit the challenge website</li>
        <li>Read the instructions carefully</li>
        <li>Start exploring the filesystem using the available commands</li>
        <li>Find all three flags as quickly as possible</li>
        <li>Avoid malicious files that will disable your terminal</li>
    </ol>

    <div class="footer">
        <p>Cyber Forest CTF Challenge &copy; 2023 | Good luck, explorer! The forest awaits... 🌲💻</p>
    </div>

    <script>
        // Make code blocks copyable
        document.querySelectorAll('pre').forEach((pre) => {
            pre.addEventListener('click', () => {
                const range = document.createRange();
                range.selectNode(pre);
                window.getSelection().removeAllRanges();
                window.getSelection().addRange(range);
                
                try {
                    const successful = document.execCommand('copy');
                    const msg = successful ? 'Copied!' : 'Failed to copy';
                    console.log(msg);
                } catch (err) {
                    console.error('Failed to copy: ', err);
                }
                
                window.getSelection().removeAllRanges();
            });
        });
    </script>
</body>
</html>


## How to Use This README

1. Copy the entire HTML code above
2. Create a new file named `README.md` in your GitHub repository
3. Paste the following Markdown content into that file:

markdown
# 🌲 Cyber Forest CTF Challenge

> Navigate through a digital filesystem, find hidden flags, and avoid malicious files!

## 📋 Challenge Overview

You are a cyber explorer lost in a digital forest. Your goal is to navigate through a maze of files and find three hidden flags. But beware: this forest is full of traps! Some files are malicious and will temporarily disable your terminal if you open them.

> **⚠️ WARNING:** Some files are malicious! If you open them, your terminal will be disabled for 10 seconds and you'll see a scary (but harmless) virus animation.

## 🎮 How to Play

Click on the website link provided by your instructor to start the challenge. You will see a terminal interface in your web browser.

### Available Commands:

- `ls` - Lists files in the current or specified directory
- `cd` - Changes to a different directory
- `cat` - Displays the contents of a file
- `file` - Reveals the true type of a file
- `clear` - Clears your terminal screen
- `help` - Shows available commands

## 🏁 The Flags

There are three flags hidden in the system. Each flag is a string that looks like this: `CTF{something_here}`.

**Flag 1**
Hidden in a file most people ignore.

*Hint: Look for hidden files!*

**Flag 2**
In a place where documents are stored.

*Hint: Check common document directories!*

**Flag 3**
Hidden within an image's metadata.

*Hint: Use the right tools to examine files!*

## ⚠️ Avoiding Traps

Be careful with files in the `Downloads/` and `bin/` directories. These are more likely to contain malicious files.

> **💡 Pro Tip:** Use the `file` command before opening any file to check what type of file you're dealing with.

## 🏆 Winning the Challenge

The first player to find all three flags wins! The challenge tracks your completion time.

> **💡 Pro Tip:** The flags are not always in obvious places. Look for hidden files and think about where you might hide something valuable.

## 🆘 Need Help?

If you get stuck, try these strategies:

- Use ls -a to see hidden files (those starting with a .)
- The file command is your best friend for avoiding traps
- Check everywhere—even where it seems obvious
- Remember: This is a simulation. No real systems are being harmed.

### Example Exploration:

$ ls -a
. .. .hidden_file Documents Downloads

$ file .hidden_file
.hidden_file: ASCII text

$ cat .hidden_file
CTF{hidden_in_plain_sight}


## 🚀 Getting Started

To play the Cyber Forest CTF challenge:

1. Visit the challenge website
2. Read the instructions carefully
3. Start exploring the filesystem using the available commands
4. Find all three flags as quickly as possible
5. Avoid malicious files that will disable your terminal



Cyber Forest CTF Challenge &copy; 2023 | Good luck, explorer! The forest awaits... 🌲💻


This Markdown version will render properly on GitHub and provides all the necessary information about your CTF challenge in a clean, readable format.
