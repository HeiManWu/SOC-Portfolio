# SOC engagement portfolio: Cloudora

<!-- Write this file yourself. It is the first thing a reviewer reads,
     and it has to be in your voice. Prompts to answer: --> 

Worked on 20 triage alerts, giving verdicts to each case correctly, provide real evidence to backup my claims, provide suggestions to resolve the incidents and tune the alerts.

## What this engagement was
<!-- Two or three sentences: the client, the queue, your role. -->

Working for HR software company Cloudora, 4 triages a day, analysing the triage based on real evidence.

## How I worked
<!-- The routine you ran per alert. Reference the seven-part verdict
     structure and how you used the severity matrix. -->
Go through the handover and record the important information. Then read the alert details carefully to understand what evidence I need to investigate in. 
Hypothesise the potential reasons for the alert – both malicious and benign. Then go through several evidence to see which hypothesis is correct.
Provide action suggestions that minimise the harm created with malicious activity.
Suggest alert tuning for false positive alerts that were generated due to high detection sensitivity.

## What I found
<!-- The incidents worth talking about, in one paragraph each. Link the
     verdict files. -->

Guest account got hacked via credential breaching, and attacker maintained access even after password reset.
Attacker attempting to sign-in to employee account with correct credentials but failed MFA.
Unauthorised data transfer to malicious domain, confirmed data breach.

## What I would do differently
<!-- The honest section. Reviewers trust portfolios that contain one. -->
Jot down the important information provided in the handover, including intel – it reduces the time needed to go back and forth from mid-investigation to the handover.
Collect all the information required before writing documentation, making the writing more logical and flow better.


## Contents
- verdicts/: one file per alert, my own words, written during the shift
- handovers.md: my end-of-shift handovers in sequence

All data in this engagement is synthetic (reserved IP ranges, reserved
domains); the verdicts and writing are mine.
