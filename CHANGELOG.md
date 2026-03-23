# Changelog 

 

All notable changes are documented here. 

Format: Keep a Changelog (https://keepachangelog.com) 

 

## [2.0.0] - 2026-03-23 

 

### Added 

- Text_Analysis_Template_2_0.ipynb: full v2.0 pipeline 

- Modular function-based architecture (run_text_analysis orchestrator) 

- Timestamped output directory structure (5 subdirectories) 

- NetworkX co-occurrence graph with GraphML and edge list exports 

- BERTopic-compatible topic modeling and JSON topic export 

- Semantic embedding and UMAP/HDBSCAN clustering 

- Entity-level sentiment extraction and CSV export 

- Section-level aggregate analysis (moral, threat, power scores) 

- Parquet dataset export for performance 

- Automated DOCX report via python-docx 

- Document fingerprint JSON replacing flat metadata dict 

 

### Removed 

- Phase-based linear execution model 

- PHASE 0 configuration cell pattern 

- Sentence-level falsifiability and evidence typology flags 

- Lexical frequency / bigram / trigram appended to FINAL_DATASET 

- Dataset SHA-256 hash and LOCK_TIMESTAMP pattern 

 

### Kept 

- Text_Analysis_Template_1_0.ipynb: sentence-level claim audit 

  pipeline remains in repo for traceability-focused workflows. 

 

## [1.0.0] - Initial release 

- 20-phase sentence-level PDF audit pipeline 

- Claim extraction, classification, falsifiability, evidence typing 

- Lexical frequency (Phase 15) and phrase extraction (Phase 16) 

- SHA-256 dataset hash and export metadata 
