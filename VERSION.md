# D2CE4I Website — v1.1 (Initial Launch)

**Stand festgehalten:** 15. November 2026  
**Status:** veröffentlichte erste Landingpage, nach Nutzerprüfung  
**Offizielle Adresse:** https://d2ce4i.com  
**Repository:** https://github.com/rwmt95ny9r-gif/d2ce4i-website

## Umfang der Version

- Responsive, englischsprachige, statische Landingpage
- Wortmarke D2CE4I mit rot hervorgehobenen Ziffern 2 und 4
- Leitgedanke: **From Inspiration to Impact.**
- Unterzeile: **Human potential. Shared possibilities.**
- Vier Dimensionen: **Discover · Connect · Create · Experience**
- Erklärender Abschnitt mit vier Kacheln und Coming-soon-Hinweis
- Kontaktbereich **Let's connect.** mit dem Button **Get in touch**
- Kontaktbutton öffnet das Mailprogramm mit der korrigierten Adresse `md@minds4motion.com` (Betreff: `D2CE4I inquiry`)
- E-Mail-Adresse wird clientseitig erst bei Klick aus Bestandteilen zusammengesetzt, als Basisschutz vor einfachen HTML-Scrapern (kein garantierter Spam-Schutz)
- Kein Anmeldeformular, kein Tracking, kein Backend, keine Zahlungen

## Bereitstellung und Domain

- Öffentliche Website-Quelldatei: `index.html`
- Bereitstellung über GitHub Pages mit `Source: GitHub Actions`
- Workflow `.github/workflows/pages.yml` ist **manuell** (`workflow_dispatch`): Merge allein veröffentlicht keine neue Version
- Nur die vorbereitete `index.html` wird als Pages-Artefakt publiziert
- Eigene Domain `d2ce4i.com` bei GitHub Pages hinterlegt
- DNS-Check laut GitHub-Pages-Screenshot vom 15. November 2026: **successful**
- **Enforce HTTPS** laut Screenshot vom 15. November 2026: aktiviert
- DNS-Verwaltung der Domain über IONOS; `www` als CNAME für GitHub Pages konfiguriert
- Ein separater technischer Live-/Browsercheck beider Hostnamen ist in diesem Versionsprotokoll nicht dokumentiert

## Grenzen und nächste Entwicklungsschritte

- Dies ist eine **Concept Preview**, noch keine funktionsfähige Matching-/Community-Plattform.
- Die E-Mail-Verschleierung hält fortgeschrittene Bots nicht zuverlässig auf.
- Produktfunktionen, Datenschutz-/Rechtstexte, Markenklärung, eine spätere Kontaktlösung mit stärkerem Spam-Schutz und automatisierte Deployments bleiben gesonderte Themen.
- **Schutz der internen Arbeit:** Das private M60-OS-Repository und seine Strategieunterlagen bleiben getrennt von diesem öffentlichen Website-Repository.

## Versionshistorie

- **v1.0:** Initiale visuelle Landingpage, GitHub-Pages-Deployment
- **v1.1:** Kontaktbereich ergänzt, Zieladresse auf `md@minds4motion.com` korrigiert, Custom Domain und HTTPS erfolgreich eingerichtet

**Hinweis:** Dieses Dokument fixiert den besprochenen Produkt-/Website-Stand als Baseline. Es verändert weder das sichtbare Design noch den Deployment-Workflow und erstellt keinen Git-Tag.
