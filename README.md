# Semi-supervised-radio-classification

Semi-supervised learning for AGN/SFG classification in the MIGHTEE-COSMOS radio survey.

## Overview

This repository contains code and data for the paper **"Exploiting minimal labels for radio source classification: semi-supervised learning in the MIGHTEE-COSMOS field"** by V. Asadi (2026). 

We present a clustering-based semi-supervised learning framework that classifies radio sources as AGN or star-forming galaxies (SFGs) using only 50 labeled sources—just 1.6% of the training pool.

**Key results:**
- SSL with 50 labels → Weighted F1 = 0.92 (AGN: 0.89, SFG: 0.94)
- Active learning with 81 additional labels → F1 = 0.95 (beats supervised kNN with 642 labels)
