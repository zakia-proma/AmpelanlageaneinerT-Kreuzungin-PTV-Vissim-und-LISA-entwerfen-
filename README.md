# AmpelanlageaneinerT-Kreuzungin-PTV-Vissim-und-LISA-entwerfen-

Design of Traffic Lights at Various Intersections in Chemnitz and Their Subsequent Co-ordination
________________________________________
________________________________________
Table of Contents
1.	Introduction
2.	Model
3.	Conflict Matrix
4.	Intergreen Times
5.	Stages
6.	STP
7.	Coordination Updates STP
8.	Conclusion



# 1. Introduction:
The following example is an attempt to design a signal controller at two 4 way intersections in Chemnitz situated approximately 470m apart and further co-ordination between these intersections. The road network was modelled in PTV Vissim. The use of software LISA+ was used for the calculation of conflicts, intergreen times, stage groups and signal timing plans

2. Model
Intersection 1:
  <img width="945" height="913" alt="image" src="https://github.com/user-attachments/assets/fd02dd3c-7ed0-44da-a208-48021b1297f7" />
<img width="945" height="907" alt="image" src="https://github.com/user-attachments/assets/13fa4482-bab8-4c41-8210-5d2e9f91fe15" />

 
# Intersection 2:
   <img width="945" height="952" alt="image" src="https://github.com/user-attachments/assets/2ecc1c72-72dd-4bda-adda-9c7c7c6de1a4" />
<img width="945" height="945" alt="image" src="https://github.com/user-attachments/assets/344f5256-9723-4e3a-94a7-37b74f38a3af" />

# 3. Conflict Matrix
Intersection 1:
 <img width="945" height="881" alt="image" src="https://github.com/user-attachments/assets/343faddd-f586-4180-8468-372ffd38e059" />

 Intersection 2:
 <img width="788" height="709" alt="image" src="https://github.com/user-attachments/assets/667032d5-eae4-4cee-a97b-f4966b152164" />

# 4. Intergreen Calculation
Intersection 1:
 <img width="945" height="872" alt="image" src="https://github.com/user-attachments/assets/8c522d21-fa4e-4fd1-a14e-98198c9d68c8" />

Intersection 2:
 <img width="878" height="786" alt="image" src="https://github.com/user-attachments/assets/80f9ce44-9bca-40a7-b8ea-9526c39bedcf" />

#5. Stages
Intersection 1:
 <img width="945" height="830" alt="image" src="https://github.com/user-attachments/assets/0f74293a-29dd-4b94-9082-6efd5743a60f" />

Intersection 2:
 <img width="945" height="831" alt="image" src="https://github.com/user-attachments/assets/6716ed20-83c3-41d0-8687-74125bf280c0" />

# 6. Signal Time Program:
Intersection 1:
 <img width="877" height="814" alt="image" src="https://github.com/user-attachments/assets/bfd4125e-84ac-4e68-8766-9a6bc3670c0e" />

Intersection 2:
 <img width="945" height="588" alt="image" src="https://github.com/user-attachments/assets/7ca66328-d00c-46ee-a288-ae20cefab886" />

# 7. Attemting Co-ordination:
 
<img width="945" height="1305" alt="image" src="https://github.com/user-attachments/assets/66d8fe03-50ba-4d65-8bf4-048f30ac0b61" />

<img width="888" height="1019" alt="image" src="https://github.com/user-attachments/assets/38f50c47-13ee-4462-bd1b-fd4f76fb63c6" />

 

The STPs are subsequently updated to reflect the co-ordination is achieved.
The network and the signal controllers are exported to vissim and the simulations are run to check the performance of the signal controller. 

# 8. Conclusion:
 The two intersections are modelled in Vissim and the vehicle inputs and routes are described. The calculations of conflict matrix, intergreen matrix, stages, Signal Time Program are calculated in LISA+. The co-ordination between these intersections is also attempted to achieve a green wave for the vehicles travelling between these intersections. The signal controller is exported to Vissim and simulations are run to check the performance of the controller. The observations made from these simulations suggest that the the network performance is sufficient as there is no major traffic jams and a good level of service is achieved.

