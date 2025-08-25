# Vendor Standardization with Snowflake Cortex AI

AI-powered vendor standardization using Snowflake Cortex AI and LLMs. Demonstrates corporate hierarchy extraction (L1/L2/L3) from messy vendor names with 80%+ accuracy using few-shot prompting and structured JSON outputs.

## 🎯 **Project Overview**

This repository contains a **Snowflake Notebook** that demonstrates how to use **Snowflake Cortex AI's `AI_COMPLETE` function** to automatically standardize vendor names into a clean 3-level corporate hierarchy:

- **L1 (Global Parent)**: Ultimate holding company (e.g., "IBM", "BNP Paribas Group")
- **L2 (Regional Parent)**: Regional subsidiary (e.g., "IBM Canada", "Arval Belgium") 
- **L3 (Local Entity)**: Specific legal entity (e.g., "IBM CANADA LTD")

## 🚀 **Key Results**

- ✅ **80%+ L1 accuracy** on real-world vendor data
- ✅ **Cost-effective processing** at under $10 per 1,000 vendors on LLM inference
- ✅ **Production-ready implementation** using pure LLM reasoning
- ✅ **Scalable batch processing** for enterprise datasets

## 📊 **What's Included**

### **VENDOR_STANDARDIZATION_AI_DEMO.ipynb**
A comprehensive Snowflake Notebook showcasing:
- **Business problem context** and solution approach
- **Live AI_COMPLETE demonstrations** with structured JSON outputs
- **Batch processing** of 220 real vendor names
- **Intelligent fuzzy matching** for realistic accuracy assessment
- **Cost analysis** and enterprise scaling projections
- **Production deployment guidance**

### **deploy_vendor_demo.sql** (Optional)
Not included in repo, contact your Snowflake Solution Engineer.
