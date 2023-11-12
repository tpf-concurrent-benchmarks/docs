# Image Processing Pipeline

## Architecture

![robustness](img/ip_robustness.png)

The system is composed by a manager node and a number of format, resolution and size worker nodes.

The work is distributed through messaging, but the files are accessed through a shared file system.

## Specifications

### Processes

- Format: Converts an image into png format.
- Resolution: Resizes an image to a given resolution. The chosen resolution is: [TBD]
- Size: Resizes an image to a given size. The chosen size is: [TBD]

### Data

[TBD](https://akridata.ai/datasets/) dataset will be used for the benchmarks.

## Benchmarks

Benchmarks will be run using [TBD] worker nodes.

- Measurements
  - Worker Throughput
  - Combined Throughput
  - Work-time Variation
  - Memory Usage
  - CPU Usage
  - Completion Time
- Subjective analysis
  - Ease of development
  - External Resources
