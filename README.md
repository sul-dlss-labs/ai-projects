The site is a window into Stanford Libraries' work to build capacity in AI while experimenting with applications of AI on library materials and in library processes. We approach building capacity as a cross-library effort. While an essential part of the effort is giving developers an opportunity to get their hands on new tools and understand new ways of working, there was a parallel effort to familiarize people from all parts of the library with the potential of AI so that they could identify possible useful applications of the technology, help shape the projects, assess outcomes (at every step) and bring domain expertise to the challenges that arise. 

# Projects

## AI for ETDS
This project was our first dive into how machine learning and natural language processing might help us automate the assignment of subject headings from the [FAST (Faceted Application of Subject Terminology)](https://www.oclc.org/research/areas/data-science/fast.html) vocabulary to ETDs (electronic theses and dissertations). 

### Phase 1 (October 2020)
**Objective**: To become familiar with the data, experiment with methods, and determine whether we can successfully automate or semi-automate FAST subject headings for ETDs.  

**Outcomes:**
- [druid_2_text](https://github.com/sul-dlss-labs/druid_2_text) (to retrieve pdf from our repository and convert to txt for pre-processing)
- [Document Structure Classifier](https://github.com/sul-dlss-labs/etd_structure_classifier) (to extract bibliographies)
- [Biology ETDs FAST tagging app](https://biology-fast-etds.herokuapp.com/)
- [Abstract Similarity/clustering app](https://etd-abstract-similarity.herokuapp.com/)

## SPOC (Species Occurrences)
[Source code](https://github.com/sul-dlss-labs/spoc)

Observations of marine plants and animals are “hidden” in the text of undergraduate student research papers (Paper > TIFF > OCR > plain text). Researchers need this information but can’t find it, access it, or use it. The goal of this project is to extract species occurrences (genus-species, place, time) from student papers held in libraries along the western coast of the U.S.


