# CocoSketch

## Introduction

Sketch-based measurement has emerged as a promising alternative to the traditional sampling-based network measurement approaches due to its high accuracy and resource-efficiency. While there have been significant recent contributions in various designs around sketches for measuring over one particular flow key, there is still non-trivial resource overhead when performing sketches over multiple flow keys. Existing multi-key solutions are sacrificing either resource-efficiency or hardware compatibility, making them impracticable on diverse network platforms.

In this work, we make a significant step in multi-key measurement by supporting arbitrary partial key queries. We present the design and implementation of CocoSketch, a sketch-based framework that achieves high resource-accuracy tradeoffs over supported arbitrary partial keys while staying as performant as a single-key sketch. We implement CocoSketch on four popular software and hardware platforms (CPU, Open vSwitch, P4, and FPGA) and evaluate the performance. We demonstrate that the CocoSketch can improve the packet processing throughput by 29.8× with 9.3× better accuracy when measuring six flow keys.

## About this repo

- `CPU`: CocoSketch and other algorithms implemented on CPU
- `OVS`: CocoSketch sketch implemented on OVS
- `FPGA`: CocoSketch sketch implemented on FPGA
- `P4`: CocoSketch sketch implemented on P4
- more details can be found above four folders.

