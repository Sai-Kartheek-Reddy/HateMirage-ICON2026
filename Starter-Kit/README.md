# HateMirage ICON 2026 Shared Task — Starter Kit

This repository contains the **starter kit for the HateMirage ICON 2026 Shared Task**.

The starter kit provides sample data, baseline implementations, RAG reference resources, and documentation to help participants understand the task and begin developing their systems.

---

## Repository Structure

```text
HateMirage-ICON2026/
│
├── code/
│   ├── README.md
│   ├── zero_shot.py
│   └── rag.py
│
├── source_docs/
│   ├── RAG_Reference_Data.jsonl
│   └── fake_claims.txt
│
├── sample-data.xlsx
│
├── README.md
│
└── requirements.txt
```

# Sample Data

This directory contains a sample dataset provided as part of the HateMirage shared task starter kit.

## File

- `sample-data.xlsx` - Sample data provided to help participants understand the input data format and the annotation structure.

## Data Format

Each record contains the following columns:

| Column | Description |
|--------|-------------|
| `Index` | A unique identifier for each comment. |
| `Comments` | The raw comment translated into English using ChatGPT-4. |
| `Target` | Identifies the group or individual affected by the comment. |
| `Intent` | Describes the underlying motivation or purpose behind the comment. |
| `Implication` | Explains the potential social impact of the comment. |

## Column Details

### 1. Index

A unique identifier assigned to each comment.

### 2. Comments

The original comment translated into English using ChatGPT-4.

### 3. Target

Identifies the group or individual affected by the comment.

### 4. Intent

Describes the underlying motivation or purpose behind the comment.

### 5. Implication

Explains the potential social impact of the comment.
