# aws-sagemaker-kernels

In each directory you will find a Docker file for
building a specific Sagemaker Compatible Kernel.

## Build R Notebook Kernel for Sagemaker Studio

In the [r-kernel](r-kernel) example we demonstrate how to
use the Sagemaker Studio Image Build CLI to build and register
a customer Notebook Kernel from within Sagemaker Studio.


## Bespoke Python ML Algorithm

In the [bespoke-model](bespoke-model) example we demonstrate
how to build a custom ML model that can be executed using a
Sagemaker Training Instance. This requires building a container
with the required dependencies, as well as conforming the convention
required for Sagemaker training jobs.

