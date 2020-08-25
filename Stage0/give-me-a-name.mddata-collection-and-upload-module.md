# data-collection-and-upload-module

## Feature

This Module is used to collect sleep data of patients
and collects sleep time of patients.
It is used to upload data to system and present data to doctors.
It is used to treat insomnia.

## Acceptance Criteria

### Scenario: Collect sleep data of patients

  Given The device used to measure sleep data is available with patients
and is compatible with Google Fit or able to upload data to system

  When patient measures data using device

  Then Record sleep time of patient

### Scenario: Upload data to system

  Given System is working and patient measures sleep data using device

  When Sleep time data of patient is available on device

  Then Device uploads data on system after every one hour of working
and data is available in different formats like pdf,charts,etc.
