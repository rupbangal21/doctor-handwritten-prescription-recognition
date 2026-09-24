# Doctor Handwritten Prescription Recognition using TrOCR

An AI-based handwritten prescription recognition system that converts handwritten prescription images into machine-readable text using **TrOCR (Transformer-based Optical Character Recognition)**.

The project also uses **fuzzy string matching** and **medicine-name mapping** to improve the identification of medicines from OCR-generated text.

---

## 📌 Overview

Reading handwritten medical prescriptions can be difficult because of variations in handwriting, abbreviations, and medical terminology.

This project aims to automate the recognition of handwritten prescriptions using a Transformer-based OCR model. The system processes prescription images, recognizes the handwritten text, and can map recognized medicine names to their corresponding generic names.

---

## 🎯 Objectives

- Recognize handwritten text from prescription images.
- Convert handwritten prescriptions into digital text.
- Reduce errors associated with manual transcription.
- Correct possible OCR spelling variations.
- Identify medicine names using fuzzy matching.
- Map medicine names to their generic names.
- Provide a foundation for an intelligent prescription-processing system.

---

## 🔄 System Workflow

```text
Handwritten Prescription Image
            ↓
     Image Preprocessing
            ↓
       TrOCR Model
            ↓
    Recognized Text
            ↓
     Text Correction
            ↓
    Medicine Detection
            ↓
   Generic Medicine Mapping
