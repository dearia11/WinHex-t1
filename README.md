# 🕵️‍♀️ Digital Forensics Project – WinHex MFT Analysis

## 🔍 Project Overview
This project focuses on basic digital forensic analysis using **WinHex**, a hex editor and disk tool. The objective was to understand how the **Master File Table (MFT)** works in NTFS file systems and to analyze metadata of a created file.

## 🎯 Goals
- Locate the **MFT (Master File Table)** on a disk image.
- Identify and interpret **date and time values** in file metadata.
- Detect and recover **deleted file fragments** from the MFT record.

## 🛠️ Tools & Environment
- **WinHex** – used to view and analyze disk sectors, metadata, and hex values.
- Windows virtual machine – test environment for file creation and deletion.

## 📁 What I Did
1. Created a test file on the virtual disk.
2. Used WinHex to find the **MFT entry** corresponding to that file.
3. Interpreted the metadata fields such as **Created**, **Modified**, and **Accessed** timestamps.
4. Simulated file deletion and located the remnants of the MFT record for that deleted file.

## 🧠 Skills & Learning Outcomes
- Introduction to **hex analysis** and **disk structure**.
- Understanding **NTFS file system** and how metadata is stored.
- Hands-on use of **forensic tools** to detect and recover deleted data.
- Improved skills in **digital investigation** and **technical documentation**.


