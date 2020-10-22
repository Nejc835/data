## How to update health_centers.csv
___
In this folder run:
1. `python3.7 -m venv venv` or `virtualenv -p python3 venv`
1. `source venv/bin/activate`
1. `pip install -r ../requirements.txt`
1. `python process.py` or `python process.py --cached` if you want to work with already downloaded XLS files (dev mode)


## CSV field meaning
___
| CSV field | Meaning (EN) | Meaning (SI, original meaning) |
|-|-|-|
| examinations.medical_emergency | No. emergency medical examinations | Št. pregledov NMP |
| examinations.suspected_covid | No. examinations of suspected COVID | Št. pregledov  suma na COVID |
| phone_triage.suspected_covid | No. suspected COVID without examination (telephone triage) | Št. sumov na COVID brez pregleda (triaža po telefonu) |
| tests.performed | No. COVID tests performed | Št. opravljenih testiranj COVID |
| tests.positive | No. positive COVID | Št. pozitivnih COVID |
| sent_to.hospital | No. sent to hospital | Št. napotitev v bolnišnico |
| sent_to.self_isolation | No. sent into self-isolation | Št. napotitev v samoosamitev |
