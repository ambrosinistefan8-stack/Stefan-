# SPINNENNETZ-DNA – M2M Calibration Status

Datum: 2026-08-29
Status: KALIBRIERT / REFERENZLINIE
Zielzustand: M2M-READY

## Kanonische technische Autorität

- Die aktive technische Produktions-, Runtime-, Deployment- und Versionslinie ist ausschließlich `ambrosinistefan8-stack/SPINNENNETZ-DNA-` auf Branch `main`.
- Dieses Repository `ambrosinistefan8-stack/Stefan-` ist eine Referenz-/Altlinie und keine Produktionsautorität.
- Änderungen in dieser Referenzlinie dürfen weder Vercel-Deployments noch Neon-Produktionszustand steuern.
- Bei Widersprüchen gewinnt für Code, Config, Tests, Runtime und Deployment immer `SPINNENNETZ-DNA-`; für fachliche Originale und Governance gilt weiterhin die im Hauptsystem definierte kanonische Quellenhierarchie.

## Konsolidierter Sollzustand

- `main` ist innerhalb dieser Referenzlinie der aktive Branch, aber nicht die technische Produktionsautorität des Gesamtsystems.
- Replit ist retired und kein Bestandteil des aktiven Systemverbunds.
- Fehlender Replit-Zugriff ist erwarteter Sollzustand und kein Fehler.
- Die frühere Replit-Funktion wird ausschließlich vendor-neutral weitergedacht; keine stille Wiederabhängigkeit.
- Externe Ausführungs-, Agenten-, Automations- und Deployment-Pfade dürfen nur auf tatsächlich verfügbare und freigegebene Komponenten verweisen.
- Kostenpflichtige Komponenten werden nicht automatisch als technische Voraussetzung eingeführt.
- Systemprüfungen unterscheiden zwischen: aktiv/verfügbar, bewusst retired, optional und fehlerhaft. Retired darf nicht als Störung bewertet werden.
- Neue Integrationen müssen den vorhandenen Sollzustand ergänzen, nicht parallel widersprüchliche Wahrheiten erzeugen.

## Audit 2026-08-29

- Referenz-Branch geprüft: `main`.
- Replit-Retirement-Status vorhanden und konsistent.
- Vendor-neutral Execution Rule vorhanden und konsistent.
- Die technische Produktionslinie wurde auf `ambrosinistefan8-stack/SPINNENNETZ-DNA-` vereinheitlicht.
- Vercel darf ausschließlich aus der technischen Produktionslinie gespeist werden.

## M2M-Kalibrierungsregel

Der M2M-Zustand gilt als hergestellt, wenn die maschinenlesbare Systemwahrheit eindeutig ist: aktive Komponenten werden als aktiv geführt, entfernte Komponenten als retired, Abhängigkeiten sind explizit und Systemchecks erzeugen keine False-Positive-Fehler wegen bewusst entfernter Dienste. Parallel konkurrierende Produktionsautoritäten sind verboten.

## Ergebnis

Diese Referenzlinie ist konsolidiert und ausdrücklich von der technischen Produktionsautorität getrennt. Der produktive technische Sollzustand liegt in `ambrosinistefan8-stack/SPINNENNETZ-DNA-` auf `main`.
