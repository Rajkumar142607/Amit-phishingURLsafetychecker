# Phishing URL Safety Checker

**Student:** Amit  
**Program:** IBM SkillsBuild Cyber Security BootCamp 2026 (BharatCares)

## Project description
This small Python project checks a URL for common warning signs associated with phishing. It gives a risk score, a label, and reasons for the score. It does not visit the URL or verify whether a website is actually safe.

## Technologies used
- Python 3
- Jupyter Notebook
- Built-in Python modules: `urllib.parse` and `ipaddress`

## Dataset
This first version uses example URLs written directly in the notebook. It does not train a machine-learning model and does not require an external dataset. The examples are not a labelled real-world dataset.

For further study, the UCI Machine Learning Repository has a public Phishing Websites dataset:
https://archive.ics.uci.edu/dataset/327/phishing+websites

If you extend the project using that dataset, review its documentation and terms and update the report to explain the data actually used.

## Files
- `Amit_PhishingURLSafetyChecker.ipynb` — project code and explanations
- `requirements.txt` — dependency notes
- `Amit_ProjectReport.docx` — project report

## Setup and run
1. Install Python 3 and Jupyter Notebook, or use an online notebook environment.
2. Open `Amit_PhishingURLSafetyChecker.ipynb`.
3. Run the notebook cells from top to bottom.
4. Try the sample URLs or enter a URL as text when prompted.

No third-party Python libraries are needed for the project code. Jupyter is needed to open and run the notebook.

## Understanding the result
The score is based on a few simple rules, including URL length, an IP address as host, an `@` symbol, URL-shortener domains, and selected words. The score is only a learning aid, not a reliable verdict.

## Safety note
Do not open suspicious links just to test them. A low score does not guarantee safety, and HTTPS does not prove that a site is legitimate. Follow your college or organisation's security guidance.
