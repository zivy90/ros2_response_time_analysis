# About

This is the companion code for the ECRTS 2019 paper *Response-Time Analysis of ROS 2 Processing
Chains under Reservation-Based Scheduling* (a [preprint](https://t-blass.de/papers/response-time-analysis-of-ros2.pdf) is available). The source code comprises two components

1. A [model validation test](model_validation) that validates our model of the ROS 2 callback scheduling by sending messages to a node and reporting their execution ordering.
2. [case_study](case_study), a prototypical implementation of the proposed response-time analysis, together with a model of the `move_base` stack that is used in the paper's case study.

Please cite the above paper when reporting, reproducing or extending the results.

## Purpose of the project

This project contains the source code for the experiments in the above paper. It can be used to reproduce our results.

Please note that this software is a research prototype, solely developed for and published as
part of the publication cited above. It will neither be
maintained nor monitored in any way.

## Requirements, how to build, test, install, use, etc.

This repository consists of two independent components. Please refer to the README files in the respective subdirectories for instructions.

## License

This work is open-sourced under the BSD-3-Clause license. See the
[LICENSE](LICENSE) file for details.

This work does not include any third-party components.
