# effect_of_model_res_Argentine_Basin_JGRO
Code for "The effect of resolution on vertical heat and carbon transports in a regional ocean circulation model of the Argentine Basin"
https://doi.org/10.5281/zenodo.4488699

Instructions for reproducing regional model output: 

1) Create initial and boundary condition files from BSOSE using MATLAB code in folder /create_ICs_and_BCs/

2) Run three day model initializations at each resolution 
(setups contained in /MITgcm + NBLINGv2/SO3_20190510/, /MITgcm + NBLINGv2/SO6_20190510/, and /MITgcm + NBLINGv2/SO12_20190510/)

3) Create new initial condition files with the MATLAB script /create_ICs_and_BCs/make_second_round_ICs.m

4) Run 13 month models at each resolution 
(setups contained in /MITgcm + NBLINGv2/SO3_20190513/, /MITgcm + NBLINGv2/SO6_20190513/, and /MITgcm + NBLINGv2/SO12_20190513/)
