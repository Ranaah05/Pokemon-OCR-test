# Pokémon OCR Scanner

An experimental project to build an OCR pipeline for identifying **Pokémon trading cards** from images and retrieving real-time card price data.

## Project Overview
- **OCR Prototype**: Developed using Python, Jupyter Notebook, and OpenCV to detect and extract card names from images.  
- **Preprocessing**: Implemented autocropping and contour detection to improve OCR accuracy.  
- **API Integration**: Connected with [PokémonTCG.io](https://pokemontcg.io/) and [PokemonPrice](https://pokemonpricetracker.com/) APIs to fetch set information and live pricing data.  
- **Version Control**: Used Git feature branches to separate **OCR experiments** and **API testing** for modular development.

## Branches
- `feature/ocrprac-testing` → Experiments with image preprocessing and OCR.  
- `feature/api-testing` → Experiments with PokémonTCG.io and PokemonPrice APIs.  
- `main` → Placeholder branch, currently nothing at the moment  

## CurrentTech Stack
- **Python 3**
- **OpenCV**
- **Jupyter Notebook**
- **REST APIs** (PokémonTCG.io, PokemonPrice)

##  Example Workflow
1. Input: Pokémon card image  
2. Preprocessing: Autocropping + contour detection  
3. OCR: Extract Pokémon name from card  
4. API Lookup: Retrieve set info + real-time price  

*(Screenshots  coming soon!)*

## Status
This is a **prototype / work in progress**. The goal is to evolve from experimental notebooks into a reliable OCR pipeline that can scan card images and return pricing data.  

## Future Improvements
- Improve OCR accuracy with deep learning-based models (e.g., Tesseract fine-tuning, EasyOCR, or custom CNNs).  
- Add unit tests and better error handling.  
- Build a simple CLI or web demo for user-friendly scanning.  

---
(https://github.com/Ranaah05)*  
