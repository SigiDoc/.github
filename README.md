[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/) [![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

# SigiDoc

SigiDoc 1.0 - The XML-based and EpiDoc-compliant encoding standard for the scholarly edition of Byzantine lead seals and coin-like objects. Newest developments in the framework of the DFG-ANR project DigiByzSeal "Unlocking the Hidden Value of Seals: New Methodologies for Historical Research in Byzantine Studies" ANR: https://anr.fr/Project-ANR-21-FRAL-0008; DFG: https://gepris.dfg.de/gepris/projekt/469385434.

# DigiByzSeal Metaportal

The goal of the DigiByzSeal project is creating a sigillographic hub, an overarching search portal for all collections encoded in SigiDoc-XML, whether they have a web presence or not. You can see the structure of the metaportal here:

![Portal-structure](https://github.com/SigiDoc/.github/assets/29565842/54c112d9-0024-4850-bb04-307d959c3d80)

# Collections currently encoded in SigiDoc

* Collection Robert Feind, Cologne: [Collection Repo](https://github.com/byzantinistik-koeln/feind-collection), [EFES instance](https://github.com/byzantinistik-koeln/EFES-SigiDoc-feind)
* Collection Seyrig, Bibliothèque nationale de France, Paris: [Collection Repo](https://github.com/sceaux-byzantins-paris/seyrig-collection), [EFES instance](https://github.com/sceaux-byzantins-paris/EFES-SigiDoc-seyrig)
* Collection of the Institut Français d'Études Byzantines, Paris: [Collection Repo](https://github.com/sceaux-byzantins-paris/ifeb-collection), [EFES instance](https://github.com/sceaux-byzantins-paris/EFES-SigiDoc-ifeb)
* ...and many more are joining!

# Onboarding guidelines

If you would like to encode your seals with SigiDoc and to make them searchable via the DigiByzSeal search portal, featuring more than 4,000 seals, get in touch with the developers or the PIs of [DigiByzSeal](https://ifa.phil-fak.uni-koeln.de/forschung/byzantinistik-und-neugriechische-philologie-forschung/drittmittel-projekte/digibyzseal). We are eager to help! 

![Onboarding-guidelines](https://github.com/SigiDoc/.github/assets/29565842/7f699561-42e7-4330-8904-e25cf54fc2b5)

# Encoding guidelines

The latest version of the guidelines (v1.0) is at https://github.com/SigiDoc/Guidelines.

# Development

When there are authority lists in your project (stored in /webapps/ROOT/content/xml/authority) you can harvest RDF from them and that will give you the values in your facets and indices pages in EFES.
