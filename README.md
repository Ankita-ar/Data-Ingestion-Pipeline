# 🚀 Data Ingestion & Processing Assignment

This project demonstrates a complete data ingestion pipeline using a large CSV (2+ GB) dataset in a resource-constrained environment like Google Colab. The goal is to evaluate different data reading methods, validate data structure, and efficiently export the processed file.

---

## 📝 Assignment Objectives

- ✅ Read a large CSV file using:
  - Pandas
  - Dask
  - Modin (Ray backend)
- ✅ Compare performance across frameworks
- ✅ Clean column names (remove special characters and whitespaces)
- ✅ Define schema and structure using YAML
- ✅ Validate file structure (column names and count)
- ✅ Export processed data as pipe-separated `.txt.gz` file
- ✅ Generate file summary: rows, columns, and file size

---

## 📂 Project Structure

- `assignment_ingestion.ipynb` – Full implementation notebook
- `processed_output.txt.gz` – Final processed file (pipe-separated, gzipped)
- `schema.yaml` – YAML schema (column names, separator, structure)
- `README.md` – This documentation

---

## ⚙️ Technologies Used

- Python
- Pandas, Dask, Modin (Ray)
- PyYAML
- Google Colab
- Google Drive (as external storage)

---

## 📊 Results Summary

- ✅ Efficient file processing in Google Colab (2GB+ file)
- ✅ Output file size: ~200MB (gzip)
- ✅ Compatibility with low-resource environments

---

## 📎 Links

- 📘 [Colab Notebook](https://colab.research.google.com/drive/14tHX6rekaBnoHcRrXwJC3VAvIzzbVOVj)

---

## 🙌 Acknowledgements

This project was completed as part of a practical assignment on data engineering principles and large-scale data handling.
