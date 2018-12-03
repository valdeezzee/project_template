# Research Practicum 2018 – Research Plan
(text between brackets to be removed)

> * Group Name: MYOwn Reality 
> * Group participants names: Kamryx Davis, Jonathan Valderrama
> * Project Title: VR environments for amputee prosthetics training and rehabilitation

![Picture from Unity Scene](https://github.com/valdeezzee/project_template/blob/master/TS.PNG "Picture from Unity Scene")

## Purpose Statement
The purpose of this study is to explore different way of mitigating phantom limb pain in amputees and providing alternate methods for prosthetics training and rehabilitation.

## General Introduction

(States your motivation clearly: why is it important / interesting to solve this problem?)
(Add real-world examples, if any)
(Put the problem into a historical context, from what does it originate? Are there already some proposed solutions?)

The amount of people living with limb loss is increasing. There is an estimate of 185,000 people that have gone through a upper or lower limb amputation each year. In the United States, it is expected that the amount of people living with limb loss will more than double in 45 years. In 2005 that amount was estimated at 1.6 million people and it's predicted to increase to 3.6 million in 2050. The drastic increase is due to obesity which can cause dysvascular conditions like diabetes which can lead to limb amputation (Ziegler-Graham et al., 2008). It is not easy living with an lost limb and it becomes tougher to do simple everyday tasks. There is a phenomenon called phantom limb pain (PLP) where there is a sensation of pain in an absent limb in which 40% to 85% of amputees suffer from (Chau et al., 2017). Psychological disorders tend to appear in most people with PLP, including anxiety(66%) and depression(41%). Apart from taking pharmaceutical drugs and mirror therapy, there are not many treatments for mititgating PLP. There are two main psycological interventions being used to treat PLP, mental imagery and mirror therapy. 

With the increasing amount of amputees, there is sure to be a need for more training. There has been studies done for VR therapies but they had small amount of test subjects. So conducting more of these types of simulations can benefit to add more research and data to the community.

To tackle this problem, we plan on using Virtual Reality with the combination of the MYO armband. With VR we want to create realistic environments to immerse the user and help reduce pain with different forms of distractions. In the simulation we will have hand and/or arm assets to create the illusion of Virtual Body Ownership. This way the users mind can be convinced that the virtual arm is theirs. The myo armband will be used to collect muscle signals that then get translated to hand gestures. With the hand gestures we will create animations that correspond to the hand gestures the user is making. In addition, we want to create simple tasks that the user can perform. These task will be taken from the Southampton Hand Assessment Procedure (SHAP). It is a clinically validated hand function test. 

Contributions
1. VR therapy and rehabilitation
2. Pre and post rosthetics training
3. Avatar embodiment research


## Related Work


From several pieces of published literature, we have learned that amputation is becoming an increasingly larger problem worldwide and have learned possible treatments for the rehabilitation of amputees using virtual reality and myoelectric control. 
 
The three causes of limb loss in order of the largest are vascular diseases, trauma, and cancer.  In less than 50 years limb loss is expected to more than double. There are many statistics about amputation available. Amputee Coalition points out that within 5 years, almost half of the amputations caused by vascular diseases will die (Amputee Coalition, 2018). According to Advanced Amputee Solutions, LLC worldwide there are over 1 million limb amputations a year, that's one every 30 seconds (Advanced Amputee Solutions, LLC, 2012). As amputation becomes a larger problem, a better way to rehabilitate amputees is needed.  

Many of these papers explored the concept of virtual body ownership, on how the brain distinguishes what is part of our body and what is not. This can be seen in "Inducing Illusory Ownership" by Slater et. al where experiments were conducted with a virtual reality adaptation of the rubber hand illusion, in which the subject is fooled to think a rubber hand is their own. The mind can be convinced that a virtual body is their own with synchronous actions between their body and the virtual reality model (Slater et. al, 2009). Virtual embodiment has also been used to allow people to see different things from different perspectives such as the rehabilitation of violent behavior allowing the aggressor to see a violent situation through the eyes of the victim or by reducing racism by putting a person in a body of a different color. Appearance of the avatar or virtual body part have also been shown to have an effect on pain, body temperature, and virtual body ownership. Some of this can be seen in "Avatar Embodiment Realism and Virtual Fitness Training," where they focused on gender and realism of avatars on the illusion of virtual body ownership. They concluded that “same-gender realistic human  avatar  elicited  a  slightly  higher  level  of  illusion and performance," but qualitatively the users felt more powerful "with non-realistic strong-looking avatars" (Lugrin et. al, 2015). 

There have been several experiments done with rehabilitation, training, and therapy after conditions such as amputation, stroke, and neurological impairment in the medical industry using newer technologies and techniques such as virtual reality, body sensors, and nerve remapping, but many done with a small number of test subjects. More studies can be done in these areas. Some studies have explored using the Myo Armband for these purposes such as collecting electromyography data to detect progress made in therapy and to control virtual hands such as in "Immersive Virtual Reality Therapy with Myoelectric Control for Treatment-resistant Phantom Limb Pain: Case Report" by Chau et. al. where this was used to treat Phantom Limb Pain. This treatment was successful, but only tested on one subject (Chau et. al, 2017). Different VR environments and games have been used in the rehabilitative process. From these experiments we have seen VR be successful in reducing pain and anxiety, and as a distraction for people going through medical procedures.  

## Research Questions 
1.	Will variables such as gender and age affect the completion times of the SHAP tests in the VR environment?
2.	Will VR limb variables such as hand and arm appearance affect the completion times of the SHAP tests?
3.	Will the VR environment combined with SHAP tests and the MYO armband affect the subjects’ pain levels?
4. Will the subjects' SHAP tests completion times change with multiple trials? 


## Research Methods

![Picture from Unity Scene of SHAP Test](https://github.com/valdeezzee/project_template/blob/master/UHS.PNG "Picture from Unity Scene")

We will be using Unity3d to create a virtual enviroment where a user can run tests taken from Southampton Hand Assessment Procedure (SHAP). In Unity there are plugins to easily implement vr support and also plugins for the myo band. We will import hand assets and then modify their animations to match up with the different gestures the myo band is able to detect. Models will be created for the user to interact with and be able to perform the SHAP tests.

For each SHAP test there will be tasks. We will measure a users performance by time of complete of each test. We will also collect completion times of each task, gender and age. With collecting completion time, we will compare those numbers with the represented virtual limb variables. Some of those variable are going to be: just a hand, hand w/forearm, skin color, gender, glove, no glove. 

We will be using an Illusion Of Virtual Body Ownership (IVBO) Questionaire to see how strong the illusion of owning the virtual limb in the VR environment is. 

If participants are amputees, we want to be able to know the pain level a patient is expriencing before and after they are inside the virtual reality environment. We will be using a Short-Form McGill Pain Questionnaire, Visual Analog Scale (VAS) and the Wong-Baker FACES pain scale, to see if there is any changes in pain. 

• McGill Pain Questionnaire: https://www.physio-pedia.com/Short-form_McGill_Pain_Questionnaire

• VAS: https://www.researchgate.net/profile/Pradeep_Koppolu3/publication/295250172/figure/fig1/AS:333063214125059@1456419866974/Visual-analog-scale.png

• Wong-Baker: http://wongbakerfaces.org/wp-content/uploads/2015/06/FACES_English_Blue1.jpg

• Illusion Of Virtual Body Ownership (IVBO) Questionaire modified from (Lugrin, Latt & Latoschik, 2015) IVBO: https://docs.google.com/forms/d/e/1FAIpQLScio4NqZ1kkvEzopqWWGbSmwbG9qwz4K1_u_RrJSqMWwy6z9g/viewform?usp=sf_link

This is a mixed methods approach, as we collect qualitative data from the questionaires and quantitave data from the completion times in the VR environment. 

## Hypotheses
1.	The VR environment combined with the Southampton Hand Assessment Procedure (SHAP) tests and the MYO armband will not increase pain in the test subjects.
2.	Variables such as gender and age will affect the completion times of the SHAP tests in the VR environment.
3.	VR limb variables such as hand and arm appearance will affect the completion times of the SHAP tests.
4. The subjects' SHAP tests completion times will decrease with multiple trials. 


## Preliminary Framework
• Install Unity 3d

• Install MYO Connect App

• Setup scene in Unity

• Add hand models and modify animations

• Create scripts to manipulate hand with the MYO armband

## Plan of Attack / Rough Deliverables
• Create 2 rooms. Empty room as a control and a doctor's office.

• Model SHAP tasks and objects.

• Hand pick up and drop objects.

• Collect data from trials

• Plot data

• Create questionnaires

## Project Review

[**PPT Presentation**](https://github.com/valdeezzee/project_template/blob/master/project_review/Project%20Review.pptx)

[**Presentation Video**](https://www.useloom.com/share/d582eed1f20a4db9a9cf7f687656035c)

## Results

Results from SHAP Tests


[**MYOwn Reality Demo**](https://youtu.be/JQdwn2WIh4Q)

[**Live MYOwn Reality Demo**](https://youtu.be/L6HFFV_olrU)

![Spherical Control Room Data Graph](https://github.com/valdeezzee/project_template/blob/master/Spherical_Control.png "Spherical Control Room Data")


![Spherical Doctors Office Data Graph](https://github.com/valdeezzee/project_template/blob/master/Spherical_Doctors_Office.png "Spherical Doctor's Office Data")




Results of IVBO Questionaire (Scale is from 1 (Not at All) to 7 (Very Much)
![IVBO Questionaire Data Graphs](https://github.com/valdeezzee/project_template/blob/master/IVBO_Res.PNG "IVBO Questionaire Data")

Question 1: I felt like the body part I saw in the virtual world was my body part. <br/>
Mean: 3.75 <br/>
Mode: 5

Question 2: The illusion of owning a different body part than my real one was very strong during the experience. <br/>
Mean: 4 <br/>
Mode: N/A

Question 3: The movements I saw in the virtual world seemed to be my own movements. <br/>
Mean: 5.25 <br/>
Mode: 5

Question 4: I enjoyed controlling the virtual body part I saw in the virtual world. <br/>
Mean: 6 <br/>
Mode: 7

Question 5: At a time during the experiment I felt as if my real body part changed in its shape and/or texture. <br/>
Mean: 3.5 <br/>
Mode: N/A

Question 6: After taking off the head mounted display (HMD), I felt the need to check that my body part does really still look like to what I had in mind. <br/>
Mean: 3.25 <br/>
Mode: 1

Question 7: I felt an after-effect as if my body part had become lighter/heavier. <br/>
Mean: 3 <br/>
Mode: N/A

Question 8: How did you like the overall experience in the virtual world? <br/>
Mean: 6.5 <br/>
Mode: N/A

Question 9: I felt like the virtual body part I saw looked human. <br/>
Mean: 5 <br/>
Mode: 5

Overall IVBO score from Questions 1-9 </br>
Mean: 4.4722222 </br>
Mode: 5

Question 10: What exactly gave you the feeling that the virtual body part is your own, or what has prevented it? <br/>
Responses- "calibration was somewhat off and changed during the experiment, so I had to twist and adapt to get results in the experiment (grabbing motion)"; "the movement", "What has prevented it was the hand movements and the skin color", "Just how it moved as I moved my actual arm"

Question 11: When was the feeling of owning the virtual body part especially strong or weak? <br/>
Responses: "it was always more weak that strong, but that was due to the calibration", "strong", "It was stronger when the movements were in sync", "Whenever I picked up an object and moved it around with the virtual arm"

## Conclusions/ Future
VR combined with a MYO arm band is a possible way to train and rehabilitate amputees and provide prosthetics training. Based on the IVBO questionaire, we know that we need to make the movement between the user's hand and the virtual hand more synchronous to improve the illusion of virtual body ownership and increase the user's experience in the VR environment. 

If we had 1-2 more semesters, we could enhance this project and explore more possibilities. We would be able to increase the number of participants in the study. We could test this project out on actual amputees who suffer from phantom limb pain to see if this project decreased their pain levels. This could also be tested out to train amputees before and after they receive prosthetics and then compare it to the results of previous studies using traditional prosthetic training and rehabilitaion methods. We would also take time to discuss with the amputees and prosthetic users to find out their needs since they are the target users. We could make the tutorial for the users have more depth so they can better get acquainted to the VR environment, this will allow them to have a better feel of how it works and have a better user experience. We could also modify more hand and limb variables such as hand size, more variety of skin colors, and allow users to customize their own hands to see if that has a difference on the task completion times and feeling of virtual body ownership. We would also use hand models with better animations. The MYO armband doesn’t track wrist movement so we could include a wrist tracker to have more accurate hand movements. The MYO band only comes with 5 preset gestures, to make it recognize more gestures we’d have to write it into the code. We would also have participants do runs on multiple days to see if their scores improved with multiple sessions. We would also have incorporate breaks into the experiment, so the user can rest their arms. Using 2 MYO bands, one for each arm could be explored, so that one arm is isn't doing all the work. This can achieve more balance as both hands are working togther. This VR training and rehabilitation environment could be made more game like and include different activities such as cooking, painting, and playing sports to make it more fun and prepare amputees to do those activities with their prosthetic limb. Artificisl intelligence (AI) could also be used to make the training and rehabilitation more personalized and adaptive to individual needs. Also the possibility of building a prosthetic controlled with the MYO armband could be explored.

## References 

Advanced Amputee Solutions, LLC. (2012). Amputee Statistics You Ought to Know. Retrieved from http://www.advancedamputees.com/amputee-statistics-you-ought-know

Amputee Coalition. (2018). Limb Loss Statistics. Retrieved from http://www.amputee-coalition.org/limb-loss-resource-center/resources-filtered/resources-by-topic/limb-loss-statistics/limb-loss-statistics/

Carlson, L. E., Choquette, E. J., Ulrey, B. L., & Carley, P. J. Facilitation of Upper Extremity Rehabilitation Using the Myo Armband.

Chau, B., Phelan, I., Ta, P., Humbert, S., Hata, J., & Tran, D. (2017). Immersive virtual reality therapy with myoelectric control for treatment-resistant phantom limb pain: Case report. Innovations in clinical neuroscience, 14(7-8), 3.

Gilpin, H. R., Bellan, V., Gallace, A., & Moseley, G. L. (2014). Exploring the roles of body ownership, vision and virtual reality on heat pain threshold. European Journal of Pain, 18(7), 900-901.

Lugrin, J. L., Landeck, M., & Latoschik, M. E. (2015, March). Avatar embodiment realism and virtual fitness training. In Virtual Reality (VR), 2015 IEEE (pp. 225-226). IEEE.

Lugrin, J. L., Latt, J., & Latoschik, M. E. (2015, October). Anthropomorphism and illusion of virtual body ownership. In Proceedings of the 25th International Conference on Artificial Reality and Telexistence and 20th Eurographics Symposium on Virtual Environments (pp. 1-8). Eurographics Association.

Martini, M., Pérez Marcos, D., & Sanchez-Vives, M. V. (2013). What color is my arm? Changes in skin color of an embodied virtual arm modulates pain threshold. Frontiers in human neuroscience, 7, 438.

Slater, M., Pérez Marcos, D., Ehrsson, H., & Sanchez-Vives, M. V. (2009). Inducing illusory ownership of a virtual body. Frontiers in neuroscience, 3, 29.

Ziegler-Graham, K., MacKenzie, E. J., Ephraim, P. L., Travison, T. G., & Brookmeyer, R. (2008). Estimating the prevalence of limb loss in the United States: 2005 to 2050. Archives of physical medicine and rehabilitation, 89(3), 422-429.
