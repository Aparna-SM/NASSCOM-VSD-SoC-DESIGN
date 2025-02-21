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

# DAY 2 - Introduction to Magic
%run_floorplan
![floorplan default val](https://github.com/user-attachments/assets/b26065a7-28ef-4e0f-a18d-41fea275abab)

open the floorplan output files to know the die value 
![placement ](https://github.com/user-attachments/assets/4b6c171d-bc9d-4731-b3a6-16b20d54e825)
use the command magic -T to open the magic tool 
![openingg magic](https://github.com/user-attachments/assets/883300f8-40cf-4401-997c-b7103df13e1b)
![magic](https://github.com/user-attachments/assets/02a06878-a361-45d3-b58d-62a4af0a123a)
Keep press 'S' to select and 'V' to align the design in the centre (back to position)
![mux](https://github.com/user-attachments/assets/61c51ce0-e822-48e7-b866-16bc6b66705f)
![what= where it is ](https://github.com/user-attachments/assets/10399d8a-dd2f-4d69-a2df-d294b4d09f7b)

%run placement 
![Screenshot 2025-02-18 220331](https://github.com/user-attachments/assets/fd21b421-5113-4421-8e97-4499fe1600bf)

review in magic 
![magic view ](https://github.com/user-attachments/assets/deba5cd4-a8e2-4cc1-b675-eaf3801b0765)









