# 🎼 awk-symphony

> *In the silence of the shell, a symphony begins—  
> each line a note, each field a rhythm.  
> With `awk`, we compose clarity from chaos.*  

---

## 🎯 Overview

**awk-symphony** is a Bash-powered project that uses the `awk` command to extract and harmonize data from CSV files.  
It’s a minimalist toolkit for learning, experimenting, and orchestrating structured text in the terminal.

---

## 📁 Files

- `mainfile.txt` — sample CSV-like data
- `extract.sh` — Bash script using `awk` to parse fields

---

## 🧪 Sample Command

### Input

```code
Ali,25,Tehran
Sara,30,Shiraz
Mehdi,22,Isfahan
```
### output

```code
Ali Tehran  
Sara Shiraz  
Mehdi Isfahan
```
##🚀 Usage
1. colne the repo:
```bash
git clone https://github.com/yourusername/awk-symphony.git
cd awk-symphony
```
2. Run thecommand:
```bash
awk -F, '{print $1, $3}' mainfile.txt
```
## 🛠️ Requirements
* Ubuntu or any Unix-like OS
* bash shell
* `awk` installed (usually pre-installed)

## 🎓 Learn More
you can use W3school or ...

## 👤 Author
YoungKoorosh
