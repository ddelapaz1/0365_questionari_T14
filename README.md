# Qüestionari · 1.1 Conceptes bàsics de radiofreqüència

Qüestionari d'autoavaluació del **mòdul 0365 – Radiocomunicacions** (EE30), generat a partir del banc de preguntes de Moodle.

- Retroacció immediata després de cada pregunta: explicació i, si l'opció triada no és correcta, per què.
- Nota final sobre 10: +1 per encert, −0,25 per error (com al Moodle) i puntuació proporcional a les preguntes d'aparellar i d'ordenar.
- Preguntes i opcions barrejades a cada intent.

Web: https://ddelapaz1.github.io/0365_questionari_T14/

## Regenerar les dades

```bash
python3 tools/moodle2quiz.py moodle/T1.1_conceptes_basics_RF.xml data/t1-1-conceptes-rf.js --id t1-1-conceptes-rf --title "1.1 Conceptes bàsics de radiofreqüència"
```

La retroacció de cada opció surt de l'XML de Moodle. Les preguntes d'ordenar es mostren com un aparellament de posicions.
