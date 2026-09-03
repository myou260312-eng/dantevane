# dantevane
Complete End-to-End RAG Pipeline:  Code  Question → Data Ingestion → Vector Embedding → Semantic Search → LLM Processing → Confidence Eval → Answer + Sources + Reasoning   Example Query:  Question: "Did Einstein win a Nobel Prize for relativity?"  Answer: "No, he won it for the photoelectric effect"  Confidence: HIGH  Sources: Wikipedia + citation 

---

## Projects

digital-twins_init.py/
│
├── README.md
├── LICENSE
├── requirements.txt
├── .gitignore
│
├── src/
│   ├── __init__.py
│   ├── digital_twin.py
│   ├── vector_addition.py
│   └── config.py
│
├── examples/
│   ├── vector_addition_demo.py
│   └── digital_twin_demo.py
│
├── tests/
│   ├── __init__.py
│   └── test_vector_addition.py
│
├── docs/
│   └── rocm-module-4.md
│
└── images/
    ├── 01_module4_objectives.jpg
    ├── 02_host_device_programming.jpg
    ├── 03_vector_addition_schema.jpg
    └── 04_vector_addition_kernel.jpg

## ROCm / HIP Learning Reference

### Module 4 Objectives
![Module 4 Objectives](images/01_module4_objectives.jpg)

### Host-Device Programming
![Host-Device Programming](images/02_host_device_programming.jpg)

### Vector Addition Schema
![Vector Addition Schema](images/03_vector_addition_schema.jpg)

### Vector Addition Kernel
![Vector Addition Kernel](images/04_vector_addition_kernel.jpg)
