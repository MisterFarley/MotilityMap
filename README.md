# MotilityMap

Beta Version

Overview
The Binocular Vision Diagnostic Tool is an interactive web application designed to assist optometrists and eye care professionals in the systematic diagnosis and documentation of ocular motility disorders. It streamlines the assessment process with a guided diagnostic flow, dynamic visual feedback on eye conditions, and convenient patient data management features.

Features
Guided Diagnostic Flow: Navigate through a logical sequence of questions to pinpoint potential binocular vision anomalies and cranial nerve palsies.
Lateralized Diagnosis: Specifically evaluate and diagnose conditions affecting the left or right eye, leading to more precise results.
Enhanced Gaze Grid Visualization:
Dynamic Eye Representations: See affected eye positions visualized directly on an interactive gaze grid, with condition-specific emojis and symbols.
Animated Effects: Conditions like Myasthenia Gravis (fatigable eye) and Nystagmus (oscillating eye) are represented with subtle animations for improved clarity.
Measurement Overlays: Key measurement data (e.g., prism diopters) can be displayed directly on the grid positions.
Special Visual Cues: Indications for ptosis, dilated pupils, globe retraction, and head/face turns enhance understanding.
Patient Data Management:
Cloud Saving: Securely save diagnostic sessions to a Firebase Firestore database.
Load Previous Sessions: Easily retrieve and review past patient diagnoses.
Comprehensive PDF Summaries: Generate printable PDF reports of each diagnosis, including patient details, the final diagnosis, key differentiating features, the visual gaze grid, and the complete diagnostic path history.
How to Use
Start a New Diagnosis: Begin by answering the initial assessment questions.
Follow the Flow: Select the options that best describe the patient's symptoms or test findings.
Interactive Gaze Grid: Observe how the gaze grid visualization updates dynamically to reflect the suspected condition. Pay attention to specific eye movements, affected eyes, and any applied visual effects.
Complete the Diagnosis: Continue until a final diagnosis is presented.
Enter Patient Details: Once a diagnosis is reached, fill in the patient's name, ID, and clinician details.
Save & Share:
Click "Save Current Diagnosis" to store the session in the cloud.
Click "Download PDF Summary" to generate a printable report.
Use "Load Saved Diagnoses" to view and restore previous sessions.
