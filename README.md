# FMEA Knowledge Reuse Dataset

This repository contains the curated industrial welding datasets and Product-Process-Resource (PPR) ontologies used in the research paper: **"Human-in-the-Loop Reuse of Risk Analysis Knowledge Using Large Language Models and Case-Based Reasoning."**

## Overview
This dataset supports a framework that combines **Case-Based Reasoning (CBR)** and **Retrieval-Augmented Generation (RAG)** to systematically capture and reuse Failure Mode and Effects Analysis (FMEA) knowledge.

## Repository Structure

### 📂 knowledge_base/
This folder contains the raw and semi-structured FMEA data used to populate the vector-relational knowledge base.
* **Format**: .xlsx (APIS IQ Exports)
* **Content**: 10 unique welding cases including Manual TIG, Robotic Spot Welding, and Ultrasonic Plastic Welding.
* **Fields**: Each file includes standardized FMEA columns: Potential Failure, Effects, Causes, Current Controls, and SOD (Severity, Occurrence, Detection) ratings.

### 📄 PPR_Description_Document.pdf
This document provides the semantic grounding for the data. It includes the **Case Title** and **Case Description**, providing a holistic view of each scenario along with the following **Product-Process-Resource (PPR)** details:

* **Product**: Detailed breakdown of the **Input Product** (raw materials) and **Output Product** (finished weldment).
* **Process**: The specific welding modality, parameters, and operational steps.
* **Resource**: The equipment, tools, or human actors involved (e.g., Cobot, NDT Equipment, or Manual Welder).
