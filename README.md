# Skin-Disorder-Prediction
Create a predictive model using machine learning techniques to predict the various classes of skin disease.

DataSet Information:-
Class
1: psoriasis
2: seboreic dermatitis
3: lichen planus
4: pityriasis rosea
5: cronic dermatitis
6: pityriasis rubra pilaris
Family history:
1: if any of these diseases has been observed in the family
0: otherwise
Age:
Represents the age of the patient
All other attributes:
0: feature not present
1,2 indicate the relative intermediate values
3 indicates the largest amount possible


Suggestions to the Doctors to identify the skin diseases of the patient at the earliest.
where feature is not present.
A Patient who has feature not present in itiching,koebner phenomnen,polygonal papules,folicular papules,oral mucosal involvement,melanin incontinece,eosinophils_in_the_infiltrate,PNL filtrate,fibrosis_of_the_papillary_dermis,exocythsis, hyperkeartosis,spongiform pustle,munro microbcess,focal hypergranulosis,disappearance_of_the_granular_layer, vacuolisation_and_damage_of_basal_layer,spongiosis,saw teeth apperance of the retes,folicular horn plug,perifolicular parakeratosis,band like infiltrate they all have highest chance of having class 1 (psoriasis) skin dieases problem.
A Patient who has feature not present in definite border,koebner phenomnen,polygonal papules,folicular papules,oral_mucosal_involvement,knee and elbow envolvement,scalp envolvement,melanin_incontinence, eosinophils_in_the_infiltrate,fibrosis_of_the_papillary_dermis,aconthosis,hyperkeratosis,perakeratosis, clubbing_of_the_rete_ridges,elongation_of_the_rete_ridges,thinning_of_the_suprapapillary_epidermis,spongiform_pustule, munro_microabcess,focal_hypergranulosis,disappearance_of_the_granular_layer,vacuolisation_and_damage_of_basal_layer,saw- tooth_appearance_of_retes,follicular_horn_plug,perifollicular_parakeratosis,inflammatory_monoluclear_inflitrate,band- like_infiltrate they have highest chance of having class 2 (seboreic dermatitis) skin dieases problem.
A Patient who has feature not present in koebner_phenomenon,folicular papules,knee and elbow envolvement,scalp envolvement,eosinophils_in_the_infiltrate,PNL inflitrate,fibrosis_of_the_papillary_dermis,hyperleratosis,perekeratosis, clubbing_of_the_rete_ridges,elongation_of_the_rete_ridges,thinning_of_the_suprapapillary_epidermis,spongiform pustule, munro_microabcess,disappearance_of_the_granular_layer,spongisis,perifollicular_parakeratosis they have highest chance of having class 3 (lichen planus) skin disorder problem.
A Patient who has feature not present in definite border,itiching,koebner_phenomenon,polygonals papules,folicular papules,oral_mucosal_involvement,knee_and_elbow_involvement,scalp involvement,melanin_incontinence, eosinophils_in_the_infiltrate,PNL infiltrate,fibrosis_of_the_papillary_dermis,acanthosis,hyperkeratosis,perekeratosis, clubbing_of_the_rete_ridges,elongation_of_the_rete_ridges,thinning_of_the_suprapapillary_epidermis,spongiform_pustule, munro_microabcess,focal_hypergranulosis,disappearance_of_the_granular_layer,vacuolisation_and_damage_of_basal_layer, saw- tooth_appearance_of_retes,follicular_horn_plug,perifollicular_parakeratosis,band-like_infiltrate they all have highest chance of having class 4 (pityriasis rosea) skin dieases problem.
A Patient who has feature not present in erythema,definite border,scaling,itiching,koebner phenomnen,polygonal_papules, follicular_papules,oral_mucosal_involvement,knee_and_elbow_involvement,scalp involvement,melanin_incontinence, eosinophils_in_the_infiltrate,PNL infiltrate,exocytosis,hyperkeratosis,perakeratosis,clubbing_of_the_rete_ridges, thinning_of_the_suprapapillary_epidermis,spongiform_pustule,munro_microabcess,focal_hypergranulosis, disappearance_of_the_granular_layer,vacuolisation_and_damage_of_basal_layer,spongiosis,saw-tooth_appearance_of_retes, folicular horn plug,perifollicular_parakeratosis,band-like_infiltrate they all have highest chance of having class 5 (cronic dermatitis) skin disorder problem.
A Patient who has feature not present in definite border,itiching,koebner_phenomenon,polygonal papules,munro_microabcess, oral_mucosal_involvement,scalp involvement,melanin_incontinence,eosinophils_in_the_infiltrate,PNL inftitrate, fibrosis_of_the_papillary_dermis,clubbing_of_the_rete_ridges,elongation_of_the_rete_ridges,spongiform_pustule, thinning_of_the_suprapapillary_epidermis,focal_hypergranulosis,disappearance_of_the_granular_layer,saw- tooth_appearance_of_retes,vacuolisation_and_damage_of_basal_layer,band-like_infiltrate they all have highest chance of having class 6 (pityriasis rubra pilaris) skin disorder problem.

Intermediate level of skin dieases.
A Patient who has intermediate level of erythema,scaling,definite border,knee and elbow envolvement,scalp envolvement,PNL infitrate,acanthosis,hyperkertosis,parakeratosis,clubbing of the rate ridge,elegation of the rate ridge,sponiform pustle,munro microbsess,disapperiance of the granular layer,inflammatory monoluclear inifitrate they all have highest chance of having class 1 (psoriasis) skin disorder problem.
A Patient who has intermediate level of erythema,scaling,definite border,itiching,koebner phonomenon,poligonal papules,oral mucosal invlovement,melanin incontience,exocytosis,acanthosis,focal hypergranulosis,vacuolisation and damage of base layer,saw tooth apperance of retes,inflammatory monocular inflitrate they all have highest chance og having class 3 (lichen planus) skin dieases problem.
A Patient who has intermediate level of erythema,scaling,itiching,PNLinflatrate,expcytosis,acanthosis,spngosis, inflammatory monoluclear inifitrate they all have highest chance of having class 2 (seboreic dermatitis) skin dieases problem.
A Patient who has intermediate level of erythema,scaling,definite border,koebner phonemnon,exocytosis,acanthosis,perakeratosis,spongiosis,inflammatory monoluclear inifitrate they all have highest chance of having class 4 (pityriasis rosea) skin dieases problem.
A Patient who has intermediate level of erythema,itiching,fibrosis of the papilarydermis,aconthosis,hyperkeratosis, perakeratosis,elegation of the rete ridges,inflammatory monoluclear inifitrate they all have highest chance of having class 5 (cronic dermatitis) skin dieases problem.
A Patient who has intermediate level of erythema,scaling,folicular papules,knee and elbow envolvement,scalp involvement,acanthosis,hyperkeartosis,folicular horn plug,perifolicular perakeratosis they all have highest chance of having class 6 (pityriasis rubra pilaris) skin dieases problem.

High chances of skin dieases.
A Patient who have largest amount possible of erythema,scaling,definite border,itiching,knee and elbow envolvement,scalp envolvement,PNL infiltrate,acanthosis,hyperkeratosis,perekeratosis,clubbing_of_the_rete_ridges, elongation_of_the_rete_ridges,thinning_of_the_suprapapillary_epidermis,spongiform_pustule,munro_microabcess, disappearance_of_the_granular_layer,inflammatory_monoluclear_inflitrate they all have highest chance of having class 1 (psoriasis) skin disorder problem.
A Patient who have largest amount possible of erythema,scaling,itiching,eosinophils_in_the_infiltrate,PNL infiltrate,exocytosis,acanthosis,spongiosis,inflammatory_monoluclear_inflitrate they all have highest chance of having class 2 (seboreic dermatitis) skin disorder problem.
A Patient who have largest amount possible of erythema,scaling,definite border,itiching,koebner_phenomenon, polygonal_papules,band-like_infiltrate oral_mucosal_involvement,melanin_incontinence,exocytosis,acanthosis, focal_hypergranulosis,spongiosis,vacuolisation_and_damage_of_basal_layer,saw-tooth_appearance_of_retes, inflammatory_monoluclear_inflitrate they all having highest chance of class 3 (lichen planus) skin disorder problem.
A Patient who have largest amount possible of erythema,koebner_phenomenon,exocytosis,spongiosis, inflammatory_monoluclear_inflitrate they all have highest chance of having class 4 (pityriasis rosea) skin disorder problem.
A Patient who have largest amount possible of erythema,scaling,definite border,itiching,fibrosis_of_the_papillary_dermis, acanthosis,elongation_of_the_rete_ridges,inflammatory_monoluclear_inflitrate they all have highest chance of having class 5 (cronic dermatitis) skin disorder problem.
A Patient who have largest amount possible of erythema,follicular_papules,knee_and_elbow_involvement,exocytosis, spongiosis,follicular_horn_plug,perifollicular_parakeratosis,inflammatory_monoluclear_inflitrate they all have highest chance of having class 6 (pityriasis rubra pilaris) skin disorder problem.
Patient whose family has no skin dieases they have high chance of having class 1 and 3, and 50-50% chance of 2,4 and 5 and those patient which family has skin dieases they have high chance of having class 1 and 6.

By follow this all instructions doctors can find any skin disorder of class 6 class qiuckly.
