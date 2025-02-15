# IntelligentDocumentProcessing
A curated list of open source tools and resources for intelligent document processing

# Open-Source Tools for Intelligent Document Processing

---

## 1. OCR & Text Recognition

This section is divided into subcategories to help you choose the right tool based on your specific OCR needs.

### Traditional OCR Engines
- **Tesseract OCR**  
  [![GitHub stars](https://img.shields.io/github/stars/tesseract-ocr/tesseract?style=social)](https://github.com/tesseract-ocr/tesseract)  
  A robust, long-standing OCR engine supporting multiple languages, widely adopted in both academic and industrial applications.  
  [Repository](https://github.com/tesseract-ocr/tesseract)

- **OCRopus (ocropy)**  
  [![GitHub stars](https://img.shields.io/github/stars/tmbdev/ocropy?style=social)](https://github.com/tmbdev/ocropy)  
  A modular OCR system that integrates layout analysis with text recognition, making it suitable for processing complex document structures.  
  [Repository](https://github.com/tmbdev/ocropy)

### Deep Learning-Based OCR
- **PaddleOCR**  
  [![GitHub stars](https://img.shields.io/github/stars/PaddlePaddle/PaddleOCR?style=social)](https://github.com/PaddlePaddle/PaddleOCR)  
  A state-of-the-art, deep learning-driven OCR solution from the PaddlePaddle ecosystem, engineered to deliver reliable performance in diverse conditions.  
  [Repository](https://github.com/PaddlePaddle/PaddleOCR)

- **DocTR (Document Text Recognition)**  
  [![GitHub stars](https://img.shields.io/github/stars/mindee/doctr?style=social)](https://github.com/mindee/doctr)  
  A modern deep learning library tailored for document text recognition, designed to efficiently handle varied layouts and formats.  
  [Repository](https://github.com/mindee/doctr)

### Specialized OCR for Historical & Handwritten Documents
- **Kraken OCR**  
  [![GitHub stars](https://img.shields.io/github/stars/mittagessen/kraken?style=social)](https://github.com/mittagessen/kraken)  
  Focused on historical and handwritten texts, Kraken provides advanced recognition capabilities for challenging scripts and degraded documents.  
  [Repository](https://github.com/mittagessen/kraken)


---

## 2. Document Layout and Structuring

### A. General Layout Analysis
- **LayoutParser**  
  [![GitHub stars](https://img.shields.io/github/stars/Layout-Parser/layout-parser?style=social)](https://github.com/Layout-Parser/layout-parser)  
  A comprehensive toolkit leveraging deep learning for detecting layout elements—such as text blocks, tables, and images—in various document types.  
  [Repository](https://github.com/Layout-Parser/layout-parser)

### B. Scholarly Document Metadata Extraction
- **GROBID**  
  [![GitHub stars](https://img.shields.io/github/stars/kermitt2/grobid?style=social)](https://github.com/kermitt2/grobid)  
  A specialized tool for extracting and structuring bibliographic and header metadata from academic publications, ideal for scholarly document analysis.  
  [Repository](https://github.com/kermitt2/grobid)

### C. Academic Document Parsing and Analysis
- **CERMINE**  
  [![GitHub stars](https://img.shields.io/github/stars/CeON/CERMINE?style=social)](https://github.com/CeON/CERMINE)  
  A Java-based library that extracts structured metadata and full-text content from scientific PDFs using advanced layout analysis and NLP techniques.  
  [Repository](https://github.com/CeON/CERMINE)

- **DeepFigures**  
  [![GitHub stars](https://img.shields.io/github/stars/allenai/deepfigures?style=social)](https://github.com/allenai/deepfigures)  
  Developed by the Allen Institute for AI, DeepFigures detects and extracts figures and tables from scholarly articles to enhance visual data analysis.  
  [Repository](https://github.com/allenai/deepfigures)

- **Science Parse**  
  [![GitHub stars](https://img.shields.io/github/stars/allenai/science-parse?style=social)](https://github.com/allenai/science-parse)  
  An open-source tool utilizing layout analysis and machine learning to extract structured metadata from academic PDFs, streamlining literature indexing.  
  [Repository](https://github.com/allenai/science-parse)

- **ParsCit**  
  [![GitHub stars](https://img.shields.io/github/stars/knmnyn/ParsCit?style=social)](https://github.com/knmnyn/ParsCit)  
  A citation extraction tool that parses academic documents to extract and structure citation data, useful for building bibliographic databases.  
  [Repository](https://github.com/knmnyn/ParsCit)

---

## 3. PDF Processing

### A. Text Extraction & Layout Analysis
- **pdfminer.six**  
  [![GitHub stars](https://img.shields.io/github/stars/pdfminer/pdfminer.six?style=social)](https://github.com/pdfminer/pdfminer.six)  
  A comprehensive Python library for PDF analysis, offering granular control for text extraction and layout analysis.  
  [Repository](https://github.com/pdfminer/pdfminer.six)

- **PDFPlumber**  
  [![GitHub stars](https://img.shields.io/github/stars/jsvine/pdfplumber?style=social)](https://github.com/jsvine/pdfplumber)  
  A tool for precise extraction of text, tables, and metadata from PDFs, preserving key layout details in the process.  
  [Repository](https://github.com/jsvine/pdfplumber)

- **Apache PDFBox**  
  [![GitHub stars](https://img.shields.io/github/stars/apache/pdfbox?style=social)](https://github.com/apache/pdfbox)  
  A robust Java library offering extensive features for text extraction, document manipulation, and rendering of PDFs.  
  [Repository](https://github.com/apache/pdfbox)

### B. PDF Manipulation & Editing
- **PyPDF2**  
  [![GitHub stars](https://img.shields.io/github/stars/py-pdf/PyPDF2?style=social)](https://github.com/py-pdf/PyPDF2)  
  A versatile Python library for programmatically splitting, merging, and editing PDF documents.  
  [Repository](https://github.com/py-pdf/PyPDF2)

- **pikepdf**  
  [![GitHub stars](https://img.shields.io/github/stars/pikepdf/pikepdf?style=social)](https://github.com/pikepdf/pikepdf)  
  Built on QPDF, this Python library enables secure and efficient PDF editing, including tasks like encryption and file repair.  
  [Repository](https://github.com/pikepdf/pikepdf)

- **qpdf**  
  [![GitHub stars](https://img.shields.io/github/stars/qpdf/qpdf?style=social)](https://github.com/qpdf/qpdf)  
  A command-line tool and library for performing structural, content-preserving transformations on PDF files.  
  [Repository](https://github.com/qpdf/qpdf)

### C. Rendering & Conversion
- **PyMuPDF (fitz)**  
  [![GitHub stars](https://img.shields.io/github/stars/pymupdf/PyMuPDF?style=social)](https://github.com/pymupdf/PyMuPDF)  
  Python bindings for the MuPDF library, enabling efficient rendering of PDFs as images along with high-quality content extraction.  
  [Repository](https://github.com/pymupdf/PyMuPDF)

- **pdf2image**  
  [![GitHub stars](https://img.shields.io/github/stars/Belval/pdf2image?style=social)](https://github.com/Belval/pdf2image)  
  Converts PDF pages into images using Poppler, facilitating image pre-processing and OCR workflows.  
  [Repository](https://github.com/Belval/pdf2image)

- **pdf.js**  
  [![GitHub stars](https://img.shields.io/github/stars/mozilla/pdf.js?style=social)](https://github.com/mozilla/pdf.js)  
  A JavaScript library that renders PDFs directly in the browser, ideal for interactive web applications and client-side PDF viewing.  
  [Repository](https://github.com/mozilla/pdf.js)

### D. Table Extraction from PDFs
- **Camelot**  
  [![GitHub stars](https://img.shields.io/github/stars/camelot-dev/camelot?style=social)](https://github.com/camelot-dev/camelot)  
  An efficient tool designed to extract tables from PDF documents, converting them into structured data formats for further analysis.  
  [Repository](https://github.com/camelot-dev/camelot)

- **Tabula**  
  [![GitHub stars](https://img.shields.io/github/stars/tabulapdf/tabula?style=social)](https://github.com/tabulapdf/tabula)  
  A widely adopted solution for extracting tabular data from PDFs, known for its ease-of-use and reliability.  
  [Repository](https://github.com/tabulapdf/tabula)

- **Excalibur**  
  [![GitHub stars](https://img.shields.io/github/stars/camelot-dev/excalibur?style=social)](https://github.com/camelot-dev/excalibur)  
  A web-based interface for Camelot that allows users to visually select and extract tables from PDF files.  
  [Repository](https://github.com/camelot-dev/excalibur)


---
## 4. Natural Language Processing (NLP)

### A. General NLP Toolkits
- **spaCy**  
  [![GitHub stars](https://img.shields.io/github/stars/explosion/spaCy?style=social)](https://github.com/explosion/spaCy)  
  A fast, production-ready NLP library designed for large-scale information extraction and text processing.  
  [Repository](https://github.com/explosion/spaCy)

- **NLTK**  
  [![GitHub stars](https://img.shields.io/github/stars/nltk/nltk?style=social)](https://github.com/nltk/nltk)  
  A comprehensive library for symbolic and statistical natural language processing in Python, offering tools for tokenization, parsing, and more.  
  [Repository](https://github.com/nltk/nltk)

- **Stanza**  
  [![GitHub stars](https://img.shields.io/github/stars/stanfordnlp/stanza?style=social)](https://github.com/stanfordnlp/stanza)  
  A Python NLP library from the Stanford NLP Group, providing state-of-the-art neural network-based text analysis and annotation.  
  [Repository](https://github.com/stanfordnlp/stanza)

### B. Deep Learning-Based NLP Frameworks
- **AllenNLP**  
  [![GitHub stars](https://img.shields.io/github/stars/allenai/allennlp?style=social)](https://github.com/allenai/allennlp)  
  An advanced NLP framework built on PyTorch, designed to support cutting-edge research and robust application development in deep learning for NLP.  
  [Repository](https://github.com/allenai/allennlp)

- **Hugging Face Transformers**  
  [![GitHub stars](https://img.shields.io/github/stars/huggingface/transformers?style=social)](https://github.com/huggingface/transformers)  
  A state-of-the-art library offering thousands of pre-trained models for a wide range of NLP tasks, simplifying the integration of transformer models into your projects.  
  [Repository](https://github.com/huggingface/transformers)

- **Flair**  
  [![GitHub stars](https://img.shields.io/github/stars/flairNLP/flair?style=social)](https://github.com/flairNLP/flair)  
  A simple yet powerful NLP framework that provides a range of text embeddings and pre-trained models for tasks such as named entity recognition and text classification.  
  [Repository](https://github.com/flairNLP/flair)

---

## 5. Computer Vision & Image Processing

### A. Core Libraries & Frameworks
- **OpenCV**  
  [![GitHub stars](https://img.shields.io/github/stars/opencv/opencv?style=social)](https://github.com/opencv/opencv)  
  A comprehensive computer vision library offering a vast array of functions for image processing, computer vision, and machine learning.  
  [Repository](https://github.com/opencv/opencv)

- **scikit-image**  
  [![GitHub stars](https://img.shields.io/github/stars/scikit-image/scikit-image?style=social)](https://github.com/scikit-image/scikit-image)  
  A collection of algorithms for image processing in Python, built on top of SciPy—ideal for rapid prototyping and research-grade applications.  
  [Repository](https://github.com/scikit-image/scikit-image)

- **Pillow**  
  [![GitHub stars](https://img.shields.io/github/stars/python-pillow/Pillow?style=social)](https://github.com/python-pillow/Pillow)  
  The friendly PIL fork, offering a powerful image processing toolkit for tasks ranging from basic operations to complex manipulations.  
  [Repository](https://github.com/python-pillow/Pillow)

### B. Deep Learning & Model-Based Computer Vision
- **Detectron2**  
  [![GitHub stars](https://img.shields.io/github/stars/facebookresearch/detectron2?style=social)](https://github.com/facebookresearch/detectron2)  
  A cutting-edge object detection and segmentation framework built on PyTorch, suitable for both research experiments and production systems.  
  [Repository](https://github.com/facebookresearch/detectron2)

- **MMDetection**  
  [![GitHub stars](https://img.shields.io/github/stars/open-mmlab/mmdetection?style=social)](https://github.com/open-mmlab/mmdetection)  
  A robust object detection toolbox offering a wide range of models and utilities for modern detection tasks.  
  [Repository](https://github.com/open-mmlab/mmdetection)

- **Kornia**  
  [![GitHub stars](https://img.shields.io/github/stars/kornia/kornia?style=social)](https://github.com/kornia/kornia)  
  A differentiable computer vision library for PyTorch that provides a rich set of image processing operations, seamlessly integrating into deep learning workflows.  
  [Repository](https://github.com/kornia/kornia)

### C. Data Augmentation & Preprocessing
- **Albumentations**  
  [![GitHub stars](https://img.shields.io/github/stars/albumentations-team/albumentations?style=social)](https://github.com/albumentations-team/albumentations)  
  A fast and flexible image augmentation library designed to improve model robustness through diverse transformations.  
  [Repository](https://github.com/albumentations-team/albumentations)

- **imgaug**  
  [![GitHub stars](https://img.shields.io/github/stars/aleju/imgaug?style=social)](https://github.com/aleju/imgaug)  
  A powerful augmentation library for images, offering a variety of techniques to enhance training datasets for computer vision tasks.  
  [Repository](https://github.com/aleju/imgaug)
