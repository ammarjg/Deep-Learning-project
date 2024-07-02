# Lane Detection Project: Reproducing and Enhancing CLRerNet

## Overview

This project focuses on reproducing and enhancing the CLReNet architecture for robust lane detection in autonomous vehicles and Advanced Driver Assistance Systems (ADAS). Our work is based on the paper titled "CLRerNet: Improving Confidence of Lane Detection with LaneIoU," and aims to validate and improve upon its findings.

## Team Members

- **Alayna Altunsu** - aleyna.altunsu@bahcesehir.edu.tr
- **Ammar Arifin** - ammar.arifin@bau.edu.tr
- **Tarkan Özşen** - tarkan.ozsen@bahcesehir.edu.tr
- **Mohamed Ben Hassen** - mohamed.benhasen@bahcesehir.edu.tr

## Abstract

We meticulously reproduced the original CLRerNet model within the PyTorch framework and validated it using the CULane dataset, ensuring our baseline results align with the original study. We then explored improvements through backbone network variations and data augmentation techniques, aiming to strike a balance between computational efficiency and accuracy. Our experimental results demonstrate that modified backbones maintain competitive performance while reducing computational overhead, and augmented training data enhances robustness in adverse weather conditions. Our findings reaffirm the robustness of CLRerNet and offer insights into optimizing lane detection systems for real-world driving scenarios, emphasizing the importance of balancing accuracy, efficiency, and robustness.

## Methodology

1. **Reproduction of CLRerNet**:
   - We reproduced the original CLRerNet model using the PyTorch framework.
   - The reproduction was validated using the CULane dataset to ensure our baseline results align with the original study.

2. **Improvements**:
   - We explored different backbone networks and data augmentation techniques.
   - The goal was to find a balance between computational efficiency and detection accuracy.

3. **Evaluation**:
   - Comprehensive evaluation using quantitative metrics (accuracy, precision, recall, F1-score, LaneIoU) and qualitative analysis (visual inspection of predictions).
   - The modified backbones maintained competitive performance with reduced computational overhead.
   - Augmented training data improved robustness in adverse weather conditions.

## Results

Our experimental results demonstrate the robustness of the CLRerNet architecture, and our improvements offer insights into optimizing lane detection systems for real-world driving scenarios. The results emphasize the importance of balancing accuracy, efficiency, and robustness in autonomous vehicle applications.

## Conclusion

This project successfully reproduced and enhanced the CLRerNet architecture, providing valuable insights into improving lane detection systems. The modifications and improvements made to the original model demonstrate the potential for further advancements in this field.

## References

Please refer to our final project report for detailed methodologies, experimental results, and comprehensive analysis.
