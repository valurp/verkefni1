# verkefni1
Stórt verkefni 1

Upplýsingar um hvernig keyra skuli verkefnið: <br />
  "dependencies": 
    "node-sass": "^4.5.3"


Lýsing á uppsetningu verkefnisins: <br />
Verkefnið eru þrjár html síður, index.html, um.html og kaupa.html. Í möppunni eru allar skrár og myndir.<br />
"browser-sync": "browser-sync start --server --files index.html styles.scss",
"sass": "node-sass um.css styles.css styles.scss lstyles.css lstyles.scss -w",
"dev": "npm-run-all --parallel sass browser-sync",
"lint": "stylelint *.scss scss/*.scss --syntax scss"


Unnið af: <br />
Kári Viðar Jónsson <br />
Loftur Einarsson <br />
Valur Páll Stefán Valsson
