# Installazione e Configurazione

### INSTALLAZIONE:
Per poter utilizzare il braccio robotico _niryo_ è necessario:
1) Scaricare **img** e **niryo studio** dal seguente [link](https://niryo.com/download/).
2) Flashare l'**img** per il raspberry presente all'interno del Niryo.
3) Installare Niryo Studio.

---

### COLLEGAMENTO PC - NIRYO CON SSH:
Può essere necessario collegarsi con il raspberry presente nel Niryo con il protocollo SSH. Per poterlo fare bisogna:
1) Collegarsi alla rete hotspot, generata in automatico dal Niryo (SSID: `NiryoRobot ...`, PASSWORD: `niryorobot`)
2) Collegarsi con ssh (USERNAME: `niryo`, PASSWORD: `robotics`, IP: (`10.10.10.10` → rete hotspot, `169.254.200.200` → se connesso in ethernet con dhcp disabilitato))

---

### INFORMAZIONI
Il braccio robotico **Niryo** presenta 6 motori ed un sensore magnetico _(Collision detection sensorMagnetic sensor (motor) AS5600)_.
Inoltre su ogni motore sono presenti delle **porte micro USB** (per maggiori informazioni consultare il seguente [link](https://niryo.com/docs/niryo-one/update-your-robot/update-niryo-steppers/)).

---

### SPEGNIMENTO NIRYO
Per poter spegnere il **Niryo** premere il pulsante posizionato sopra la base e dopo che il led è diventato rosso posizionare l'interruttore su _off_.

---

### GUIDE
Per ulteriori informazioni consigliamo di leggere la [guida_niryo](https://docs.niryo.com/product/ned/v3.1.1/en/source/software/niryo_studio.html) e le [specifiche tecniche](https://github.com/NiryoBuild/Installazione-e-Configurazione/blob/main/specifiche_meccaniche.pdf).
In caso sia necessario utilizzare `Python` installare la seguente [libreria](https://pypi.org/project/pyniryo/#installation) e eventualmente consultare la [guida_pyniryo](https://docs.niryo.com/dev/pyniryo/v1.0.5/en/source/examples/examples_vision.html).

---

### COMPONENTI AGGIUNTIVI
Per ottimizzare al meglio il Niryo abbiamo installato alcuni componenti aggiuntivi:
- Una punta in resina per la calibrazione dei _workspace_ dato che non era stata acquistata quella originale Niryo
<img scr="./immagini/punta_calibrazione.jpeg" width="40%"> <img scr="./immagini/punta_calibrazione_2.jpeg" width="40%">
- Un prolungamento del braccio per creare un appoggio fisso alla telecamera che non essendo originale Niryo non poteva essere collegata.
<img scr="./immagini/prolungamento_braccio.jpeg" width="40%"> <img scr="./immagini/prolungamento_braccio_2.jpeg" width="40%">
---

### AUTORI

- [@GabrieleFerrero](https://github.com/GabrieleFerrero)
- [@VittoriaDutto](https://github.com/vikydutto)
- [@AnthonyRuggero](https://github.com/AnthonyRuggero)
- [@IsabellaBianco](https://github.com/IsabellaBianco)
- [@AndreaBosticardo](https://github.com/Bosticardo-Andrea)
