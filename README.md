# Objective-C Retain Cycle Bug

This repository demonstrates a common memory management issue in Objective-C: a retain cycle caused by improper delegate handling.  The `ViewController.m` file shows the buggy implementation, leading to a memory leak.  The corrected version, `ViewControllerFixed.m`, illustrates how to use `weak` references to prevent the cycle.