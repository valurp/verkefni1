# verkefni1
Stórt verkefni 1

Upplýsingar um hvernig keyra skuli verkefnið:
  "dependencies": 
    "node-sass": "^4.5.3"


Lýsing á uppsetningu verkefnisins:
Verkefnið eru þjrár html síður, index.html, um.html og kaupa.html. Í möppunni eru allar skrár og myndir.     
"browser-sync": "browser-sync start --server --files index.html styles.scss",
"sass": "node-sass um.css styles.css styles.scss lstyles.css lstyles.scss -w",
"dev": "npm-run-all --parallel sass browser-sync",
"lint": "stylelint *.scss scss/*.scss --syntax scss"


Unnið af:
Kári Viðar Jónsson
Loftur Einarsson
Valur Páll Stefán Valsson
