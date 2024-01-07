---
layout: project
type: project
published: true
image: img/receipt-parse.jpeg
title: Receipt Parse
permalink: projects/kipa
date: 2023
labels:
  - Visualization
  - Big Data
  - Data Pipeline
  - Large Language Model
  - StreamLit
summary: People are continually making purchases from stores. Thus, examining receipts allows for valuable insights into the types of stores and products that individuals purchase/frequent.

This converts receipts through a data pipeline where the paper receipts information is displayed in an Optical Character Recognition (OCR) - text file format and converted into JSON objects that represent how humans may classify receipts with the assistance of Large Language Model (LLM) ChatGPT4 (latest version 2023). Upon creation of JSONs, K-Nearest Neighbors was used to assist in the classification of vendor and product categories.

The findings are displayed through visualizations on a Dashboard.

Team: Jeremiah Dy, Kylie Higashionna, Grayson Levy, Amanda Nitta

projecturl: https://receipt-classification-visualization.streamlit.app/
---