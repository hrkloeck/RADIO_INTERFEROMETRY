# RADIO INTERFEROMETRY

This is a first try to collect a record of literature and information nessesary to understand and work woith interferometric data.

- Some theory 
  
  This paper provides a good overview on CASA and the nessesary steps of calibration and imaging
  [Bean et al. 2022](https://arxiv.org/pdf/2210.02276)

  This paper provides a good overview of the gridding of visibilities
  [Offringa et al. 2019](https://arxiv.org/pdf/1908.11232)

  This is an entire course on interferometry by Oleg's group 
  [RATT-RU](https://github.com/ratt-ru/foi-course)

  A paper summary on imaging [Urvashi Rau](https://safe.nrao.edu/wiki/pub/Software/Algorithms/WebHome/SummaryImagingRadioInterferometry.pdf)

- Some practicallities
  
  - display visibilities
    - [shadeMS](https://github.com/ratt-ru/shadeMS/tree/master)

  - imaging
    - [wcsclean](https://wsclean.readthedocs.io/en/latest/)
    - [CASA TCLEAN task](https://casadocs.readthedocs.io/en/stable/api/casatasks.html#imaging)
           
  - source finding
    - [pybdfs](https://pybdsf.readthedocs.io/en/latest/)
    - [Aegean](https://github.com/PaulHancock/Aegean)
    - [Jonah's full suit](https://github.com/JonahDW/Image-processing)

  - calibration
    - generating a LSM
      - this is a very complex thing currently
      - [tigger-lsm](https://github.com/ratt-ru/tigger-lsm/tree/master)
      - [wsclean predict](https://wsclean.readthedocs.io/en/latest/prediction.html)
      - [crystalball](https://github.com/caracal-pipeline/crystalball?tab=readme-ov-file)
      - [LSM simulation CASA] (https://casadocs.readthedocs.io/en/stable/examples/community/simulation_script_demo.html)    
      - [ft CASA](https://casadocs.readthedocs.io/en/v6.2.0/api/tt/casatasks.imaging.ft.html)

    - display calibration tables
      - [ragavi](https://github.com/ratt-ru/ragavi)   
    - CASA task (1 GC, 2GC)
    - [quartical](https://quartical.readthedocs.io/en/latest/) (2 GC, 3GC)


- Some new stuff [PFB from LB](https://github.com/ratt-ru/pfb-imaging?tab=readme-ov-file)
