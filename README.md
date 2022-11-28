# ARVR-Africa-3D-Nursing-VR-Simulator
this is an education project for nursing simulation. It's submitted to the contest of ARVR Africae 2022 (online hackthon).

# Team
- Dina AL-Shorbagy
- Amira El sayed
- Alaa’ Allah Hilal
- Dr-Mona Gabr
- Waleed Mohamed


# introduction
Importance virtual reality on nursing education: VR has gained increasing attention in the field of nursing education and been used to teach many nursing concepts including communication, decision-making, critical thinking, inclusivity, health appraisal, and disaster triage for example, COVID19. 
VR simulations can give nursing students the opportunity to practice skills in a safe environment without risk to patients and facilitate learning process.
 Comparing with the traditional health education courses, VR technology provides opportunities for nursing students to investigate the 3D human body structure with vivid learning experience rather than traditional methods.
 
# solution
3D Nursing Simulator :
- Mobile VR
- Unity Technology
- Gaze-Based Interaction
- Hand Mocap using UltraLeap Camera for some animations
- Blender Modeling + online assets
- Economic Cost 
- Target Users: Students and Nursing Teachers

# Demo
3 Experiments :
1. IV Infusion ( reference : https://www.youtube.com/watch?v=_S8JfTbZbdk)
2. ECG procedure (reference: https://geekymedics.com/record-ecg/)
3. Neonatal Resuscitation (reference: https://www.youtube.com/watch?v=0WhEtCygUJM )

https://youtu.be/rjOocXlapd8
<video src="https://youtu.be/rjOocXlapd8"/>

[![My Image](/Capture.PNG)](https://youtu.be/rjOocXlapd8)

# how to test the project 
the project can be tested in one of the following 2 options:
1. using unity project source 
2. using Android Application
## Option 1: testing using source code:
1. Clone the project from github
2. use unity 2021.1.26f1 or newer version
3. open the project from the sub-folder: “\Source\Nursing-Sim”
4. open the main scene at “Assets\Scenes\VR_MenuLobby.unity”
## Option2: Testing using Android APK:
1. Install the application APK from path : “Executable-Android APK\N20.apk”
2. open the application NursingSimulator2 using android mobile
3. put the mobile device inside a mobile headset
4. the application is gaze based (ie. it uses eye direction to select action), to select any action keep looking at it for about 2 seconds till the yellow circular progress completes
# Mobile Controls
The mobile application is gaze based, so it depends on head rotation and eye looking duration.
1. camera rotation: is done by rotating head
2. Movement (Walking): it’s teleportation based. So, you can move by looking 2 seconds into one of the green boxes on the ground. When the yellow circle completes the teleportation is executed and position changes.

![moving](/move.PNG)

3. Using items and UI buttons: if item is usable, then by looking at it a blue panel appears, and if looking time is 2 seconds, then a yellow circle is completed and the item is used. 

![using](/use-1.PNG)
![using](/ui.PNG)

# Target Scenarios for the Nursing Experiments:
here are the required steps to follow for each experiment:
## IV Infusion steps( reference : https://www.youtube.com/watch?v=_S8JfTbZbdk)
    1. please start by washing your hands
    2. Then, Wear the medical glove
    3. Now, Check Patient ID
    4. Next, Check Dose and any possible Allergy in the doctor's report
    5. Next, Prepare Dose by using syringe
    6. Good Work, Now Connect I.V. Bag
    7. Very good, then Hang I.V. Bag to Dropper
    8. And Now, Connect IV to Patient's Arm
    9. well done, You Have Completed the procedure
## ECG procedure steps(reference: https://geekymedics.com/record-ecg/)
    1. Identify the fourth intercostal space (starting at the sternal angle)
    2.  Attach V1: 4th intercostal space at the right sternal edge.
    3.  Attach V2: 4th intercostal space at the left sternal edge.
    4.  Attach V4: 5th intercostal space in the midclavicular line.
    5. Attach V3: midway between the V2 and V4 electrodes.
    6. Attach V5: left anterior axillary line at the same horizontal level as V4.
    7. Attach V6: left mid-axillary line at the same horizontal level as V4 and V5.
    8. Attach Red (RA): on the ulnar styloid process of the right arm.
    9. Attach Yellow (LA): on the ulnar styloid process of the left arm.
    10. Attach Green (LL): on the medial or lateral malleolus of the left leg.
    11. Attach Black (RL): on the medial or lateral malleolus of the right leg.
## Neonatal Resuscitation steps  (reference: https://www.youtube.com/watch?v=0WhEtCygUJM )
    1. first lets dry the baby's body then wrap it with a dry towel
    2. pickup the stethoscope
    3. next, Locate the heart position .... then Use the stethoscope to check heart rate , also check the color... tone ... and breathing of the baby 
    4. BE CAREFUL! There is a breathing problem, it needs 5 inflation breaths procedure... to start, choose the suitable size mouth mask.
    5. The mouth mask is attached to bag valve unit. pickup the bag valve
    6. to start the 5 inflation breaths procedure, locate baby's mouth position and put the bag valve mask unit
    7. Good work, however the baby still needs Cardiac Compression... Locate Baby's Chest and press 3 times

 
