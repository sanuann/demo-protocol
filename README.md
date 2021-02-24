# Mumble Melody Longitudinal Study on Stuttering

This protocol is used in the context of a longitudinal study targetting the assessement of stuttering severity and how it can potentially improve over weeks using various form of feedback mechanisms.

The protocol uses the concept of activities and sub-activities in order to display tasks inside tasks (i.e. sub-tasks). You will find that *VoiceTask_Schema* calls four other schemas, namely: *Raw*, *Reverb*, *Whisper*, *Harmonize*. These tasks depicts the various feedback modes that the user are asked to select on the companion iOS App. Additionally, the items content presented in the protocol are set dynamically based on the *week#* the participants are at. This allow us to bumble different content into one single protocol.

## Activities (tasks):
* Pre-Testing Questionnaire **5 minute**
    * Goal: collect background informations about the subject.
* Baseline Voice Testing **12 minutes**
    * Goal: Initial assessement of subject (include questions, free-speech, reading).
* Mode Testing (with App) **20 minute**
    * Goal: Weekly assessement of stutter using the companion iOS App (include questions, free-speech, reading).
* Post-Testing Interview **5 minutes**
    * Goal: Leaves space to subject for any comment and feedback about the study & experience.
* Thank You **1 minutes**
    * Goal: Upload the data to our server.


## Technical details

1. This repo uses [ReproSchema](https://github.com/ReproNim/reproschema/),
[ReproSchema-UI](https://github.com/ReproNim/reproschema-ui/).
2. The UI is added as a submodule (`ui`) and changes relative to the UI are stored 
in `ui-changes`.
3. The entire build is carried out by Github actions and deployed via gh-pages.

Test protocol (without submission allowed): ```https://sensein.github.io/MumbleMelody_Long/```

reproschema-library checksum:[070c1768a023420202ace00ba9f6e7ffe2b8dfbf](https://github.com/ReproNim/reproschema-library/tree/070c1768a023420202ace00ba9f6e7ffe2b8dfbf/)
