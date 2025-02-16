# WatchDog - "/help" base

mi bro aca te doy como mrd configurar el archivo porq te puede hacer estallar la cabesa todo

## INSTALACION DE CP

primero descargate el node js

```bash
https://nodejs.org/es/download
```

de aca programa tu bot bro, no te vy a dar el code

## donde y como se pone la wea

```
botsito
└── commandos_del_papu
    ├── principal
    │   └── help.js
    └── otros_comandos
        └── cp_farmeo.js
```

sino modifica esta parte
```js
const commandsDir = path.join(__dirname, '../'); 
```
esta wea en especifco
```js
'../'
```