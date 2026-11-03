# Raw Xsens IMU data: squats and Romanian deadlifts

Full-body inertial motion capture (Xsens MVN, 17 sensors, 60 Hz) of healthy adults performing deep squats and Romanian deadlifts, both correctly and with intentional technique errors. The recordings are exported directly from the Xsens software, with no preprocessing, segmentation or labels. They were collected for the ADA study on exercise assessment.

## Participants

- 15 healthy adults (8 male, 7 female) aged 19 to 35, with no acute musculoskeletal injury. All gave written informed consent.
- This repository holds the recordings of subjects 2 to 15 (`subject_2.zip` to `subject_15.zip`).

## Exercises

- Deep squats and Romanian deadlifts (RDL).
- For each exercise, correct executions and intentionally incorrect executions (for example, altered joint mechanics).

## Files

| File | Content |
|---|---|
| `subject_N.zip` | Xsens MVN export of one participant (MVNX). |
| `load_mvnx.m` | MATLAB function that reads an MVNX file into a structure. |
| `main_mvnx.m` | Example: loads a recording and plots the position of a segment. |
| `CITATION.cff` | Citation metadata. |

## Related code

Analysis code and labelled kinematics for the ADA study: [ADA-exercise-assessment](https://github.com/drkarlareyes/ADA-exercise-assessment).

## Citation

If you use these data, please cite:

Reyes Leiva KM, Nikelova P, Cerny M. Anthropometry and diagnostic aware deep learning for exercise assessment. *Frontiers in Medical Technology* 7:1725661 (2026). https://doi.org/10.3389/fmedt.2025.1725661

## Licence

Data: [CC BY 4.0](LICENSE). You may share and adapt them with attribution.

## Contact

Karla Miriam Reyes Leiva, PhD. [Website](https://drkarlareyes.github.io) · ORCID [0000-0002-3269-0830](https://orcid.org/0000-0002-3269-0830)
