# Awesome PDF Parser & Document Intelligence Tools ✨

[![Curated List](https://img.shields.io/badge/Curated-List-blue.svg)](https://github.com/YOUR_USERNAME/Awesome_pdf_prarser)
[![License: CC0](https://img.shields.io/badge/License-CC0-green.svg)](https://creativecommons.org/publicdomain/zero/1.0)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![GitHub stars](https://img.shields.io/github/stars/YOUR_USERNAME/Awesome_pdf_prarser?style=social)](https://github.com/YOUR_USERNAME/Awesome_pdf_prarser)
[![Last Commit](https://img.shields.io/github/last-commit/YOUR_USERNAME/Awesome_pdf_prarser)](https://github.com/YOUR_USERNAME/Awesome_pdf_prarser/commits/main)

> 🚀 A comprehensive, curated list of open-source libraries, tools, and projects for document processing, intelligence, and data extraction. Synthesized from community recommendations, established projects, and emerging research.

## 📚 Table of Contents

- [📖 Curated Lists & Resources](#-curated-lists--resources)
- [🔧 General Document Processing](#-general-document-processing--pipelines)
- [🎯 Document Intelligence Platforms](#-document-intelligence-platforms)
- [📁 Document Management Systems](#-document-management-systems-dms)
- [🛠️ SDKs & API Toolkits](#️-sdks--api-toolkits)
- [📄 PDF Text & Data Extraction](#-pdf-text--data-extraction)
- [🧠 Layout-Aware Document Parsing](#-layout-aware-document-parsing)
- [👁️ OCR (Optical Character Recognition)](#️-ocr-optical-character-recognition)
- [📊 Table Extraction](#-table-extraction-from-documents)
- [🔄 Document Format Conversion](#-document-format-conversion)
- [🤖 RAG & LLM Applications](#-rag--llm-applications)
- [🎯 Specialized Document Tasks](#-specialized-document-tasks--models)
- [📋 Annotation & Benchmarks](#-annotation-datasets--benchmarks)
- [🔧 Utilities & Helper Tools](#-utilities--helper-tools)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)

## 📖 Curated Lists & Resources

> 🌟 Excellent starting points with aggregated lists of tools, datasets, and research papers in the document AI space.

| 🛠️ Tool / Resource | 📝 Description | 🔗 Link |
| :--- | :--- | :--- |
| 🌟 **awesome-document-understanding** | A comprehensive, actively maintained list of papers, toolkits, datasets, and benchmarks related to document AI and extraction. A highly valuable "hidden gem" for anyone in the field. | [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tstanislawek/awesome-document-understanding) |
| 🏷️ **GitHub Topic: document-ai** | A GitHub-curated topic page featuring dozens of public repositories tagged with `document-ai`, showcasing a vibrant and active developer ecosystem with cutting-edge projects. | [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/topics/document-ai) |
| 📚 **Document-AI-Recommendations** | A repository containing a list of papers, datasets, and other resources for Document AI, maintained by SCUT-DLVCLab. | [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SCUT-DLVCLab/Document-AI-Recommendations) |
| 🎬 **Vision\_Audio\_and\_Multimodal\_Projects** | A broad collection of projects and resources, including many relevant to document intelligence and multimodal understanding. | [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DunnBC22/Vision_Audio_and_Multimodal_Projects) |
| 👥 **Unstructured-IO/community** | The community repository for the `unstructured` project, containing discussions, resources, and usage examples. | [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Unstructured-IO/community) |
| 📰 **parsing-prickly-pdfs** | Resources and code from a NICAR 2016 workshop on PDF parsing, useful for journalistic data extraction workflows. | [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ireapps/parsing-prickly-pdfs) |

## 🔧 General Document Processing & Pipelines

> ⚡ Frameworks and comprehensive toolkits designed to orchestrate complex document processing workflows by integrating multiple specialized models and tools.

| Tool | Description | Link |
| :--- | :--- | :--- |
| **unstructured** | An open-source Python toolkit for converting diverse document formats (PDFs, HTML, Word, etc.) into structured data optimized for language model workflows. Features modular ingestion, chunking, and pre-processing. | [GitHub](https://github.com/Unstructured-IO/unstructured) |
| **deepdoctection** | A Python orchestration framework that integrates various deep learning models for document extraction tasks, including layout analysis, OCR, and table recognition. It acts as a pipeline manager rather than implementing models itself. | [GitHub](https://github.com/deepdoctection/deepdoctection) |
| **Data Prep Kit** | An open-source project from IBM focused on cleaning, transforming, and tracing unstructured data to prepare it for use in Large Language Models (LLMs). | [GitHub](https://github.com/ibm/data-prep-kit) |
| **PDF-Extract-Kit** | A comprehensive toolkit for extracting high-quality content from PDFs. It integrates state-of-the-art models for layout detection (YOLO, LayoutLMv3), OCR (PaddleOCR), and table recognition. | [GitHub](https://github.com/opendatalab/PDF-Extract-Kit) |
| **pydoxtools** | An AI-based document analysis tool supporting various formats. It is designed for low resource consumption and includes features for table extraction and other downstream tasks. | [GitHub](https://github.com/pydoxtools/pydoxtools) |
| **OpenContracts** | An Apache2-licensed annotating platform designed to preserve document layout and export positional data, useful for creating labeled datasets for model training. | [GitHub](https://github.com/OpenContracts/opencontracts) |
| **BeeAI** | An open-source agent-to-agent platform from IBM for building multi-agent AI workflows. Relevant for orchestrating complex AI pipelines that include document intelligence tasks. | [GitHub](https://github.com/ibm/beeai) |

### **Document Intelligence Platforms**

These are end-to-end platforms designed to build, deploy, and manage document processing workflows, often with a low-code or no-code interface.

| Tool | Description | Link |
| :--- | :--- | :--- |
| **Unstract** | An open-source, no-code platform for building LLM-powered ETL pipelines and APIs to extract structured data from unstructured documents. Features a workflow studio and prompt studio. | [GitHub](https://github.com/Zipstack/unstract) |

### **Document Management Systems (DMS)**

These platforms provide comprehensive solutions for storing, versioning, managing, and searching enterprise documents.

| Tool | Description | Link |
| :--- | :--- | :--- |
| **OpenKM** | A mature, enterprise-grade open-source Document Management System (DMS) built in Java. It provides features for storage, version control, workflows, and advanced search. | [GitHub](https://github.com/openkm/openkm) |

### **SDKs & API Toolkits**

These are libraries designed to simplify interaction with commercial or third-party Document AI APIs.

| Tool | Description | Link |
| :--- | :--- | :--- |
| **python-documentai-toolbox** | A Python SDK from Google to simplify interactions with the Google Cloud Document AI API suite, wrapping common operations for easier use. | [GitHub](https://github.com/googleapis/python-documentai-toolbox) |

## 📄 PDF Text & Data Extraction

> 🔍 Libraries focused on the fundamental task of extracting text, images, and metadata from PDF files. The foundation for many document processing applications.

| Tool | Description | Link |
| :--- | :--- | :--- |
| **pypdf** | A widely used, pure-Python library for a full range of PDF manipulations: splitting, merging, cropping, encryption, and extracting text and metadata. It is actively maintained and serves as a successor to the original PyPDF2. | [GitHub](https://github.com/py-pdf/pypdf) |
| **PyMuPDF (fitz)**| A high-performance Python library praised for its speed and superior handling of text extraction, especially for paragraph chunking and retaining granular layout information. Also extracts images and metadata. | [GitHub](https://github.com/pymupdf/PyMuPDF) |
| **pypdfium** | A Python wrapper for Google's high-performance `PDFium` library. It is emerging as a top contender for fast and accurate text extraction from PDFs. | [GitHub](https://github.com/pypdfium/pypdfium2) |
| **pdfplumber** | A popular library for detailed extraction of text characters, lines, rectangles, and tables from PDFs. Its visual debugging features are particularly useful for analyzing document structure. | [GitHub](https://github.com/jsvine/pdfplumber) |
| **pdfminer.six** | A community-maintained fork of the original `pdfminer`, focused on extracting and analyzing text content and layout information from PDF documents. | [GitHub](https://github.com/pdfminer/pdfminer.six) |
| **Apache PDFBox** | A mature and widely-used open-source Java library for working with PDF documents. It supports content extraction, PDF creation, manipulation, and more. | [Homepage](https://pdfbox.apache.org/) |
| **PdfPig** | A comprehensive open-source library for extracting text and other content from PDF files, written in C# for the .NET ecosystem. | [GitHub](https://github.com/UglyToad/PdfPig) |
| **borb** | A pure-Python library for reading, writing, and manipulating PDFs. It represents the PDF's structure hierarchically, similar to JSON, which can simplify complex operations. | [Homepage](https://borb.io/) |
| **PDFium** | Google's open-source C++ library for rendering and parsing PDF files. It's the core engine behind Google Chrome's PDF viewer and can be used for robust text and metadata extraction. | [Homepage](https://pdfium.googlesource.com/pdfium/) |
| **pymupdf4llm** | An open-source tool built on PyMuPDF to extract and convert PDF content into Markdown optimized for Large Language Models (LLMs), preserving semantic structure. | [Homepage](https://pymupdf.readthedocs.io/en/latest/pymupdf4llm/) |

### **Layout-Aware Document Parsing**

This category includes advanced tools that leverage deep learning to understand the visual and structural layout of a document, going beyond simple text extraction to identify elements like paragraphs, lists, titles, and figures.

| Tool | Description | Link |
| :--- | :--- | :--- |
| **LayoutParser** | A deep learning toolkit for Document Image Analysis (DIA). It provides a unified API and pre-trained models for detecting and analyzing the layout of document images. | [GitHub](https://github.com/Layout-Parser/layout-parser) |
| **LayoutLM / UniLM** | A family of powerful, pre-trained multimodal transformer models from Microsoft (including LayoutLMv3 and LiLT) that combine text, layout, and visual information for state-of-the-art document understanding tasks. | [GitHub](https://github.com/microsoft/unilm) |
| **LiLT** | Language-independent Layout Transformer for universal document layout analysis, extending LayoutLM to work effectively across multiple languages without language-specific training. | [GitHub](https://github.com/jpWang/LiLT) |
| **ViBERTgrid-PyTorch** | A model that grids document pages and applies a BERT-based architecture to understand document layout and structure. | [GitHub](https://github.com/ZeningLin/ViBERTgrid-PyTorch) |
| **RFUND** | A project from SCUT-DLVCLab focused on form understanding with visually-rich features. *Note: Repository appears to be a research artifact.* | [GitHub](https://github.com/SCUT-DLVCLab/RFUND) |
| **Donut** | An OCR-free Document Understanding Transformer (`clovaai/donut`) that directly parses a document image into a structured output (e.g., JSON) without an explicit OCR step, excelling at information extraction tasks. | [GitHub](https://github.com/clovaai/donut) |
| **Docling** | A tool designed to accurately interpret PDF content by considering its layout, reading order, tables, code blocks, and images. Now a commercial product. | [Homepage](https://docling.ai/) |
| **Doc2Graph** | A framework that uses Graph Neural Networks (GNNs) for task-agnostic document understanding, leveraging the structural and relational patterns within a document. | [GitHub](https://github.com/Doc2Graph/Doc2Graph) |

## 👁️ OCR (Optical Character Recognition)

> 🖼️ Essential engines for converting scanned documents or images of text into machine-readable text. Modern OCR tools often incorporate deep learning for higher accuracy.

| Tool | Description | Link |
| :--- | :--- | :--- |
| **SuryaOCR** | A state-of-the-art OCR engine demonstrating superior accuracy and speed on GPUs, especially for complex documents. Features built-in layout detection and reading order extraction. Licensed under GPL 3.0. | [GitHub](https://github.com/VikParuchuri/surya) |
| **Tesseract** | The de facto open-source OCR engine. It is highly reliable, CPU-friendly, supports numerous languages, and has a permissive Apache 2.0 license, making it a popular choice for many applications. | [GitHub](https://github.com/tesseract-ocr/tesseract) |
| **PaddleOCR** | A strong all-around OCR toolkit with multilingual support that delivers high accuracy. It performs well on CPUs and is robust against image distortions and complex layouts. | [GitHub](https://github.com/PaddlePaddle/PaddleOCR) |
| **OCRmyPDF** | A crucial utility that adds a searchable text layer to scanned PDF files by running an OCR engine (typically Tesseract) on the document images and embedding the recognized text. | [GitHub](https://github.com/ocrmypdf/OCRmyPDF) |
| **EasyOCR** | A popular Python library that provides a ready-to-use OCR model with support for a wide range of languages. | [GitHub](https://github.com/JaidedAI/EasyOCR) |

## 📊 Table Extraction from Documents

> 📋 Tools specifically optimized for the challenging task of identifying and extracting structured tabular data from both text-based and image-based documents.

| Tool | Description | Link |
| :--- | :--- | :--- |
| **Camelot** | A powerful Python library for extracting tables from text-based PDFs. It offers high control through configurable settings, provides accuracy metrics, and exports to pandas DataFrames and various file formats (CSV, JSON, etc.). Includes a web UI called *Excalibur*. | [Homepage](https://camelot-py.readthedocs.io/) |
| **Tabula** | A well-known open-source tool and Python library for liberating data tables trapped inside PDF files. It is a popular choice for its simplicity and effectiveness with text-based PDFs. | [Homepage](https://tabula.technology/) |
| **Table Structure Recognition** | A research project (`whn09/table_structure_recognition`) that uses modern object detection models (YOLOv5/v8) for advanced table detection and structure recognition from images. | [GitHub](https://github.com/whn09/table_structure_recognition) |
| **Tabulo** | A tool specifically designed to extract tables from images, useful when dealing with scanned documents or screenshots. | *No public repository link found in sources.* |

### **Document Format Conversion**

This category contains tools designed to convert documents from one format to another, with a focus on preserving structure for downstream use.

| Tool | Description | Link |
| :--- | :--- | :--- |
| **Marker** | A versatile tool that converts various formats (PDF, EPUB, DOCX, etc.) into clean, LLM-friendly Markdown. It is optimized for speed and multilingual support. | [GitHub](https://github.com/VikParuchuri/marker) |
| **Pandoc** | A universal document converter. While not a PDF-first tool, it's often used in workflows (e.g., PDF → Word via Adobe Acrobat → Markdown via Pandoc) to achieve high-fidelity conversions. | [Homepage](https://pandoc.org/) |
| **Markitdown** | A Microsoft open-source Python library to convert a wide range of file types (PDF, Office, images, audio) into clean, LLM-friendly Markdown. | [GitHub](https://github.com/microsoft/markitdown) |
| **pdf2md.morethan.io** | A free, privacy-focused offline converter that processes PDF-to-Markdown conversions directly in the browser without uploading files to a server. | [Homepage](https://pdf2md.morethan.io/) |
| **NoteGPT.io Converter** | A free online PDF-to-Markdown converter that includes AI features like summarization and mind maps. Praised for its speed and format retention. | [Homepage](https://notegpt.io/pdf-to-markdown-converter) |

### **RAG & LLM Applications**

These are tools and frameworks focused on Retrieval-Augmented Generation (RAG) and building applications for interacting with documents using LLMs.

| Tool | Description | Link |
| :--- | :--- | :--- |
| **VDocRAG** | A Retrieval-Augmented Generation (RAG) framework from NTT tailored for visually-rich documents, enabling Q&A over complex layouts. | [GitHub](https://github.com/nttmdlab-nlp/VDocRAG) |
| **DocGPT** | An open-source application that enables users to have interactive conversations with their documents using Large Language Models. | [GitHub](https://github.com/NirmalNagaraj/DocGPT) |
| **daniel** | An open-source, local-first alternative for document interaction (chatting with documents) powered by LLMs. | [GitHub](https://github.com/Shulk97/daniel) |

### **Specialized Document Tasks & Models**

This category includes models and projects designed for highly specific document intelligence tasks beyond general parsing or extraction.

| Tool | Description | Link |
| :--- | :--- | :--- |
| **SlideVQA** | A project focused on Visual Question Answering for slides and presentations, understanding both text and visual elements. | [GitHub](https://github.com/nttmdlab-nlp/SlideVQA) |
| **GOSE** | A model for Grid-based Object Spotting and Extraction, specializing in detecting and recognizing text in documents. | [GitHub](https://github.com/chenxn2020/GOSE) |
| **PEneo** | A research project focused on the specialized task of price tag extraction and linking from documents or images. | [GitHub](https://github.com/ZeningLin/PEneo) |

### **Annotation, Datasets & Benchmarks**

These are tools for creating labeled data, benchmark datasets for model evaluation, and projects for performance comparison.

| Tool | Description | Link |
| :--- | :--- | :--- |
| **pawls** | PDF Annotations with Labels and Structure. An annotation tool from the Allen Institute for AI for creating structured, labeled datasets from PDFs. | [GitHub](https://github.com/allenai/pawls) |
| **ReadingBank** | A benchmark dataset consisting of 1.4 million annotated pages from 500 academic articles for deep learning-based document analysis. | [GitHub](https://github.com/doc-analysis/ReadingBank) |
| **webvicob** | A web-visual-corpora benchmark from Clova AI for various document AI tasks, including layout analysis and information extraction. | [GitHub](https://github.com/clovaai/webvicob) |
| **pdf-text-extraction-benchmark** | A project for benchmarking the performance and accuracy of various Python-based PDF text extraction libraries. | [GitHub](https://github.com/jbarlow83/pdf-text-extraction-benchmark) |

### **Utilities & Helper Tools**

Miscellaneous helper tools for common document processing tasks.

| Tool | Description | Link |
| :--- | :--- | :--- |
| **Born digital pdf scanner** | A command-line utility to determine if a PDF file is 'born-digital' (text-based) or scanned (image-based). | [GitHub](https://github.com/colarusso/born-digital-pdf-scanner) |

---

## 🤝 Contributing

Your contributions are always welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

### How to Contribute

1. 🍴 Fork this repository
2. 🌟 Add your awesome tool/library to the appropriate section
3. 📝 Ensure your addition follows the format: `| 🎯 **Tool Name** | Description | [![GitHub](badge-url)](link-url) |`
4. ✅ Make sure the tool is:
   - **Open source** (or has significant free features)
   - **Actively maintained** (recent commits/releases)
   - **Well documented**
   - **Relevant** to document processing/intelligence
5. 🚀 Create a Pull Request

### Quality Standards

- 📚 **Documentation**: Tool should have clear documentation
- 🔄 **Activity**: Recent activity (commits, releases, or issues)
- ⭐ **Community**: Some level of community adoption
- 🎯 **Relevance**: Direct relevance to document processing/AI

## 📜 License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

This work is licensed under a [Creative Commons Zero v1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0) license.

---
## 🌟 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Apexiq.ai/Awesome_pdf_prarser&type=Date)](https://star-history.com/#Apexiq.ai/Awesome_pdf_prarser&Date)

---

<div align="center">

**Made with ❤️ by the document processing community**

[⬆️ Back to Top](#awesome-pdf-parser--document-intelligence-tools-)

</div>