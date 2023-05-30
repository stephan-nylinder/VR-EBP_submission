##Introduction

The following is a description of the steps (all or some) necessary for submitting data in the VR-EBP project. It is simiar to, but different from, the ERGA initiative. THe two projects are run in parallel at NBIS with data handling and analysis performed by the same staff. For the ERGA project there is an already more developed pipeline with steps not (yet) present for VR-EBP.

For ERGA the data is intended to be submitted by the sequencing platform, with a metadata manifest filled in by the PI. The manifest willthen be validated in COPO, generating an ENA manifest to be used in the raw data submission. Steps for registering studies and providing both general and specific descriptions have been, or is under, development.

In comparison, the VR-EBP project have very few similar steps already defined. As a consequence, NBIS, as data handlers and responsible for supporting data submissions can assist in developing a sustainable pipeline for data submissions. Due to the large and overlapping similarities between ERGA and VR-EBP for both sequencing and data handling/analysis, the DM Team at NBIS will model the VR-EBP data submission pipeline on the already developed pipeline for ERGA.

1. Make sure the data to be submitted is verified and compiled by the bioinformatician acting as contact person. The bioinformatician together with the Team Manager decides on what data is ready for submission before contact is made with the DM Team.

2. The DM representative is invited to the UPPMAX project with necessary access.

3. Get final clearance from the Team manager (Henrik Lantz) that data is ready to be submitted. This will usually be a primary submission of raw reads, with a later secondary submisison of assembly and annotation.

4. Each species in the VR-EBP must be submitted with a Tree of Life ID (ToLID)

4.1 Go to the ToL webpage (https://id.tol.sanger.ac.uk/) and login using ELIXIR credentials

4.2 Select 'Create' and fill in the NCBI Taxonomy ID for the species (if the species lack an NCBI ID, register one: https://ena-docs.readthedocs.io/en/latest/faq/taxonomy_requests.html)

4.3 The 'Specimen ID' is an arbitrary identification tag (if any) used in the sequencing project. Its purpose is to make it possible to identify the individual (set of) specimen in the project used for the sequencing in case the species collection includes more than one individual.

4.4 Scientific name - Fill in the species name corresponding to the NCBI Taxonomy ID (Genus species).

4.5 Click 'Request' to submit the application. You will receive an email with the ToLID when the application has been considered. All ToLID's are manually curated.


5. For each species, a new study is registered in ENA. Login using the DM Team broker account credentials.

5.1 Release date - By default in the VR-EBP the study is to be released without embargo time

5.2 Study name - Same as ToLID

5.3 Study title - To be written as: "'species_name', genomic and transcriptomic data"

5.4 Study abstract - NBIS has together with the PI's in the VR-EBP project developed a template text, based on the corresponding ERGA template abstract.
[Fill in here]

5.5 Study attributes - Click + and type 'keyword' and 'VR-EBP'.

