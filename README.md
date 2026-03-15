# 🔋 EV Calculator Pro Max

A comprehensive, responsive, and bilingual (EN/IT) web application for calculating Electric Vehicle (EV) charging times, costs, and added range. It runs entirely in the browser with zero dependencies.

**🌐 Live Demo:** [https://philsaino.github.io/EV-Calc/](https://philsaino.github.io/EV-Calc/)

Created with ⚡️ by [@philsaino](https://github.com/philsaino).

---

## ✨ Features

* **Smart Charging Modes:** Go beyond simple 0-100% calculations. Choose between targeting a specific State of Charge (%), setting a maximum charging time (Hours), or defining a maximum budget (€). The minute-by-minute simulation adjusts dynamically.
* **Smart Bottleneck Calculation:** Automatically determines the real charging power by comparing your AC grid limit (Amps/Phases) with the car's On-Board Charger (OBC).
* **Battery Chemistry Aware:** Supports both traditional (NMC/NCA) and LFP batteries, correctly adjusting the charging curve to account for the slowdown over 90% SoC (or lack thereof).
* **Minute-by-Minute Cost Tracking:** Accurately splits charging costs across different time-of-use tariffs (F1, F2, F3) based on the specific hour and day of the week.
* **Visual Cost Breakdown:** A dynamic, color-coded bar visually displays how your charging costs are distributed across your different time-of-use tariffs.
* **Calendar Export (.ics):** With a single click, generate and download a native calendar event to remind you exactly when your car will finish charging.
* **Range Estimation:** Calculates how many kilometers of range you are adding based on your car's average consumption and battery State of Health (SoH).
* **Built-in Database:** Quick selection menu pre-loaded with popular EVs (Tesla Model 3/Y, VW ID.3, MG4, Fiat 500e, etc.) to auto-fill specs.
* **Smart UI & UX:** Features a dark/light mode toggle, automatic saving of your preferences to local storage, fluid intrinsically responsive Grid layout, and a handy button to copy a charging report directly to your clipboard.
* **PWA & Mobile Native Feel:** Can be added to your iOS/Android Home Screen as a standalone web app with a custom generated App Icon, running perfectly in full-screen mode.
* **Accessible & Robust:** Full semantic labeling for screen readers and built-in safe input clamping (e.g., prevents entering invalid SoC values) with elegant in-UI error handling.

## 🕒 Time-of-Use Tariffs (Standard EU/IT)
The app calculates costs minute-by-minute based on these standard time brackets:
* **F1 (Peak):** Mon-Fri 08:00 - 19:00
* **F2 (Mid-level):** Mon-Fri 07:00-08:00 & 19:00-23:00, Sat 07:00 - 23:00
* **F3 (Off-peak):** Mon-Sat 23:00 - 07:00, Sun all day.

## 🚀 How to Use

1. **[Open the Live App](https://philsaino.github.io/EV-Calc/)** directly in any modern web browser.
2. *Alternatively:* Clone the repository or simply download the `index.html` file and open it locally.
3. Select your car, input your grid limits, set your tariffs, and click **Calculate**.
*Tip: On iOS Safari, tap "Share" and "Add to Home Screen" for a full-screen, native app experience!*

---
---

## 🇮🇹 Panoramica (Italiano)

Una web app completa, responsiva e bilingue (IT/EN) per calcolare i tempi di ricarica, i costi e l'autonomia recuperata per i veicoli elettrici (EV). Funziona interamente nel browser senza alcuna dipendenza.

**🌐 Usa l'App Online:** [https://philsaino.github.io/EV-Calc/](https://philsaino.github.io/EV-Calc/)

Creato con ⚡️ da [@philsaino](https://github.com/philsaino).

---

## ✨ Funzionalità

* **Modalità Smart Charging:** Vai oltre il semplice calcolo 0-100%. Scegli se impostare un Target di ricarica (%), un Tempo Massimo di ricarica (Ore) o un Budget Massimo (€). La simulazione si adatterà automaticamente calcolando i risultati al minuto.
* **Calcolo Intelligente dei Limiti:** Determina automaticamente la potenza di ricarica reale confrontando il limite della rete elettrica (Ampere/Fasi) con il caricatore di bordo (OBC) dell'auto.
* **Gestione Chimica Batteria:** Supporta sia batterie tradizionali (NMC/NCA) che LFP, adattando la curva di ricarica per tenere conto del rallentamento oltre il 90% di SoC (se presente).
* **Tracciamento Costi al Minuto:** Suddivide accuratamente i costi di ricarica tra le diverse fasce orarie (F1, F2, F3) in base all'ora specifica e al giorno della settimana.
* **Grafico Costi Visivo:** Una barra progressiva dinamica e colorata mostra a colpo d'occhio come si distribuisce la spesa tra le varie fasce orarie della bolletta.
* **Esportazione Calendario (.ics):** Con un solo clic, genera e scarica un evento di calendario nativo per ricordarti il momento esatto in cui scollegare l'auto.
* **Stima Autonomia:** Calcola i chilometri di autonomia aggiunti in base al consumo medio dell'auto e allo stato di salute della batteria (SoH).
* **Database Integrato:** Menu rapido precaricato con i veicoli più diffusi per compilare automaticamente le specifiche tecniche.
* **UI & UX Avanzate:** Tema scuro/chiaro, salvataggio automatico delle preferenze, griglia CSS fluida e un comodo pulsante per copiare il report di ricarica negli appunti.
* **Supporto PWA & iOS App:** Può essere aggiunta alla Schermata Home di iOS/Android comportandosi come un'app nativa a schermo intero con tanto di icona generata automaticamente.
* **Accessibile e Sicura:** Etichette semantiche complete e gestione automatica degli input (impedisce l'inserimento di SoC impossibili) con avvisi di errore eleganti integrati nell'interfaccia.

## 🕒 Fasce Orarie (Standard ARERA)
L'app calcola i costi minuto per minuto basandosi sulle seguenti fasce orarie standard:
* **F1 (Ore di punta):** Lun-Ven 08:00 - 19:00
* **F2 (Ore intermedie):** Lun-Ven 07:00-08:00 e 19:00-23:00, Sab 07:00 - 23:00
* **F3 (Ore fuori punta):** Lun-Sab 23:00 - 07:00, Domenica tutto il giorno.

## 🚀 Come si usa

1. **[Apri l'App Online](https://philsaino.github.io/EV-Calc/)** da qualsiasi browser web moderno.
2. *In alternativa:* Clona la repository o scarica semplicemente il file HTML e aprilo in locale.
3. Seleziona la tua auto, inserisci i parametri della tua presa, imposta le tariffe e clicca su **Calcola Ricarica**.
*Tip: Su Safari per iOS, premi "Condividi" e "Aggiungi alla schermata Home" per usarla come una vera app nativa!*

---

### 📝 License
This project is open-source and available under the MIT License. Feel free to fork, modify, and contribute!
