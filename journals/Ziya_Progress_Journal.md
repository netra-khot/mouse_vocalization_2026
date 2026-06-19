# Ziya's Progress Journal
 
## June 18, 2026
**Time:** 2:00pm–4:45pm
**Duration:** 2h 45m
 
- Set up Git/GitHub workflow (cloning, gitignore, branches, tried working w/ LFS for large files)
- Resolved dataset access by pulling real audio from BiWaveGAN GitLab repo via Git LFS
- Set up local config file system so each collaborator can use their own data path without pushing it to GitHub
- Began EDA: confirmed sample rate (250kHz) and call duration (~40ms) on a single file
- Computed dataset-wide call duration distribution
- Checked RMS energy across files to screen for bad detections
- Confirmed train/test split is 90/10 and well-stratified by strain
- Identified strain imbalance (DBA: 20,265 train files vs. C57: 8,064 train files)
- Decided to filter dataset to DBA only for training + testing