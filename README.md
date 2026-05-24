## Koda struktūra

- `main.py` – galvenais izpildes skripts
- `src/git_analyzer.py` – Git izmaiņu analīze
- `src/prioritizer.py` – testu prioritizēšana pēc pārklājuma datiem
- `src/risk_scorer.py` – riska novērtēšana
- `src/runner.py` – testu izpilde ar pytest
- `src/reporter.py` – HTML atskaites ģenerēšana

## Nepieciešamās bibliotēkas
Lai rīku varētu startēt ir nepieciešamas trīs Python bibliotēkas:
- gitpython
- coverage
- pytest

Tās var uzstādīt ar komandu:

`pip install gitpython coverage pytest`
## Rīku startēšana
Rīku var startēt ar komandu

`python main.py`

Rīkam ir iespējams manuāli norādīt riska līmeni ar komandu:
- `python main.py --risk LOW`
- `python main.py --risk MEDIUM`
- `python main.py --risk HIGH`
