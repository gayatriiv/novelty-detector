# Scientific Paper Contradiction & Novelty Detector

## Overview
This project detects semantic contradictions and novelty between scientific papers using transformer-based Natural Language Inference (NLI) and sentence embeddings.

## Features
- PDF text extraction
- Sentence-level semantic similarity
- Novelty scoring via cosine similarity
- Disagreement detection using BART-MNLI
- Visualization of novelty distribution

## Models Used
- sentence-transformers (all-MiniLM-L6-v2)
- facebook/bart-large-mnli

## Methodology
1. Extract text from PDFs
2. Segment into sentences
3. Generate embeddings
4. Compute cosine similarity
5. Apply NLI for contradiction detection

## Future Improvements
- Use SciBERT for domain-specific NLI
- Add FAISS for scalable retrieval
- Deploy as Streamlit web app
