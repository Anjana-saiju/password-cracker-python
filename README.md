# Multi-Threaded Hash Cracker in Python
**By Inlighn Tech (Anjana Saiju)**

## One-line summary
Educational Python tool to demonstrate dictionary and brute-force password cracking on hashed values using multithreading and progress bars.

---

## Overview
This repository contains a teaching-focused hash cracker that supports multiple hash algorithms (MD5, SHA1, SHA2, SHA3, SHA512). It demonstrates dictionary attacks and brute-force generation, and uses `concurrent.futures` for parallelism and `tqdm` for progress visualization.

> ⚖️ **Ethical use only:** This project is for learning, research, and defensive purposes. Do **not** use it to attack systems you do not own or for which you do not have explicit written permission.

---

## Features
- Dictionary attack (wordlist)
- Brute-force attack with configurable charset and length range
- Multiple hash algorithms supported (`md5`, `sha1`, `sha256`, `sha3_256`, etc.)
- Multithreaded execution (configurable `--max_workers`)
- Progress bars with `tqdm`

---

## Prerequisites
- Python 3.8 or higher
- Install `tqdm`:
  
pip install tqdm

