# BOM Auto-Fill

Fills the Dunnes BOM "New" tab (columns A to T) from the PO PDF and the CBD costing sheet.

How to use: open the site, add the BOM Excel, the PO PDF and the CBD sheet, click **Fill the BOM**, then download the filled Excel file.

- Everything runs inside the visitor's browser (Python via Pyodide). Files are never uploaded to any server.
- The server only sends static files, so any number of people can use it at the same time.
- Files: `index.html` (the page), `pylib.json` (the Python tool and libraries: bom_tool.py, pdfplumber, pdfminer.six, openpyxl, xlrd, charset-normalizer, et_xmlfile, with their licences), `pyodide/` (Pyodide 314.0.8 engine, MPL-2.0, https://pyodide.org).
