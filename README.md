# A simple tool for moderating localization from xcode project

### Requirement:
- Python 2.7
- xlsxwriter: http://xlsxwriter.readthedocs.io/
- xldr: https://pypi.python.org/pypi/xlrd
- Update path os.walk('./YourAwesomeProject/')

Run: `python export-text.py`

Then, update lang.xlsx as your demand

Run: `python import-text.py` to import it into project
