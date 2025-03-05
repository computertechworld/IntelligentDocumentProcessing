# IntelligentDocumentProcessing
A curated list of open source tools and resources for intelligent document processing

# Open-Source Tools for Intelligent Document Processing

---

## 1. OCR & Text Recognition

### A. Traditional OCR Engines
- **Tesseract OCR** [![GitHub stars](https://img.shields.io/github/stars/tesseract-ocr/tesseract?style=social)](https://github.com/tesseract-ocr/tesseract) – Established OCR engine supporting multiple languages, now enhanced with LSTM (v4+). [Repo](https://github.com/tesseract-ocr/tesseract)
- **OCRopus (ocropy)** [![GitHub stars](https://img.shields.io/github/stars/tmbdev/ocropy?style=social)](https://github.com/tmbdev/ocropy) – Modular OCR system combining layout analysis with text recognition for complex documents. [Repo](https://github.com/tmbdev/ocropy)

### B. Deep Learning-Based OCR
- **PaddleOCR** [![GitHub stars](https://img.shields.io/github/stars/PaddlePaddle/PaddleOCR?style=social)](https://github.com/PaddlePaddle/PaddleOCR) – State-of-the-art deep learning OCR solution from PaddlePaddle for robust text recognition. [Repo](https://github.com/PaddlePaddle/PaddleOCR)
- **DocTR (Document Text Recognition)** [![GitHub stars](https://img.shields.io/github/stars/mindee/doctr?style=social)](https://github.com/mindee/doctr) – Modern deep learning library for document text recognition handling diverse layouts. [Repo](https://github.com/mindee/doctr)

### C. Specialized OCR for Historical/Handwritten Documents
- **Kraken OCR** [![GitHub stars](https://img.shields.io/github/stars/mittagessen/kraken?style=social)](https://github.com/mittagessen/kraken) – Specialized OCR tool optimized for historical and handwritten texts with advanced recognition features. [Repo](https://github.com/mittagessen/kraken)

## 2. Document Layout and Structuring

### A. General Layout Analysis
- **LayoutParser** [![GitHub stars](https://img.shields.io/github/stars/Layout-Parser/layout-parser?style=social)](https://github.com/Layout-Parser/layout-parser) – Toolkit leveraging deep learning for detecting layout elements (text blocks, tables, images) in documents. [Repo](https://github.com/Layout-Parser/layout-parser)

### B. Scholarly Document Metadata Extraction
- **GROBID** [![GitHub stars](https://img.shields.io/github/stars/kermitt2/grobid?style=social)](https://github.com/kermitt2/grobid) – ML-based tool for extracting and structuring bibliographic and header metadata from scholarly documents. [Repo](https://github.com/kermitt2/grobid)

### C. Academic Document Parsing and Analysis
- **CERMINE** [![GitHub stars](https://img.shields.io/github/stars/CeON/CERMINE?style=social)](https://github.com/CeON/CERMINE) – Java library that extracts structured metadata and full-text content from scientific PDFs using advanced layout analysis and NLP. [Repo](https://github.com/CeON/CERMINE)
- **DeepFigures** [![GitHub stars](https://img.shields.io/github/stars/allenai/deepfigures?style=social)](https://github.com/allenai/deepfigures) – Automatically detects and extracts figures and tables from scholarly articles for visual data analysis. [Repo](https://github.com/allenai/deepfigures)
- **Science Parse** [![GitHub stars](https://img.shields.io/github/stars/allenai/science-parse?style=social)](https://github.com/allenai/science-parse) – Uses layout analysis and ML to extract structured metadata from academic PDFs, streamlining literature indexing. [Repo](https://github.com/allenai/science-parse)
- **ParsCit** [![GitHub stars](https://img.shields.io/github/stars/knmnyn/ParsCit?style=social)](https://github.com/knmnyn/ParsCit) – Citation extraction tool that parses academic documents to structure citation data for bibliographic databases. [Repo](https://github.com/knmnyn/ParsCit)

## 3. PDF Processing

### A. Text Extraction & Layout Analysis
- **pdfminer.six** [![GitHub stars](https://img.shields.io/github/stars/pdfminer/pdfminer.six?style=social)](https://github.com/pdfminer/pdfminer.six) – Comprehensive Python library for granular text extraction and layout analysis from PDFs. [Repo](https://github.com/pdfminer/pdfminer.six)
- **PDFPlumber** [![GitHub stars](https://img.shields.io/github/stars/jsvine/pdfplumber?style=social)](https://github.com/jsvine/pdfplumber) – Extracts text, tables, and metadata from PDFs while preserving layout details. [Repo](https://github.com/jsvine/pdfplumber)
- **Apache PDFBox** [![GitHub stars](https://img.shields.io/github/stars/apache/pdfbox?style=social)](https://github.com/apache/pdfbox) – Robust Java library for text extraction, document manipulation, and PDF rendering. [Repo](https://github.com/apache/pdfbox)

### B. PDF Manipulation & Editing
- **PyPDF2** [![GitHub stars](https://img.shields.io/github/stars/py-pdf/PyPDF2?style=social)](https://github.com/py-pdf/PyPDF2) – Versatile Python library for splitting, merging, and editing PDF documents. [Repo](https://github.com/py-pdf/PyPDF2)
- **pikepdf** [![GitHub stars](https://img.shields.io/github/stars/pikepdf/pikepdf?style=social)](https://github.com/pikepdf/pikepdf) – Python library built on QPDF for secure and efficient PDF editing, including encryption and repair. [Repo](https://github.com/pikepdf/pikepdf)
- **qpdf** [![GitHub stars](https://img.shields.io/github/stars/qpdf/qpdf?style=social)](https://github.com/qpdf/qpdf) – Command-line tool and library for structural, content-preserving transformations of PDF files. [Repo](https://github.com/qpdf/qpdf)

### C. Rendering & Conversion
- **PyMuPDF (fitz)** [![GitHub stars](https://img.shields.io/github/stars/pymupdf/PyMuPDF?style=social)](https://github.com/pymupdf/PyMuPDF) – Python bindings for MuPDF, enabling efficient rendering of PDFs as images with high-quality content extraction. [Repo](https://github.com/pymupdf/PyMuPDF)
- **pdf2image** [![GitHub stars](https://img.shields.io/github/stars/Belval/pdf2image?style=social)](https://github.com/Belval/pdf2image) – Converts PDF pages into images using Poppler, ideal for image pre-processing and OCR workflows. [Repo](https://github.com/Belval/pdf2image)
- **pdf.js** [![GitHub stars](https://img.shields.io/github/stars/mozilla/pdf.js?style=social)](https://github.com/mozilla/pdf.js) – JavaScript library for rendering PDFs directly in the browser for interactive web applications. [Repo](https://github.com/mozilla/pdf.js)

### D. Table Extraction from PDFs
- **Camelot** [![GitHub stars](https://img.shields.io/github/stars/camelot-dev/camelot?style=social)](https://github.com/camelot-dev/camelot) – Efficiently extracts tables from PDFs and converts them into structured data formats. [Repo](https://github.com/camelot-dev/camelot)
- **Tabula** [![GitHub stars](https://img.shields.io/github/stars/tabulapdf/tabula?style=social)](https://github.com/tabulapdf/tabula) – Widely used for extracting tabular data from PDFs, known for its ease-of-use and reliability. [Repo](https://github.com/tabulapdf/tabula)
- **Excalibur** [![GitHub stars](https://img.shields.io/github/stars/camelot-dev/excalibur?style=social)](https://github.com/camelot-dev/excalibur) – Web-based interface for Camelot, allowing visual selection and extraction of tables from PDF files. [Repo](https://github.com/camelot-dev/excalibur)

## 4. Natural Language Processing (NLP)

### A. General NLP Toolkits
- **spaCy** [![GitHub stars](https://img.shields.io/github/stars/explosion/spaCy?style=social)](https://github.com/explosion/spaCy) – Fast, production-ready NLP library for large-scale information extraction and text processing. [Repo](https://github.com/explosion/spaCy)
- **NLTK** [![GitHub stars](https://img.shields.io/github/stars/nltk/nltk?style=social)](https://github.com/nltk/nltk) – Comprehensive library for symbolic and statistical NLP in Python, offering extensive processing tools. [Repo](https://github.com/nltk/nltk)
- **Stanza** [![GitHub stars](https://img.shields.io/github/stars/stanfordnlp/stanza?style=social)](https://github.com/stanfordnlp/stanza) – Neural network-based NLP toolkit from Stanford, delivering state-of-the-art text analysis and annotation. [Repo](https://github.com/stanfordnlp/stanza)

### B. Deep Learning-Based NLP Frameworks
- **AllenNLP** [![GitHub stars](https://img.shields.io/github/stars/allenai/allennlp?style=social)](https://github.com/allenai/allennlp) – Advanced NLP framework built on PyTorch for cutting-edge research and robust application development. [Repo](https://github.com/allenai/allennlp)
- **Hugging Face Transformers** [![GitHub stars](https://img.shields.io/github/stars/huggingface/transformers?style=social)](https://github.com/huggingface/transformers) – Extensive library offering thousands of pre-trained models for diverse NLP tasks with transformer architecture. [Repo](https://github.com/huggingface/transformers)
- **Flair** [![GitHub stars](https://img.shields.io/github/stars/flairNLP/flair?style=social)](https://github.com/flairNLP/flair) – Simple yet powerful framework providing state-of-the-art text embeddings and models for various NLP tasks. [Repo](https://github.com/flairNLP/flair)

## 5. Computer Vision & Image Processing

### A. Core Libraries & Frameworks
- **OpenCV** [![GitHub stars](https://img.shields.io/github/stars/opencv/opencv?style=social)](https://github.com/opencv/opencv) – Comprehensive library offering extensive functionalities for image processing and computer vision tasks. [Repo](https://github.com/opencv/opencv)
- **scikit-image** [![GitHub stars](https://img.shields.io/github/stars/scikit-image/scikit-image?style=social)](https://github.com/scikit-image/scikit-image) – Collection of image processing algorithms built on SciPy for rapid prototyping and research. [Repo](https://github.com/scikit-image/scikit-image)
- **Pillow** [![GitHub stars](https://img.shields.io/github/stars/python-pillow/Pillow?style=social)](https://github.com/python-pillow/Pillow) – Friendly fork of PIL offering powerful image manipulation and processing capabilities. [Repo](https://github.com/python-pillow/Pillow)

### B. Deep Learning & Model-Based Computer Vision
- **Detectron2** [![GitHub stars](https://img.shields.io/github/stars/facebookresearch/detectron2?style=social)](https://github.com/facebookresearch/detectron2) – Cutting-edge object detection and segmentation framework built on PyTorch for research and production. [Repo](https://github.com/facebookresearch/detectron2)
- **MMDetection** [![GitHub stars](https://img.shields.io/github/stars/open-mmlab/mmdetection?style=social)](https://github.com/open-mmlab/mmdetection) – Robust toolbox offering a wide range of models and utilities for modern object detection tasks. [Repo](https://github.com/open-mmlab/mmdetection)
- **Kornia** [![GitHub stars](https://img.shields.io/github/stars/kornia/kornia?style=social)](https://github.com/kornia/kornia) – Differentiable computer vision library for PyTorch with rich image processing operations for deep learning workflows. [Repo](https://github.com/kornia/kornia)

### C. Data Augmentation & Preprocessing
- **Albumentations** [![GitHub stars](https://img.shields.io/github/stars/albumentations-team/albumentations?style=social)](https://github.com/albumentations-team/albumentations) – Fast and flexible image augmentation library designed to boost model robustness with diverse transformations. [Repo](https://github.com/albumentations-team/albumentations)
- **imgaug** [![GitHub stars](https://img.shields.io/github/stars/aleju/imgaug?style=social)](https://github.com/aleju/imgaug) – Powerful augmentation library offering a variety of techniques to enhance training datasets for computer vision tasks. [Repo](https://github.com/aleju/imgaug)
