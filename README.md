# 🚀 My Recent Projects

## 🧠 DealSignal: AI Sourcing Intelligence Engine
> *Deal teams don’t have an information problem—they have a "what do I do now?" problem.*

### The Core Challenge
In private equity and venture sourcing, the signal is almost always buried. Important moves are hidden across random interviews, obscure press releases, and leadership shifts. Most deal teams don't struggle to find data; they struggle to decide which companies actually deserve a phone call today. 

Manually tracking a massive watchlist simply doesn't scale. This project is about automating that "manual grind" and converting raw public data into a **ranked, actionable shortlist.**

### The Strategy: Signal over Stream
Instead of handing users a noisy feed of alerts, this system uses a combination of **web discovery and LLM extraction** to hunt for high-intent moves:

* **Expansion & Intent:** Detecting geographic growth or explicit acquisition signals.
* **Capital & Leadership:** Tracking fundraising activity and regulatory shifts in real-time.
* **Narrative Deltas:** Identifying what is *actually* new, rather than just re-hashing old news.

### The Architecture
* **The Intelligence:** We use **Azure OpenAI** for structured signal extraction and a custom lead-scoring model based on significance, recency, and thesis fit.
* **The Pipeline:** A nightly batch process running on **Azure Container Apps** ensures the data is fresh every morning.
* **The Interface:** A clean, high-signal UI focused on **Priority Now** and **Top Opportunities This Week.**

### Why This Matters
> "Most tools tell you what happened. This engine tells you why it matters and who you should approach first."

**The Bottom Line:** This isn't just a monitoring tool. It’s a sourcing engine designed to move the needle on outreach by focusing on the signals that lead to closed deals.

👉 Explore the project here:  
**[View Repository](https://github.com/deril2605/DealSignal-AI-in-the-Wild)**

---

## 🧠 GP One-Pager Tearsheet Generator

> *Investment analysts shouldn't spend their afternoons hunting through PDF footers for AUM and leadership bios.*

### The Problem: The "Analyst Tax"
Every investment team knows the drill: to understand a new firm, someone has to spend hours digging through fragmented websites, buried PDFs, and outdated reports. Extracting core data—like **AUM, investment strategy, and team profiles**—is a manual, repetitive "tax" on an analyst's time.

This project solves that by turning an investment firm’s entire digital footprint into a **clean, structured one-page profile** in seconds.


### How it Works: The AI Researcher
We built an agentic workflow that doesn't just scrape; it *researches*. It navigates a firm's website much like a human would, identifying the most relevant pages and extracting high-fidelity data:

* **Strategic Intelligence:** Auto-extracting AUM, sector focus, and investment stage.
* **Team Discovery:** Identifying key leadership and automatically surfacing professional headshots.
* **The "Tear Sheet" Output:** Generating a polished, dynamic HTML report that's ready for immediate review.

### The Tech Behind the Agent
* **Autonomous Web Navigation:** AI-guided exploration that knows the difference between a "News" post and a "Strategy" page.
* **LLM Extraction:** High-accuracy data parsing that structures messy web text into clean JSON fields.
* **Dynamic Generation:** A frontend that instantly assembles this data into a professional, one-page GP profile.


### The Reality Check
> "This isn't just about 'scraping' data. It’s about automating the document discovery process so deal teams can spend their time on *analysis*, not data entry."

**The Bottom Line:** Instead of manually compiling firm summaries over the course of an hour, this system builds them in under thirty seconds. It’s not just a tool; it’s a force multiplier for investment research.

👉 Curious how it works?  
Explore the project here: **[View Repository](https://github.com/deril2605/GP-One-Pager-Tearsheet-Generator)**

---

## 📄 Intelligent Document Processing (Production-Ready)

> *Modern organizations don't have a storage problem—they have a "trapped data" problem.*

### The Challenge: The Document Black Box
Most companies are sitting on a goldmine of information locked inside thousands of contracts, licenses, and financial reports. The value is there, but it’s trapped in static PDFs that software can’t "read" effectively. Manually transcribing this data isn't just slow; it’s an operational bottleneck that prevents real-time decision-making.

This project bridges that gap by building a **production-grade AI pipeline** that transforms raw documents into structured, actionable intelligence.


### The Architecture: A Real-World Blueprint
This isn't just a simple script; it’s a scalable infrastructure designed for enterprise-level document processing. The system focuses on three core stages:

* **High-Fidelity Ingestion:** Using GPU-accelerated parsing and advanced OCR to handle even the most complex, multi-column layouts.
* **Intelligent Extraction:** Moving beyond keyword matching to true "document understanding"—identifying context, relationships, and hidden fields.
* **Asynchronous Scalability:** A cloud-native workflow that processes documents in the background, ensuring the system stays fast even under heavy loads.

### The Tech Stack
* **Processing:** GPU-based parsing engines for speed and accuracy on dense financial documents.
* **Intelligence:** Advanced AI services for field normalization (making sure "Date" and "Signed On" mean the same thing).
* **Infrastructure:** A scalable, asynchronous pipeline with cloud-native storage for downstream application integration.

### The Strategic Value
> "The goal isn't just to 'extract text.' It’s about building a reliable, automated infrastructure that turns a folder of PDFs into a structured database in minutes."

**The Bottom Line:** This project moves document processing from a manual chore to an automated asset. It provides the "eyes and brain" for an organization's digital archive, making data accessible, searchable, and ready for work.

👉 See the full architecture and implementation:  
**[View Repository](https://github.com/deril2605/Intelligent-Document-Processing-Production-Ready)**

---

✨ More projects coming soon — exploring **AI agents, web automation, and intelligent research systems.**

# Explore me on [Git City](https://www.thegitcity.com/dev/deril2605)
<img width="1264" height="719" alt="image" src="https://github.com/user-attachments/assets/4ddf8eda-5ec1-4846-a1b0-ab2c847c7e65" />
