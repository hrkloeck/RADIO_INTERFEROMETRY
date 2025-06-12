# RADIO INTERFEROMETRY

This is a first try to collect a record of literature and information nessesary to understand and work woith interferometric data.

- Some theory 
  
  This paper provides a good overview on CASA and the nessesary steps of calibration and imaging
  [Bean et al. 2022](https://arxiv.org/pdf/2210.02276)

  This paper provides a good overview of the gridding of visibilities
  [Offringa et al. 2019](https://arxiv.org/pdf/1908.11232)

  This is an entire course on interferometry by Oleg's group 
  [RATT-RU](https://github.com/ratt-ru/foi-course)

- Some practicallities
  
  - display visibilities
    - [shadeMS](https://github.com/ratt-ru/shadeMS/tree/master)

  - imaging
    - wcsclean
    - casa task
           
  - source finding
    - pybdfs
    - moresane

  - calibration
    - generating a LSM
      - this is a very complex thing currently
      - [tigger-lsm](https://github.com/ratt-ru/tigger-lsm/tree/master)
      - [wsclean predict](https://wsclean.readthedocs.io/en/latest/prediction.html)
      - [crystalball](https://github.com/caracal-pipeline/crystalball?tab=readme-ov-file)
      - [LSM simulation CASA] (https://casadocs.readthedocs.io/en/stable/examples/community/simulation_script_demo.html)    
    - CASA task (1 GC, 2GC)
    - [quartical](https://quartical.readthedocs.io/en/latest/) (2 GC, 3GC)
   
- Some new stuff [PFB from LB](https://github.com/ratt-ru/pfb-imaging?tab=readme-ov-file)
