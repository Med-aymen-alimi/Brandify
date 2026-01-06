---

# **Brandify: AI-Powered Branding Strategy Application**

**Brandify** is an AI-powered application designed to deliver intelligent recommendations and strategic guidance for branding. The platform integrates multiple AI models into a unified web application to support interactive, data-driven brand development.

This repository contains **three AI models** that work together to provide a seamless branding experience:

---

## **Integrated AI Models**

### **1. Speech-to-Text Model**

This model converts spoken user input into text, enabling natural and seamless interaction with the application. It leverages:

* `Speech2TextProcessor`
* `Speech2TextForConditionalGeneration`
  from the Transformer architecture.

---

### **2. NLP-Driven Branding Strategy Tool**

This model focuses on generating branding assets that enhance corporate visibility and appeal. It provides:

* Product name suggestions
* Color palette recommendations

These outputs are tailored to support effective branding strategies within a professional and competitive market landscape.

---

### **3. Text-to-Speech Model**

The Text-to-Speech model converts the generated branding recommendations into audio output. It is built using:

* `SpeechT5Processor`
* `SpeechT5ForTextToSpeech`
* `SpeechT5HifiGan`

The `set_seed` function is used to ensure reproducibility of the generated results.

---

## **Deployment Readiness**

All three models have been thoroughly tested within this notebook and are fully prepared for integration and deployment within the Brandify web application.

---

