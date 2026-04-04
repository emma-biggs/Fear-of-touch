---
icon: book-open-lines
---

# Experiment Manual

## 1. Hardware & Physical Configuration

### 1.1 Tactile Stimulation (CS)

* Device: Modified Metec AG refreshable braille device (30 Hz pattern).
* Placement: Modules positioned under the fingertips of the index (D2) and little fingers (D5) of both hands.
* Instruction: Participants must maintain constant finger-to-sensor contact to prevent signal noise and configural uncertainty.<br>

### 1.2. Aversive Stimulation (US)

* Device: Digitimer DS7A Constant Current Stimulator.
* Parameters: 2-ms electrocutaneous pulses.
* Placement: 8-mm Ag/AgCl electrodes on the left and right wrists.\
  <br>

### 1.3. Multi-Modal Measurement (Outcome Measures)

<table data-header-hidden><thead><tr><th valign="top">Measure</th><th valign="top">Electrode</th><th valign="top">Placement</th><th valign="top">Technical Specs</th></tr></thead><tbody><tr><td valign="top">Skin Conductance (SCR)</td><td valign="top">8-mm Ag/AgCl</td><td valign="top">Left palm (hypothenar eminence)</td><td valign="top">0.5 V constant current</td></tr><tr><td valign="top">Eyeblink Startle (EMG)</td><td valign="top">4-mm Ag/AgCl</td><td valign="top">Orbicularis oculi (under left eye)</td><td valign="top">100 dB white noise probes</td></tr><tr><td valign="top">Heart Rate (ECG)</td><td valign="top">8-mm Ag/AgCl</td><td valign="top">Clavicles and right ribs</td><td valign="top">150 Hz low pass filter</td></tr></tbody></table>

## 2. Standard Operating Procedures (SOP)

### 2.1. Preparation Phase

{% stepper %}
{% step %}
### Screening

Verify exclusion criteria (e.g., pregnancy, electronic implants, chronic pain history).
{% endstep %}

{% step %}
### Measurement Preparation

Scrub and dry the skin under the left eye and forehead to ensure low impedance for EMG.
{% endstep %}

{% step %}
### Sensor Attachment

Apply electrodes using K-Y gel for SCR/Shocks and Microlyte/Electrolyte gel for EMG.
{% endstep %}

{% step %}
### Device Check

Ensure braille cells are active and the NIDAQ Affect software is loaded with the correct experiment script.
{% endstep %}
{% endstepper %}



### 2.2. Calibration: The "Subjective 8" Protocol

To model high-stakes pain, the US must be calibrated to a level that is "painful and demanding effort to tolerate".



* [ ] Deliver pulses in an ascending stepwise procedure.
* [ ] Participant provides verbal ratings (0–10 scale).
* [ ] **Target:** Aim for a subjective rating of 8.
* [ ] **Rigor Note:** If left and right wrist physical intensities (mA) differ, use the mean value to maintain balance.<br>

<br>

## 3. Scripted Participant Instructions (English Translation)



**Welcome & Consent:**

> "Thank you for participating. In this session, you will experience two types of unpleasant stimuli: loud tones and mild electrical pulses. The tones are harmless but may startle you. You have total control over the intensity of the electrical pulses; I will never exceed the level you set during calibration".



**On Calibration:**

> "It is vital for our research that the sensation is unpleasant and slightly painful—what we call an '8 out of 10.' Please make an effort to find a level that is challenging but tolerable".<br>

\
**During the Task:**

> "Please sit as still as possible. It is critical that your fingers remain in contact with the tactile modules at all times. You will use the foot pedals to provide ratings so your hands do not have to move".





## 4. The Experimenter’s Checklist

### 4.1. Pre-Experiment Checklist

* [ ] Coulbourn System: Power on; verify NI channels (8, 3, 1).
* [ ] Tactile Modules: Braille cells connected and vibrating on command.
* [ ] Audio: Headphones connected; startle probe volume verified.
* [ ] Safety: Shocker set to "Safety" mode until calibration begins.

### 4.2. Post-Experiment Checklist

* [ ] Deactivation: Return shockers to safety; unplug braille cells.
* [ ] Data Check: Confirm all logs (self-reports, SCR, EMG) saved to the project directory.
* [ ] Debrief: Provide the participant with the debriefing sheet and payment slip.

<br>
