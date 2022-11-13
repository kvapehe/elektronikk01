# Info om json-fil
Tanken er at denne har tre valg pr dd.  
Valgene er serieresistans, parallell-capaistans og serie-induktans  
Dette fordi disse tre kretsene håndteres likt  
For hver oppgave er det noen enkle spørsmål  
og flere gyldige svar  

Ved å velge vanskelighetsgrad kan en velge andre oppgaver som kan  
være mer kompliserte.

# JSON-struktur
{
  "jsonstruktur": {
    "oppgavetype": [
      {
        "generell": "Et navn",
        "beskrivelse": "En beskrivelse",
        "nivaa": [
          1,
          2,
          3
        ],
        "spenning": 0,
        "strom": 0,
        "v1": 0,
        "v2": 0,
        "v3": 0,
        "rettsvar01": 135,
        "rettsvar02": 150,
        "rettsvar03": 120,
        "rettsvar04": 0.135
      },
      {
        "resistans_serie": "3 resistanser",
        "beskrivelse": "Resistanser i serie. Bruker tre stk resistanser Finn En av resistansverdiene",
        "nivaa": [
          1,
          2,
          3
        ],
        "spenning": 25,
        "strom": 0.037,
        "v1": 240,
        "v2": 300,
        "v3": 0,
        "rettsvar01": 135,
        "rettsvar02": 150,
        "rettsvar03": 120,
        "rettsvar04": 0.135,
      },
      {
        "kondensator_parallell": "3 Kondensatorer i parallell",
        "beskrivelse": "Resistanser i serie. Bruker tre stk resistanser Finn En av resistansverdiene",
        "nivaa": [
          1,
          2,
          3
        ],
        "spenning": 25,
        "strom": 0.037,
        "v1": 22,
        "v2": 10,
        "v3": 0
      },
      {
        "spole_serie": "Peter",
        "beskrivelse": "Resistanser i serie. Bruker tre stk resistanser Finn En av resistansverdiene",
        "nivaa": [
          1,
          2,
          3
        ],
        "spenning": 25,
        "strom": 0.037,
        "v1": 22,
        "v2": 10,
        "v3": 0
      }
    ]
  }
}