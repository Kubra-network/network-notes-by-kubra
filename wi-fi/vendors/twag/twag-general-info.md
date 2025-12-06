# TWAG : WIFI GATEWAY 

Small Deployment Model (without Content Services) 


This cluster style is an adaptation of the Smallest Deployment Model (with Content Services) for cases where content services in the user-plane is not required.


* The CSM in the former model is replaced with the CPM, as described below. vMCM – Functions as described in vMCM. 


* vCPM – Logically combines all of the vCCM, vDCM capabilities, creating a single VM type that provides all control-plane services. 


* The vCPM is similar to the vCSM, except it does not provide the content services Value Added Services in the user-plane. Requires a minimum of one vCPM and two for redundancy.


* vSSM – Logically combines the vIOM and vWSM capabilities. Requires a minimum of one vSSM and two for redundancy.
