# rLocal-LLM-Pomelo_Portable

**(The package is in the releases: rLocal-LLM-Pomelo v0.1 Release, as rLocal-LLM-Pomelo_Portable.zip)**


This package provides a portable version of the **rLocal-LLM-Pomelo** Shiny application. The app is bundled with R-Portable so that users can run it without needing to install a full R environment. This version retains the functionality of the original app and is pre-configured for use on systems without a prior R installation.

The original **rLocal-LLM-Pomelo**:

https://github.com/yin4dev/rLocal-LLM-Pomelo.git


(This app is part of the **WakaCitrus-Informatics** series. For other apps in the **WakaCitrus-Informatics** series, please visit:　https://github.com/yin4dev?tab=repositories)

---

Welcome to **rLocal-LLM-Pomelo_Portable**! This packaged version allows users to run the Shiny application directly from a portable environment without needing to install R separately. Perfect for users who prefer plug-and-play solutions.

---

## Table of Contents
1. [Overview](#overview)
2. [Included Components](#included-components)
3. [System Requirements](#system-requirements)
4. [Setup and Running](#setup-and-running)
5. [Usage](#usage)
6. [Dependencies](#dependencies)
7. [License](#license)
8. [Acknowledgments](#acknowledgments)

---

## Overview

**rLocal-LLM-Pomelo Portable** is an intuitive R/Shiny application optimized for direct use from portable storage. It provides robust interactions with Local Large Language Models (LLMs) through a convenient, ready-to-use environment.

Key functionalities include:

- Multi-conversation management
- Document embeddings and retrieval-augmented generation (RAG)
- OCR support for image-based text extraction
- Integration with local LLM services (e.g., Ollama)

---

## Included Components

Upon extracting `rLocal-LLM-Pomelo.zip`, you'll find the following structure:

```
rLocal-LLM-Pomelo_Portable.zip
├── rLocal-LLM-Pomelo
│   ├── app.R
│   └── jpn.traineddata
│       
│
├── RunScripts
│   └── run_rLocal-LLM-Pomelo.R
│
├── R-Portable
│
├── LICENSE.txt
│
├── README.md
│
└── rLocal-LLM-Pomelo.bat
```

---

## System Requirements

- Windows OS
- Ollama installed and running
- At least 8GB RAM recommended
- Internet connection (for initial model downloads with Ollama)

---

## Setup and Running

### Step 1: Initial Setup

- Install [Ollama](https://www.ollama.com/) and download desired LLM models (e.g., `llama3.2:1b`, `llama3.2:3b`, `deepseek-r1:8b`).

### Step 2: Launching the Application

- Double-click the file `rLocal-LLM-Pomelo.bat` in the extracted folder.
- The Shiny app should launch automatically in your default web browser.

---

## Usage

### Multi-Conversation UI

- Create, manage, and delete multiple conversation sessions.
- Persistent storage of chat histories.

### File Upload & OCR

- Supported file formats: `.txt`, `.csv`, `.pdf`, `.doc/.docx`, `.png`, `.jpg`
- OCR via Tesseract is preconfigured (Japanese trained data included. If needed, please replace the Japanese data with other languge data).

### Retrieval-Augmented Generation (RAG)

- Embed and retrieve context-rich document data on-the-fly or from pre-embedded sources.
- Optional reranking and prompt construction for optimized results.

### Custom Assistant Profiles

- Select predefined personas such as Normal, Professional Data Analyst, Scientific Report Writer, etc.

---

## Dependencies

The portable edition includes R and essential packages pre-installed:

- `shiny`, `shinyBS`, `shinyjs`, `httr`, `jsonlite`, `pdftools`, `readtext`, `tools`, `RSQLite`, `DBI`, `curl`, `tesseract`, `magick`, `base64enc`, `rollama`

Additionally, Ollama and Tesseract OCR must be installed separately.

---

## License

This project is licensed under the GNU General Public License v3.0 (GPL-3.0).

Copyright (C) 2025 Hongrong Yin

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

---

## Acknowledgments

Special thanks to my loving Aimi Yago for her continuous support, inspiration, and contributions to this project's success! 🎉

