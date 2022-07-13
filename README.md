# SkinDisorderDetectionModel
In this project, WE're performing multi-class classification to detect the type of skin disorder

## Business Case for Skin Disease Detection
 
The dataset consists of information about 6 kinds of skin disorder.The details are as follows
 
the family history feature has the value 1 if any of these diseases has been observed in the family, and 0 otherwise. 
 
The age feature simply represents the age of the patient. 
 
Every other feature (clinical and histopathological) was given a degree in the range of 0 to 3. 
 
Here, 0 indicates that the feature was not present, 3 indicates the largest amount possible, and 1, 2 indicate the relative intermediate values. 
 
Number of Instances: 366 
 
Number of Attributes: 34 
 
Attribute Information: -- Complete attribute documentation: Clinical Attributes: (take values 0, 1, 2, 3, unless otherwise indicated) 
1: erythema 
2: scaling 
3: definite borders 
4: itching 
5: koebner phenomenon 
6: polygonal papules 
7: follicular papules 
8: oral mucosal involvement 
9: knee and elbow involvement 
10: scalp involvement 
11: family history, (0 or 1) 34: Age (linear) Histopathological Attributes: (take values 0, 1, 2, 3) 
12: melanin incontinence 
13: eosinophils in the infiltrate 
14: PNL infiltrate 
15: fibrosis of the papillary dermis 
16: exocytosis 
17: acanthosis 
18: hyperkeratosis 
19: parakeratosis 
20: clubbing of the rete ridges 
21: elongation of the rete ridges 
22: thinning of the suprapapillary epidermis
23: spongiform pustule 
24: munro microabcess 
25: focal hypergranulosis 
26: disappearance of the granular layer 
27: vacuolisation and damage of basal layer 
28: spongiosis 
29: saw-tooth appearance of retes 
30: follicular horn plug 
31: perifollicular parakeratosis 
32: inflammatory monoluclear inflitrate 
33: band-like infiltrate 8. Missing Attribute Values: 8 (in Age attribute). Distinguished with '?'. 
 
Class Distribution: Database: Dermatology Class code: Class: Number of instances: 
1 psoriasis 112 
2 seboreic dermatitis 61 
3 lichen planus 72 
4 pityriasis rosea 49 
5 cronic dermatitis 52 
6 pityriasis rubra pilaris 20 
 
Task:1 Determine which features is impacting for a particular skin disorder (for all classes)
Task2:-Create a machine learning model which will predict the disorder available.
Task:3:-Perform the EDA and show the trend of the disease.
