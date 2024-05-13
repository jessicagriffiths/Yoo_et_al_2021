Cecal contents were isolated and resuspended in 400 μL of phosphate buffered solution and centrifuged at 20,000 xg to spin down cells and lysate. Protein was isolated from the resulting supernatant using Wessel-Flügge’s methanol/chloroform extraction method, and then precipitated. Precipitated protein samples were denatured, digested, and desalted. Samples were analyzed on a Q Exactive HF Orbitrap mass spectrometer coupled to an EASY nLC 1200 liquid chromatographic system. Thermo.raw files were converted to.ms1 and.ms2 files using RawConverter 1.1.0.18 operating in data dependent mode and selecting for monoisotopic m/z. Tandem mass spectra (.ms2 files) were identified by a database search method using the Integrated Proteomics Pipeline 6.5.4. Briefly, databases containing forward and reverse (decoy) peptide sequences were generated from in silico trypsin digestion of either the mouse proteome or protein sequences derived from large comprehensive public repositories. Tandem mass spectra were matched to peptide sequences using the ProLuCID/SEQUEST (1.4) software package. The validity of spectrum-peptide matches was assessed using the SEQUEST-defined parameters XCorr (cross-correlation score) and DeltaCN (normalized difference in cross-correlation scores) in the DTASelect2 (2.1.4) software package. Detected proteins were grouped by sequence similarity into "clusters" using CD-HIT 4.8.1. Ion intensity data were analyzed using the Differential Enrichment analysis of Proteomics data DEP package.