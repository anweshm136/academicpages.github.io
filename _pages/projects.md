---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---
<!---
{% include base_path %}


{% for post in site.projects %}
  {% include archive-single.md %}
{% endfor %}
--->

1. **SincNet for Small Footprint Keyword Spotting** (Summer '20)  
    _Advisor: Prof.Oliver Bringmann, University of Tuebingen, Germany_  
    Implemented SincNet in the University's framework using PyTorch. Increased the efficiency for the [original SincNet model for KWS](https://www.researchgate.net/publication/337075024_Small-Footprint_Keyword_Spotting_on_Raw_Audio_Data_with_Sinc-Convolutions "original") by reducing the model size as well as computations without compromising on accuracy. Conducted an extensive benchmark test under several noise conditions, where the proposed model outperformed the state-of-art TC-RESNET 8 model. [[Report]](https://docs.google.com/presentation/d/18lp1ZnE3iOwVLqjaOHyqKQnYmv_7MXFICfgcu03G6KA/edit?usp=sharing "ppt")
    
2. **Eigen Faces vs Fisher Faces** (Autumn '19)  
    _Advisor: Prof.Suyash Awate, CS, IITB_  
    Implemented and compared two popular face recognition algorithms, fisher faces and eigen faces. Analyzed the differences in performances of the algorithms on the [Yale Dataset](https://www.kaggle.com/olgabelitskaya/yale-face-database "Dataset") which has sufficient variations in lighting and facial expressions, and provided a mathematical basis for this difference in performance as well. [[Report]](https://drive.google.com/file/d/1dxcA98J-Xu4lrbiPaNsTxnucZlaoyE_1/view?usp=sharing "Report")
    
3. **PCMO Transient Analysis** (Summer '19)  
    _Advisor: Prof.Udayan Ganguly, EE, IITB_  
    Designed a LTSpice model to verify the lumped model temperature behavior of a PCMO device. Developed a physical and corresponding quantitative MATLAB model to compare the effects of electrical field and temperature on the reset transient of the device. Calibrated the MATLAB model parameters to give accurate results for various devices.[[Report1]](http://iitbnf.iitb.ac.in/udayanresearch/index.php/2019/05/30/competition-between-electric-field-and-temperature-in-pcmo-reset-transient/ "Report 1"), [[Report2]](http://iitbnf.iitb.ac.in/udayanresearch/index.php/2019/07/01/calibration-of-parameters-for-comparison-between-electric-field-and-temperature-in-pcmo-reset-transient/,"Report 2") 
  
4. **Image Compression** (Spring '19)  
    _Advisor: Prof.Biplab Banerjee, CSRE, IITB_  
    Implemented k-means clustering algorithm to achieve image compression with significant decrease in size while still retrieving most of the important attributes. Designed a Convolutional Neural Network in Keras to implement a basic classification task, and compare the accuracies achieved using the compressed and original image datasets.[[Report]]("Report") ADD LINK TO REPORT!!!
 
 5. **Transient Thermal Feedback Model for PMO RRAM** (Spring '19)  
    _Advisor: Udayan Ganguly, EE, IITB_   
    Conducted an extensive literary survey to understand the conduction mechanism in PMO devices. Built a thermal feedback based model on MATLAB to see the role of self heating in PMO DC I-V characteristics and verified it with experimental results. Obtained the thermal transients to explain the distortion in DC I-V hysteresis on varying the ramp rates and the step response of the device.[[Report1]](https://drive.google.com/file/d/1FrZqOk3dWUZSJl9k64kBdtvFfhQjbrU5/view?usp=sharing "Report1"), [[Report2]](https://drive.google.com/file/d/11wAcZ9nemFdylRMQgk_WaoNDQq5I70QO/view?usp=sharing "Report2")
    
6. **IITB-Proc, multi-cycle RISC Processor Designing** (Spring '19)  
    _Advisor: Virendra Singh, EE, IITB_  
    Developed a 16-bit, 8-register processor which can solve complex problems. Implemented the design of Register File, Datapath, Finite State Machine and other components like ALU, and included operations like add, load, store and jump. Used VHDL for description of the hardware design of various components and integrating them along with the controller FSM using suitable select pins which were toggled depending on the current state.[[Report]](https://drive.google.com/file/d/1I0IaLywZjTE23czczVJkxm4jrdFtqNPz/view?usp=sharing "Report")
 
7. **Hand Gesture Controlled 3-D Hologram** (Summer '18)  
    _Institute Technical Summer Project, Electronics and Robotics Club, IITB_  
    Designed models and animations in Unity and basic operations like rotation, scaling and changing to other models were incorporated using standard model libraries. Constructed a self-designed IR sensor board to record the input in the form of hand gestures. Used Arduino MEGA to provide the interface between the Unity game and IR sensor board and the final output was presented in the form of a 3D hologram. [[Video]](https://youtu.be/IPDkaxrHhvE "Video")
