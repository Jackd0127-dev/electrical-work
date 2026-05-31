# NI Electrical Revision Reference

Static single-page revision/reference app for `electrical.scriptai.space`.

## Purpose

This project is a UK/Northern Ireland electrical revision aid for competent-person learning and recap. It is intended for apprentices, improvers, qualified electrical workers and supervised learners who need compact notes on principles, terminology, testing purposes, documentation and Northern Ireland compliance context.

It is not a contractor website, lead-generation page, quote workflow, public DIY wiring guide or replacement for BS 7671, employer procedures, manufacturer instructions, supervision or formal training.

## Files

- `index.html` - the complete static app, including content, styles and vanilla JavaScript.
- `sitemap.xml` - root URL only for the hash-based single-page app.
- `robots.txt` - crawler policy pointing at the sitemap.

## Run Locally

```sh
python3 -m http.server 8000
```

Then open `http://127.0.0.1:8000/` from this directory.

## Review Policy

Technical and legal content must be reviewed against the current edition of BS 7671, official Northern Ireland sources, employer procedures and competent electrical judgement before it is relied upon or published as reviewed.

Official source anchors:

- IET BS 7671 current edition/amendment: https://electrical.theiet.org/bs-7671-18th-edition-wiring-regulations/ensure-you-are-up-to-date-with-bs-7671/
- Electrical Safety First - Building Regulations in Northern Ireland: https://www.electricalsafetyfirst.org.uk/find-an-electrician/building-regulations/northern-ireland/
- Department of Finance NI - Technical Booklet P: https://www.finance-ni.gov.uk/publications/technical-booklet-p
- Department for Communities NI - Electrical Safety Standards for Private Tenancies Regulations: https://www.communities-ni.gov.uk/articles/electrical-safety-standards-private-tenancies-regulations-northern-ireland-2024
- Department for Communities NI - Smoke, Heat and Carbon Monoxide Alarms guidance: https://www.communities-ni.gov.uk/articles/smoke-heat-and-carbon-monoxide-alarms-private-tenancies-regulations-northern-ireland-2024-guidance-notes
- HSENI electrical safety: https://www.hseni.gov.uk/articles/electrical-safety
- Consumer Council NI - electric vehicles: https://www.consumercouncil.org.uk/consumers/help-consumers/travel-and-transport/electric-vehicles
- NIE Networks low carbon technologies: https://www.nienetworks.co.uk/connections/low-carbon-technologies

## Manual Review Checklist

A qualified/competent reviewer should check:

- BS 7671 edition/amendment wording
- safe isolation wording
- inspection and testing wording
- EICR coding notes
- consumer unit and protective device notes
- SPD and AFDD notes
- bathroom and special-location notes
- EV charging, open-PEN and PME notes
- outbuilding earthing and bonding notes
- NI private tenancy electrical safety dates and duties
- NI smoke, heat and carbon monoxide alarm dates and duties
- Building Control and NI compliance wording
- all future diagrams or concept visuals

## Content Boundaries

Do not add contractor lead-generation content, fake business details, contact/quote flows, testimonials, pricing, service-area claims, emergency callout copy, insurance claims or membership claims.

Do not add terminal-level wiring instructions, consumer-unit internal wiring, meter-tail diagrams, socket/switch terminal diagrams, shower/cooker wiring diagrams, exact cable sizing recipes, detailed test-lead connection diagrams, buried cable installation instructions, or bathroom zone diagrams unless they have been manually checked and clearly labelled as conceptual.
