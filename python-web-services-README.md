# 🌐 Python Web Services & API Data Processing

A collection of Python exercises demonstrating real-world API interaction,
data parsing, and web service integration — skills directly relevant to
biomedical data pipelines and precision medicine informatics.

---

## 📁 Contents

### Week3-1.py — XML Data Parsing
Fetches data from a remote URL and parses **XML** using `xml.etree.ElementTree`.
Extracts comment counts and computes their sum.

```python
# Key concepts: urllib, XML parsing, ElementTree
python Week3-1.py
# Enter URL when prompted: http://py4e-data.dr-chuck.net/comments_42.xml
```

### Week3-2.py — JSON Data Parsing
Same task as above but with **JSON** format using Python's `json` module.
Demonstrates format-agnostic data retrieval.

```python
# Key concepts: urllib, JSON parsing, data aggregation
python Week3-2.py
# Enter URL when prompted: http://py4e-data.dr-chuck.net/comments_42.json
```

### Week3-3.py — Geolocation API Integration
Queries a **REST geolocation API** (Geoapify proxy) to retrieve two-character
country codes for any location. Handles edge cases like ocean coordinates
where no country code exists.

```python
# Key concepts: REST API, JSON, error handling, urllib.parse
python Week3-3.py
# Enter location when prompted: e.g. "Istanbul" or "Atlantic Ocean"
```

---

## 🧠 Key Skills Demonstrated

- HTTP requests with `urllib`
- Parsing structured data: **XML** and **JSON**
- REST API integration and query parameter encoding
- Graceful error handling (`try/except`, `.get()` for missing keys)
- SSL context management

---

## 🔗 Relevance to Precision Medicine

These data-handling skills are directly applicable to:
- Querying **genomic databases** (NCBI, Ensembl REST API, UniProt)
- Parsing **EHR/clinical data** in XML/JSON (HL7 FHIR format)
- Building automated **biomedical data pipelines**

---

## 🛠️ Requirements

```bash
pip install urllib3
```
Standard library only — no additional packages needed.

---

