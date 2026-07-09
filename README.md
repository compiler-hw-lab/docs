# Practical Course: Compiler and Hardware Co-Design (WS26/27)

This practical course is offered by the [Systems Research Group](https://dse.in.tum.de) at TUM.

## Course Information

- Language: English
- Type: Practical training
- Module: [IN0012, IN2106](https://campus.tum.de/tumonline/wbLv.wbShowLVDetail?pStpSpNr=950951054)
  - *(This course is not offered to IN2397)*
- SWS: 6
- ECTS Credits: 10
- Prerequisites:
  - Practical Course: Systems Programming or equivalent:
    - [Practical Lab: Systems Programming (2023-)](https://github.com/ls1-sys-prog-course/docs)
    - Practical Lab: Advanced Systems Programming in C/Rust (offered in 2021-2023)
      - This course is equivalent to the current "Practical Lab: Systems Programming"
    - An equivalent course at another university.
  - *Please submit your Systems Programming grade to the following form by the end of the matching application period.* If you did an equivalent course at another university, please fill the form and add a link to the course's description so we can check this.
    - [Link to form](https://collab.dvb.bayern/spaces/TUMcsel/pages/2752096784/Practical+course+Compiler+and+Hardware+Co-Design+--+WS26+27)
- TUM Online: You must register for this course in TUM Online before the course starts
- Student note: Compulsory enrollment after two weeks of the matching outcome; students who fail to de-register in this period will be registered for the exam

## Course Details

This course covers compiler and hardware co-design across compilers, accelerators, and FPGAs.
- Compilers: You will build compiler optimizations with MLIR to detect and optimize operations such as matrix multiplications, then offload them to accelerators.
- Drivers: You will implement a driver that communicates with the accelerator.
- Accelerators: Finally, you will synthesize an accelerator that executes the offloaded operations.

## Objectives

- Build practical experience with MLIR and compiler optimizations.
- Understand how compiler passes, device drivers, and accelerator hardware fit together in one system.
- Learn how to move computations from a general-purpose program to dedicated hardware.
- Gain hands-on experience with FPGA-based accelerator development and integration.
- Work with the full co-design flow from analysis and transformation to implementation and testing.

## Meetings

- Preliminary Meeting: Thursday, 09.07.2026 at 15:00. Meeting link: https://bbb.cit.tum.de/rooms/lpf-mwp-oue-zdy/join

## Tasks

Please refer to the respective task repositories (that are released on the published date) for detail.
The tasks and schedule may change. **All deadlines are at 15:00 (CEST).**

| Task         | Published on | Deadline | Points | Slide | Video |
| ------------ | ------------ | -------- | ------ | ----- | ----- |
| MLIR         |              |          |   40   |       |       |
| Drivers      |              |          |   40   |       |       |
| Accelerators |              |          |   40   |       |       |

Note that:
- 100% points lost if private tests detect cheating or we find a solution tries to game the system (modifying test scripts, etc.)
- 50% points lost if normal private tests fail

## Environment

Each task repository provides more information about the runnable environment.

Note that only the test results on CI count toward grading.

## Grades

| From | To  | Grade |
| ---- | --- | ----- |
| 0    | 45  | 5.0   |
| 46   | 52  | 4.7   |
| 53   | 59  | 4.3   |
| 60   | 63  | 4.0   |
| 64   | 68  | 3.7   |
| 69   | 75  | 3.3   |
| 76   | 81  | 3.0   |
| 82   | 88  | 2.7   |
| 89   | 95  | 2.3   |
| 96   | 102 | 2.0   |
| 103  | 108 | 1.7   |
| 109  | 116 | 1.3   |
| 117  | 120 | 1.0   |

## Communication

We will use Zulip for all communication.

- **Zulip:** https://zulip.cit.tum.de
- **Channel:** [`Compiler-HW-Co-Design — General`](https://zulip.cit.tum.de/#narrow/channel/3698-Compiler-HW-Co-Design-.E2.80.94-General)


## Contact

We *strongly* prefer Zulip for all communications. For any further questions/comments, please contact the course organizer(s):

- Martin Fink: firstname `.` lastname `at` cit.tum.de
- Prof. Pramod Bhatotia: firstname `.` lastname `at` cit.tum.de
