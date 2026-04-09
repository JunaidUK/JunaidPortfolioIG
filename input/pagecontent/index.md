# WHOAMI

Implementation Guides are one of the key ways to document how resources should be used in healthcare interoperability, and it struck me as the most apt medium for presenting the skillsets, tools, and accomplishments that I have accrued in the last decade in healthcare.

---

# Core areas of practice:

I help healthcare organizations design, build, and deploy FHIR-based solutions that meet regulatory requirements and real-world clinical workflows. My work spans the full lifecycle — from strategic planning through technical implementation and go-live support.
- FHIR R4 Implementation Guide (IG) development using FSH/SUSHI
- Health data interoperability and API design
- SMART on FHIR application integration
- Clinical data mapping and terminology management (SNOMED CT, LOINC, ICD)
- Advisory services for payers, providers, and health IT vendors

---

# Explore This Site

| Page | Description |
|------|-------------|
| [About](about.html) | Professional background, skills, and services |
| [MBA](mba.html) | Business education and how it shapes my approach |
| [Personal Life](personal.html) | Beyond the work — interests and values |
| [Resume](resume.html) | Downloadable resume and credentials summary |
| [Artifacts](artifacts.html) | FHIR profiles and example resources from this IG |

# Get In Touch

I am available for consulting engagements, advisory roles, and collaborative projects

- **LinkedIn:** [linkedin.com/in/junaidsidd](https://www.linkedin.com/in/junaidsidd/)
- **GitHub:** [github.com/JunaidUK](https://github.com/JunaidUK)
- **Resume:** [Download PDF](resume.html)

## How this site was built
- Site Generation: This IG was generated using the `fsh-sushi` NPM package for [FHIR Shorthand](https://github.com/FHIR/sushi), and the HTML artifacts were built using the [HL7 FHIR IG Publisher](https://github.com/HL7/fhir-ig-publisher)
- CI/CD pipeline: Github Actions Runners build the artifacts in production, and site is hosted on Github Pages
- Claude Code CLI was used to debug pipeline actions, build issues, and add features to the site. [The Claude FHIR Skill from Topology Health](https://github.com/joshcds/ClaudeFHIRSkill) was invoked to generate the FSH profiles in this IG and example resources in this IG. 