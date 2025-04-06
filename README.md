# Proiect-TSC 
Tulumb Radu Cristian 332CB
e-book reader


In prima parte a proiectului cand am realizat schematicul m-am folosit de descrierea pieselor din pdf-ul de pe ocw pentru a denumi, aranja si a da valori componentelor. am schimbat de fiecare data layerul cand ba puneam nets ba symbols ba lines. M-am folosit de toolurile necesare pentru a schimba numele si valorile pieselor apoi am dat switch in pcb.

In pcb am tinut cont de masuratorile de pe ocw si de pozitia componentelor. Ca sa ma asigur ca dimensiunea placutei este corecta am modificat gridul pcb-ului in 1 mm cu 1 mm pentru a determina daca este dimensiunea corecta. Rutarea a fost mai complicata, dar am reusit sa o fac pe layerul de top si bottom. Mai aveam doua erori hole carora le-am dat aprove. Pentru a continua am dat switch in pcb3d.

Am cautat piesele individual folosind design manager si sintaxa (ObjectType = Device) AND (Name = "piesa respectiva") pentru a cauta piesa pentru care urma sa fac un model 3d. Modelele 3d au fost luate de pe Mouser, Snapeda, SnapMagic si componentsearchengine unde am gasit modelele 3d pentru fiecare piesa in parte. Am creat un fisier special cu toate modelele 3d necesare, le-am rotit si ajustat pentru a se incadra in linia punctata verde si intre cele doua puncte versi si i-am dat replace package apoi am salvat, am dat in pcb update apoi cand dadeam switch to pcb3d imi punea piesa pe placuta. Pentru tp-uri am desenat un cerc.

Componentele alaturi de datasheet-ul acestora este in BOM\Radu\Admin Project\CAMOutputs\Assembly\proiect2025v19.csv 
EX:
1	MAX17048G+T10	MAX17048G+T10	SON50P200X200X80-9N	U4	Check availability			In Stock		https://www.snapeda.com/parts/MAX17048G+T10/Analog+Devices/view-part/?ref=eda			 3µA 1-Cell/2-Cell Fuel Gauge with ModelGauge 							Analog Devices						MAX17048G+T10		TDFN-8 Maxim			None		https://www.snapeda.com/api/url_track_click_mouser/?unipart_id=329239&manufacturer=Analog Devices&part_name=MAX17048G+T10&search_term=None		https://www.snapeda.com/parts/MAX17048G+T10/Analog+Devices/view-part/?ref=snap						
3	MBR0530	MBR0530	SOD3716X135N	D3, D4, D5	ON SEMICONDUCTOR - MBR0530 - DIODE, SCHOTTKY, 0.5A, 30V, SOD-123			In Stock		https://www.snapeda.com/parts/MBR0530/Onsemi/view-part/?ref=eda			 Diode Schottky 30 V 500mA Surface Mount SOD-123 							ON Semiconductor						MBR0530		SOD-123-2 ON Semiconductor			None		https://www.snapeda.com/api/url_track_click_mouser/?unipart_id=179458&manufacturer=ON Semiconductor&part_name=MBR0530&search_term=None		https://www.snapeda.com/parts/MBR0530/Onsemi/view-part/?ref=snap						
6	PGB1010603MR	PGB1010603MR	DIOC1608X36N	D6, D8, D9, D10, D11, D12	Check availability			In Stock		https://www.snapeda.com/parts/PGB1010603MR/Littelfuse/view-part/?ref=eda			 150V (Typ) Clamp - Ipp Tvs Diode Surface Mount 0603 (1608 Metric) 							Littelfuse Inc.						PGB1010603MR		0603 Littelfuse Inc.			None		https://www.snapeda.com/api/url_track_click_mouser/?unipart_id=5659453&manufacturer=Littelfuse Inc.&part_name=PGB1010603MR&search_term=None		https://www.snapeda.com/parts/PGB1010603MR/Littelfuse/view-part/?ref=snap					
