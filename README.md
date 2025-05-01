# 📘 Assignment 2 – JMeter Test Plan

This repository contains a JMeter test plan for Assignment 2 using a full CRUD sequence.

## 🔁 Test Flow

1. **POST** – Create a book using CSV input  
2. **GET** – Retrieve the created book   
3. **DELETE** – Delete the book  
4. **GET** – Attempt to retrieve the deleted book (expect 404)

## 📂 Files

- `Book Api.jmx` – Main JMeter test plan  
- `books-data.csv` – Input data for book creation  
- `README.md` – Project description

## 🔧 Features

- CSV Data Set Config  
- JSON extractors & assertions  
- Dynamic timestamps with JSR223  
- Full response validation for each request
