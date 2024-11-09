Python pipeline to use SDO/HMI continuum intensity images as a reference to correct the pointing information (WCS FITS header keywords) of SO/PHI-HRT data.

This only works while SO/PHI-HRT is observing the Earth-side of the Sun.

Pipeline requires using the HRTandHMIfiles loader to get the SO/PHI-HRT and SDO/HMI file pairs (same time - including light travel time corrections)

<iframe frameborder="0" scrolling="no" style="width:100%; height:3523px;" allow="clipboard-write" src="https://emgithub.com/iframe.html?target=https%3A%2F%2Fgithub.com%2FJonasSinjan%2Far_long_term_oct_2023%2Fblob%2Fmain%2Fsrc%2Fhrt_wcs_corr_pipeline.py&style=github-dark-dimmed&type=code&showBorder=on&showLineNumbers=on&showFileMeta=on&showFullPath=on&showCopy=on"></iframe>