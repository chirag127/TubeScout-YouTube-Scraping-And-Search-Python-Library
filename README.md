# TubeScout-YouTube-Scraping-And-Search-Python-Library

[![Build Status](https://img.shields.io/github/actions/workflow/user/chirag127/TubeScout-YouTube-Scraping-And-Search-Python-Library/ci.yml?style=flat-square&logo=github)](https://github.com/chirag127/TubeScout-YouTube-Scraping-And-Search-Python-Library/actions/workflows/ci.yml)
[![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/TubeScout-YouTube-Scraping-And-Search-Python-Library?style=flat-square&logo=codecov)](https://codecov.io/gh/chirag127/TubeScout-YouTube-Scraping-And-Search-Python-Library)
[![Python Version](https://img.shields.io/badge/Python-3.10%2B-blue?style=flat-square&logo=python)](https://www.python.org/)
[![Linting](https://img.shields.io/badge/Linting-Ruff-009722?style=flat-square&logo=ruff)](https://github.com/astral-sh/ruff)
[![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey?style=flat-square&logo=creativecommons)](https://creativecommons.org/licenses/by-nc/4.0/)
[![GitHub Stars](https://img.shields.io/github/stars/chirag127/TubeScout-YouTube-Scraping-And-Search-Python-Library?style=flat-square&logo=github)](https://github.com/chirag127/TubeScout-YouTube-Scraping-And-Search-Python-Library)

<br>

**TubeScout** is a Python library designed for unauthenticated YouTube data retrieval, enabling the scraping of search results, video details, playlists, and channel information without relying on the official YouTube API. This project is archived and no longer maintained.

## 🚀 About TubeScout

TubeScout provides a robust, albeit unofficial, method to interface with YouTube's public data. It allows developers to programmatically search for content, extract metadata from videos and playlists, and gather information about YouTube channels. Due to its reliance on web scraping, it is susceptible to YouTube's UI changes and is archived as such.

## 🏛️ Architecture

TubeScout follows a **Modular Monolith** architecture, ensuring clear separation of concerns and maintainability for a Python library.

mermaid
graph TD
    A[CLI Interface] --> B(Search Service)
    B --> C(Scraping Engine)
    B --> D(Parser Service)
    C --> E[YouTube Web Interface]
    D --> F(Data Models)
    D --> G(Cache Service)
    G --> H[Local Storage]


## 📋 Table of Contents

*   [About TubeScout](#-about-tubescout)
*   [Architecture](#-architecture)
*   [Table of Contents](#-table-of-contents)
*   [Key Features](#key-features)
*   [Development Setup](#development-setup)
*   [Usage](#usage)
*   [Testing](#testing)
*   [Contributing](#contributing)
*   [License](#license)
*   [Disclaimer](#disclaimer)
*   [AI Agent Directives](#ai-agent-directives)

## ✨ Key Features

*   **Unauthenticated YouTube Search:** Scrape video results based on keywords.
*   **Video Metadata Extraction:** Retrieve title, description, views, likes, etc.
*   **Playlist Data Retrieval:** Fetch video lists and details within playlists.
*   **Channel Information:** Scrape subscriber counts, video counts, and channel details.
*   **Simple Python Interface:** Easy-to-use functions for developers.

## 🛠️ Development Setup

TubeScout uses `uv` for package management. Ensure you have Python 3.10+ installed.

1.  **Clone the repository:**
    bash
      git clone https://github.com/chirag127/TubeScout-YouTube-Scraping-And-Search-Python-Library.git
      cd TubeScout-YouTube-Scraping-And-Search-Python-Library
    

2.  **Install dependencies using uv:**
    bash
      uv venv  # Creates a virtual environment
      uv pip install -r requirements.txt
      uv pip install -r requirements-dev.txt # For development dependencies (testing, linting)
    

3.  **Run Ruff for linting and formatting:**
    bash
      ruff check .
      ruff format .
    

## ▶️ Usage

(Example usage would go here, showing how to import and use the library. As this is a retired product, specific examples are omitted but would typically demonstrate calling functions for search, video info, etc.)

python
# Example (Conceptual):
# from tubescout import YouTubeSearch
# searcher = YouTubeSearch()
# results = searcher.search_videos('Python tutorial')
# print(results)


## 🧪 Testing

TubeScout is tested using `Pytest`.

*   **Run all tests:**
    bash
      pytest
    

## 🤝 Contributing

This project is **archived and no longer maintained**. Contributions will not be accepted. For new projects, please refer to the contributing guidelines in `.github/CONTRIBUTING.md`.

## 📜 License

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0). See the `LICENSE` file for more details.

## ⚠️ Disclaimer

This library is an unofficial tool and is not affiliated with, endorsed by, or sponsored by YouTube or Google LLC. Web scraping may violate YouTube's Terms of Service, and its usage is at your own risk. YouTube's UI and structure are subject to change, which can break the functionality of this scraper.

<details>
  <summary><strong>🤖 AI Agent Directives</strong></summary>

## 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

---

## 2. INPUT PROCESSING & COGNITION
*   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    *   **Context:** User inputs may contain phonetic errors (homophones, typos).
    *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
    *   **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
*   **MANDATORY MCP INSTRUMENTATION:**
    *   **No Guessing:** Do not hallucinate APIs.
    *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    *   **Validation:** Use `docfork` to verify *every* external API signature.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

---

## 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** Detect the project type (`pyproject.toml` for Python) and apply the corresponding **Apex Toolchain**. This repository, `TubeScout-YouTube-Scraping-And-Search-Python-Library`, is a Python-based scraping tool.

*   **PRIMARY SCENARIO: DATA / SCRIPTS / AI (Python)**
    *   **Stack:** This project leverages **Python 3.10+**. Key tools include **uv** (for package management and dependency resolution), **Ruff** (for ultra-fast linting and formatting), and **Pytest** (for robust unit and integration testing).
    *   **Architecture:** Adheres to a **Modular Monolith** pattern, ensuring clear separation of concerns for features like YouTube scraping, data parsing, and caching, while maintaining a unified structure.
    *   **Verification Commands:**
        *   `uv venv`
        *   `uv pip install -r requirements.txt`
        *   `uv pip install -r requirements-dev.txt`
        *   `ruff check .`
        *   `ruff format .`
        *   `pytest`

*   **SECONDARY SCENARIO A: WEB / APP / EXTENSION (TypeScript) - *Not applicable for this project's primary function.***
    *   **Stack:** TypeScript 6.x (Strict), Vite 7 (Rolldown), Tauri v2.x (Native), WXT (Extensions).
    *   **State:** Signals (Standardized).

---

## 4. ARCHIVAL PROTOCOL (RETIRED PRODUCT STANDARD)
*   **MANDATE:** Archived repositories are **NOT** junk. They are "Retired Products." They must be maintained with the highest professional standards for documentation and metadata.
*   **ACTIONS:** Even when archiving, you **MUST** elevate the metadata (Name, Description, Topics, README) to the highest professional standard. The tone should be dignified, historical, and valuable.

---

## 5. SOCIAL PROOF & COMMUNITY ENGAGEMENT
*   **Star Velocity:** Encourage users to **Star ⭐ this Repo** to acknowledge its historical value and utility.
*   **Shields.io:** All badges are configured with `style=flat-square` and `username=chirag127` for consistent branding.

</details>

**Star ⭐ this Repo**
