<div align="center">

# MoneyPrinterTurbo 💸

**Automated Multi-Modal Video Generation Engine powered by Large Language Models & Text-to-Speech**

[![Version](https://img.shields.io/github/v/release/harry0703/MoneyPrinterTurbo?color=blue&label=version)](https://github.com/harry0703/MoneyPrinterTurbo/releases)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg)](https://github.com/harry0703/MoneyPrinterTurbo/releases/latest)
[![Python](https://img.shields.io/badge/python-3.11%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Downloads](https://img.shields.io/github/downloads/harry0703/MoneyPrinterTurbo/total)](https://github.com/harry0703/MoneyPrinterTurbo/releases/latest)
[![License](https://img.shields.io/github/license/harry0703/MoneyPrinterTurbo)](LICENSE)

[Releases](https://github.com/harry0703/MoneyPrinterTurbo/releases) • [Issue Tracker](https://github.com/harry0703/MoneyPrinterTurbo/issues) • [API Documentation](#api-service)

</div>

---

### User Interfaces

<table align="center" width="100%">
<tr>
<td align="center" width="50%">
  <strong>WebUI (Streamlit)</strong><br><br>
  <img src="docs/webui-en.jpg" alt="WebUI Preview" width="100%"/>
</td>
<td align="center" width="50%">
  <strong>FastAPI Interactive Docs</strong><br><br>
  <img src="docs/api.jpg" alt="API Preview" width="100%"/>
</td>
</tr>
</table>

---

## Overview

**MoneyPrinterTurbo** is an end-to-end automated video production framework designed to turn a single topic or prompt into a finalized short-form or landscape video. The engine orchestrates script generation, voice synthesis, dynamic footage sourcing, subtitle alignment, background scoring, and final composite rendering via FFmpeg.

### Core Capabilities

- **Flexible Interfaces:** Operate via **WebUI**, **REST API**, **CLI**, or integrated **AI Agent workflows**.
- **End-to-End Automation:** Complete pipeline from theme $\rightarrow$ script $\rightarrow$ voiceover $\rightarrow$ media asset matching $\rightarrow$ subtitle burns $\rightarrow$ background music $\rightarrow$ post-production.
- **Batch Processing:** Support for parallel and sequential task queues, job persistence, and reproducible parameter manifests.
- **Model Agnostic:** Connect directly to OpenAI, Anthropic, Google Gemini
