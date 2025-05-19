# CITS4407-open-source

This repository contains three Shell scripts developed for the CITS4407 course, focused on data processing and analysis. These scripts primarily address file processing, data cleaning, and statistical analysis.

## Tools Overview

### 1. Data Integrity Checker

#### Setup

```bash
chmod +x empty_cells
```

#### Execute

```bash
./empty_cells <input_file>
```

#### Sample

```bash
./empty_cells sample.tsv
```

This script analyzes semicolon-delimited data files and reports the number of empty values in each column.

### 2. Data Cleaner

#### Setup

```bash
chmod +x preprocess
```

#### Execute

```bash
./preprocess <input_file>
```

#### Sample

```bash
./preprocess sample.tsv
```

This script performs multiple cleaning operations on semicolon-delimited data files to make them more suitable for analysis.

### 3. Board Game Data Analyzer

#### Setup

```bash
chmod +x analysis
```

#### Execute

```bash
./analysis <input_file>
```

#### Sample

```bash
./analysis sample.tsv
```

This script is designed to analyze board game datasets and provide various statistical insights.

## Requirements

- Bash Shell environment (Linux/Unix/macOS or Windows WSL)
- Basic Unix tools: `awk`, `sed`, `tr`, `sort`, `uniq`
- Appropriate permissions for input files (readable)

## Author

Name: Yehao Chen  
Student ID: 23985897