# Ultimi aggiornamenti / Latest updates

## 16 novembre 2026 — PCB di alimentazione GUARDIAN POWER

Completato il progetto della scheda di alimentazione dedicata **GUARDIAN POWER Rev I**, pensata per sostituire la millefori del prototipo e rendere più ordinati i collegamenti. È prevista anche una predisposizione hardware per un eventuale sensore di pressione BMP280; la relativa funzione firmware non è ancora integrata.

I controlli delle regole di progetto in KiCad non hanno rilevato violazioni né collegamenti mancanti. **Attendiamo la consegna dei circuiti per verificarne montaggio e funzionamento: il collaudo fisico non è ancora stato eseguito.**

Per ora manuali e presentazioni restano invariati. I file tecnici della PCB sono conservati nel repository privato e non vengono pubblicati qui.

### English

The dedicated **GUARDIAN POWER Rev I** power-board design is complete. It is intended to replace the prototype's perfboard and simplify wiring. It also includes a hardware provision for an optional BMP280 pressure sensor; the corresponding firmware feature has not yet been integrated.

KiCad design-rule checks reported no violations or unconnected pads. **We are awaiting delivery of the boards for assembly and functional testing; physical validation is still pending.** Manuals and presentations remain unchanged. PCB design files are retained privately and are not included in this public repository.

## Novità funzionale — menu Verifica e correzioni

È stata aggiunta l'area tecnica **ALTRO → MANUTENZIONE → ACCESSO TECNICO → VERIFICA E CORREZIONI**, protetta da PIN.

- Confronto delle letture originali di GUARDIAN con i valori di uno strumento di riferimento.
- Gestione dei profili di correzione per i parametri supportati, mantenendo distinti valori originali e corretti.
- Inserimento dei punti di confronto e del riferimento al rapporto di verifica.
- Operazioni dedicate alla CO2 raccolte nell'area tecnica protetta.
- Registro tecnico per consultare le operazioni e le modifiche effettuate.

Questa funzione consente di documentare verifiche e applicare correzioni: **non costituisce, da sola, una taratura certificata o una certificazione di GUARDIAN**. Il valore metrologico dipende dal metodo, dallo strumento di riferimento e dalla documentazione delle prove. Gli indici VOC/NOx non vanno trattati come concentrazioni di gas; GUARDIAN non misura le particelle ultrafini.

Le nuove schermate e le istruzioni sono incluse nei manuali aggiornati.

## 29 ottobre 2026 — Organizzazione documenti
- Manuali e presentazioni separati nelle cartelle Italiano ed English.
- Indice unico per PDF, PowerPoint e video.
- Collegamenti aggiornati; contenuto dei PDF e dei PowerPoint invariato.
- Nessuna nuova versione firmware pubblicata con questo riordino.

## 28 ottobre 2026 — Documentazione aggiornata
- Manuali in italiano e inglese aggiornati con le nuove schermate di verifica e correzioni e del registro tecnico.
- Uniformato lo stile delle pagine dei manuali e raddrizzato il documento Sensirion.
- Presentazioni in italiano e inglese: 40 pagine/slide ciascuna.
- Fotografie del display nella lingua originale, accompagnate da spiegazioni in inglese nei documenti EN.

[Apri l'indice dei documenti](docs/README.md)

---

## Functional update — Verification and corrections menu

A PIN-protected technical area has been added, accessible from **More → Maintenance → Technical access → Verification and corrections**.

- Compare original GUARDIAN readings with a reference instrument.
- Manage correction profiles for supported parameters, keeping original and corrected values distinct.
- Record comparison points and the verification report reference.
- Access dedicated CO2 operations within the protected technical area.
- Review operations and changes in the technical log.

This feature supports documented verification and corrections; **it does not, by itself, constitute certified calibration or product certification**. Metrological validity depends on the method, reference instrument and test documentation. VOC/NOx indices must not be treated as gas concentrations; GUARDIAN does not measure ultrafine particles.

The updated manuals include the new screens and instructions.

## 29 October 2026 — Document organisation
- Manuals and presentations organised into Italian and English folders.
- A single index links to PDFs, PowerPoint files and videos.
- Links updated; PDF and PowerPoint contents unchanged.
- This reorganisation does not publish a new firmware version.

## 28 October 2026 — Updated documentation
- Italian and English manuals updated with verification/correction and technical-log screens.
- Consistent manual page styling and straightened Sensirion document.
- Italian and English presentations: 40 pages/slides each.
- Display photographs retain their original language, with English explanations in EN documents.

[Open the document index](docs/README.md)
