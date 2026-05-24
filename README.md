# Customer Data Transformation using Mapping Data Flow

## Project Overview
This project demonstrates complex data transformation using **Mapping Data Flow** in Azure Data Factory following **Medallion Architecture** (Bronze → Silver → Gold).

## Key Features
- Bronze to Silver transformation (Cleaning & Standardization)
- Silver to Gold transformation (Aggregation & Business Logic)
- Schema Drift handling
- Join, Filter, Aggregate, Derived Column transformations

## Architecture
- **Bronze Layer**: Raw data
- **Silver Layer**: Cleaned data
- **Gold Layer**: Aggregated insights

## Technologies Used
- Azure Data Factory (Mapping Data Flow)
- Azure Data Lake Storage Gen2
- Delta Lake

## Screenshots
1)[Bronze to Silver over Pipeline]<img width="509" height="323" alt="image" src="https://github.com/user-attachments/assets/6a54a0c5-9ab3-42bf-8e6e-91216516d475" />
*Successful run of Customer Bronze to Silver transformation pipeline*

2)[Silver to Gold Pipeline]<img width="496" height="299" alt="image" src="https://github.com/user-attachments/assets/947dcd86-53c3-43c3-ab1d-459dd18965d4" />
Successful run of Silver to Gold aggregation pipeline

3)[Mapping Data Flow<img width="561" height="329" alt="image" src="https://github.com/user-attachments/assets/76fff8d4-5c3d-4ec5-aa86-c6c5c764e1de" />
<img width="566" height="319" alt="image" src="https://github.com/user-attachments/assets/0f9a3b57-0dde-4faf-ac50-b9b41b71dc84" />
Customer Data Transformation using Mapping Data Flow



## How to Run
1. Update Linked Services
2. Update Datasets
3. Debug and run pipelines

## Learnings
- Mapping Data Flow in real projects
- Implementing Medallion Architecture
- Complex transformations without coding

---
**Made by Rajendra K**  
Aspiring Azure Data Engineer | Open to UK Relocation
