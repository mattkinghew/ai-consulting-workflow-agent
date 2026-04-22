# AI Consulting Workflow Agent (AromaMind PoC)

## 📌 Overview
This repository contains the Proof of Concept (PoC) for an AI-driven consulting agent designed to standardize and automate unstructured wellness consultations. Built on Amazon Bedrock (via PartyRock), it restricts user inputs and enforces predefined output schemas, mitigating the hallucination risks typical of standard conversational chatbots.

## ⚙️ System Architecture
The application utilizes a dual-node input system mapped to prompt templates:
- **Input Node 1:** `Current Stress or Mood` (Captures user intent and emotional baseline)
- **Input Node 2:** `Available Inventory` (Captures resource constraints, e.g., essential oils on hand)
- **Output Node 1:** `Custom Formulation` (LLM-generated recipe strictly bounded by inventory)
- **Output Node 2:** `Actionable Routine` (A generated 5-minute operational protocol based on the formulation)

## 🚀 Business Value (ROI)
- **Scalability:** Reduces consultation marginal costs to near zero.
- **Risk Management:** Eliminates prompt-injection vulnerabilities by hardcoding system parameters behind UI widgets.
- **Repeatability:** Transforms a generative AI model from a conversational toy into a standardized business tool.

## 🔗 Live Demo
[Insert your PartyRock Public Link Here]
