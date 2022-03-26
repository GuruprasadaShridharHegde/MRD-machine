# MRD-machine
### Abstract
Our project involves the design & development of medicine reminder and dispensing machine based on healthcare system. As per the current situation this innovative system is needed because there is no cure for COVID-19 yet, although patients are given some medicines by nurses and doctors to ease the pain, increase immunity, and reduce symptoms. But this puts our healthcare warriors at risk when they give the medicine to patients, thus we planned to develop a machine that can take in the medicine doses of an entire week, store them and supply them to the patient at the time set by the doctor once, at the start-up of the machine. This will ensure distancing from patients and nurses won't have to risk their lives to go and give medicine to the infected patient. Once the medicine is on the given rack from where the patient can take it, he/she is alerted via a speaker on the system to take the medicine. 
	The data of when the medicine is taken is stored in an SD card for further reference by doctors to monitor the effect on symptoms by the given dose. This machine can also be used in houses where old patients forget to take medicines on time and need a caretaker to provide them each dose. For using it in households, there is one more feature added- exercise and food times of the patient can be stored and act as a reminder, and the machine can also act as an alarm clock and can store 3 alarms. Food and exercise times help patients since there are certain medicines that need to be taken at proper intervals before or after food. The work concludes with an application being demonstrated practically in the college.
  
 ### Introduction:
  Good health is important for a good life and it is quite necessary to give priority to
health related issues which can be solved by digitization using a variety of devices. All are aware
of current situation that is how Covid-19 is affecting on entire human life and healthcare warriors
are serving the patients even putting their life in danger. So as a part of that we studied in detail
about the whole system where we can give better system to society by using our technical
knowledge and skills. Finally came to know that designing and implementation of
Medicine reminder and dispensing machine would be a advantageous in such a way that
patients are no need to remember the medicines and doses to be taken and also it reduces some
work of nurses. The health workers have PPE still they are getting infected. This is because they
give medicines and different drugs to patients to ease their pain and monitor the effects for drawing
further studies. Currently there isn't any fully functional embedded system in the market that
provides the options to fill the medicine and the reminder (doze) times. So this project is proposed
using embedded systems.

### Objective: 
The objective or the goal of the expected results of the project could be summarized as follows:
 Set the dose and timings by doctor.
 Display the upcoming dose, timings on a LCD display.
 Plays the confirmation alarm tone on a speaker.
 Opens the medicine holding rack and updates the information on the system.

### Proposed methodology:
 Requirements: Project requirements are analyzed and documented.
 System Design: Make a detailed plan on how to accomplish design and project goals.
 Implementation: Implement the project plan and set standards to measure progress.
 Verification: Verify the system by doing test cases and some modifications can be done.
 Maintenance: System can be maintained at regular intervals of time if necessary.

### Proposed block diagram: 
![A4_Synopsis_Medicine reminder and dispensing machine pdf - Adobe Acrobat Pro DC (32-bit)](https://user-images.githubusercontent.com/85961223/160226147-f1f89de3-cba3-429f-83d9-18e41b929de2.jpg)

Figure(a) consists of a hardware unit Arduino Mega 2560, rotary encoder with push button, SG90 micro-servo motor, DS3231 RTC module, MP3 player module and speaker, 16*2 LCD display, LED, IR sensor, micro SD card module and SD card.

### Working:
Figure(b) illustrates flow chart that is when the machine is first booted, the user is asked to set the dose times for all the doses of each day. If two racks are used, up to 28 doses can be stored in a single refill. Each day, 4 doses can be delivered according to the time set. The LCD displays upcoming doses. The rotary encoder is used to set the time for each dose. Servo motors are used to deliver the medicine to rack and clear the rack if the patient misses the dose. The IR sensor is used to detect the time at which the dose is dropped and taken by the patient and the data is stored in SD card in .csv format. Once the dose is delivered, the speaker plays a tone (a custom audio clip which is dubbing of person reminding to take the dose, followed by a ringtone) to alert the patient to take the dose. LED also blinks repeatedly to provide visual output.

![A4_Synopsis_Medicine reminder and dispensing machine pdf - Adobe Acrobat Pro DC (32-bit)](https://user-images.githubusercontent.com/85961223/160226204-bf595b08-d34e-4798-8123-e7003548c6a3.jpg)





