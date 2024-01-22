The Device aims to enhance the training of nursing students at a university's smart hospital by using standardized patients who are actually healthy. The challenge is training students to identify abnormal body sounds since these actors have healthy internal sounds. The solution involves using reprogrammable chips worn by the standardized patients. These chips, when scanned, will emit audio mimicking various internal body sounds associated with different ailments. This system allows nursing students to learn and recognize unhealthy body sounds, providing a more effective and versatile training tool for a variety of medical scenarios.


The RFID Smart Stethoscope (RSS) project is designed with a three-layer architecture for medical training:

RFID Layer: Manages RFID tags interactions, each tag corresponding to a different body part.

Stethoscope Layer: Incorporates the RFID scanner and sound database to output specific auscultation sounds through headphones based on tag IDs.

Application Layer: Enables programming and uploading of audio files for various body parts, updating the sound database in the Stethoscope layer.

This structure ensures efficient operation from tag scanning to auditory output, enhancing medical training effectiveness.


The RFID Smart Stethoscope project was meticulously implemented in three layers: the RFID layer for tag interaction, the Stethoscope layer for audio processing, and the Application layer for sound programming and management. Initial prototyping was focused on ensuring hardware reliability and software accuracy, with subsequent iterations refining the integration of the layers. Through iterative development, the project achieved a seamless synergy between the physical components and the software interface. Prototyping encompassed both the physical assembly of the RFID-enabled stethoscope and high-fidelity simulations to emulate real-world clinical conditions. The testing regimen included functional verification of tag readability, audio fidelity assessments, and end-user interface usability. Simulations played a critical role in replicating the clinical environment, allowing for adjustments to system responses and user interaction before deployment. The test plan for the RSS project was comprehensive, covering unit, integration, system, and usability testing. Future work will look towards expanding the system’s capabilities, including a wider range of simulated conditions, and exploring the integration of machine learning to adapt to user proficiency. Enhancements will be guided by ongoing user feedback and technological advancements in RFID and audio output systems.

The RFID Smart Stethoscope is a useful tool for the UTA Smart Hospital to use to help train nursing students here at UTA. Future enhancements could include expanding the singular stethoscope into a full fleet of stethoscopes so that a whole class of students could have access to this new training method. Introduction of more body parts and more accurate sounds would also improve the accuracy of simulations.

References:
1. “Pisugar 3: Battery for raspberry pi zero,” 2021, hardware component.
2. R. P. Foundation, “Raspberry pi zero,” 2015, hardware component.
3. RASPIAUDIO, “Audio dac hat sound card (audio+v2) for raspberry pi4 all models pi zero / pi3 / pi3b / pi3b+ / pi2,” 2019, better Quality Than USB. Hardware component.
4. “Rfid laundry tags 13.56 mhz hf,” 2019, designed to be imbedded or attached to bed linens, towels,and primary medical scrubs or uniforms. PPS + epoxy design. Available with both ISO 15693 and14443 NFC memory chips.
5. Stemedu, “Rc522 rfid reader writer module rf ic card sensor with s50 white card +
writable keyring for arduino for raspberry pi nano nodemcu (pack of 2sets),” 2018, hardware component.
