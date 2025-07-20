# Predictive Search System

## Description

The **Predictive Search System** is a simple C-based application that provides real-time word suggestions as a user types input. It uses a **Trie (Prefix Tree)** data structure for efficient insertion and lookup of words. The system reads a list of words from a text file and builds a Trie to support fast and accurate **auto-completion**.

This project is a demonstration of how basic data structures can be applied to build intelligent search features, commonly found in search engines, text editors, and command-line tools.

---

## Features

- Built using **C language**
- Implements **Trie data structure**
- **Fast prefix-based suggestions**
- **Word list is loaded from an external file**
- Case-insensitive search (optional)
- Lightweight and console-based

---

## How It Works

1. The program reads words from a file (e.g., `words.txt`)
2. Each word is inserted into a Trie
3. The user types a prefix in the console
4. The program suggests all possible words that begin with that prefix

---

## File Structure


---

## Sample `words.txt`


---

## Compilation & Running

### Using GCC

```bash
gcc main.c trie.c -o predictive_search
./predictive_search

Enter prefix: ap
Suggestions:
- apple
- application
- apply

Enter prefix: ba
Suggestions:
- bat
- battle
- banana


