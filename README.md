# pretty-php-log

> A smart, colorful, real-time log tailer for messy PHP/Apache error logs.

`pretty-php-log` is a lightweight Bash utility to monitor your PHP logs in real time — with colorized syntax, array key and variable highlighting, multiline PHP warning support, keyword filtering, and emoji-friendly (or PuTTY-safe) output.

---

## ✨ Features

- 🎨 Colorized: warnings, variables, quoted keys, timestamps
- 🪓 Strip document root paths for clarity
- 🔍 Filter by keyword and PHP log level (warning, fatal, parse)
- 📎 Handles multiline `PHP message:` entries
- 💾 Save cleaned output to a file
- 🖥 PuTTY-safe (no emoji by default), emoji support optional

---

## 🚀 Installation

```bash
chmod +x pretty-php-log.sh
sudo mv pretty-php-log.sh /usr/local/bin/pretty-php-log
