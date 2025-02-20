# NASSCOM-VSD-SoC-DESIGN
Repository for VLSI SoC Design

DAY 1
To run openlane version 0.9 

![openlane](https://github.com/user-attachments/assets/b6a84693-1a48-4b34-9f68-e4135cd0e84d)
%prep -design picorv32a
![designs](https://github.com/user-attachments/assets/ab19eab9-95a9-420e-b039-c766c9ae5490)
%run_synthesis
![final synthesis](https://github.com/user-attachments/assets/2919a43b-cbd6-42b2-9812-919d28c7354e)
open "runs" file and go to results
![results](https://github.com/user-attachments/assets/21738ae5-493d-4020-8857-434290fefa5f)
Go to synthesis and get the merged file after which check the yosys file to find flop ratio
![tmp](https://github.com/user-attachments/assets/2c4122c8-c59f-446f-b47f-342d9bd6c9c4)
![less yosys,opensta](https://github.com/user-attachments/assets/286696eb-cfc9-4abe-9ab0-cd178ea14492)

![yosys](https://github.com/user-attachments/assets/bd7cb593-f146-4716-a006-03e79bcf1c99)
Total no.of cells = 14876 ;
count of D flip flop = 1613 ;
Flop ratio = 1613/14876 = 0.1084 [10.84%] ;
![opensta rpt](https://github.com/user-attachments/assets/caac2564-3771-49b6-bd14-d54ca27e0e9f)


