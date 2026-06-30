# Netra's Progress Journal #
## ENTRY 3 &rarr; 06/29/2026 (3 hours)
### 3:30pm - 6:30pm
- Tentatively choosing state-space models
    - Explored neural SSMs and linear SSMs for an interpretable baseline
- Changed file name to neural_ssm.testing.ipynb
- Added configs

## ENTRY 2 &rarr; 06/28/2026 (1 hour)
### 4:45 - 5:45pm
- Worked through different model 1 architectures and families
    - Narrowed down to hierarchical conditional model and latent dynamical system
    - Hierarchical systems model the brainstem well and latent systems treat muscle data as an evolving state
        - Learning towards latent dynamical system
- Added latent_dynamical_testing.ipynb
- Added initial imports and packages needed in general

## ENTRY 1 &rarr; 06/18/2026 (3.5 hours)
### 2:00 - 4:45pm
- Set up VSCode and GitHub repository (added journal folders, data folders, set up .gitignore, etc.)
- Looked through data &rarr; imbalance of C57 and DBA strain (DBA in favor)
    - Decided to remove all C57 files to avoid bias
- Performed EDA on data
    - inspected raw data
    - checked dataset stucture
    - visualized waveform with time domain
### 10:45 - 11:30pm
- More EDA on data
    - Duration distribution
    - Converted waveform to spectrogram
