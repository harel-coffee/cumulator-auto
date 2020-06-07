# Cumulator overview

An API to evaluate the carbon footprint of computation and communcation of machine learning methods (or any other computing system).

## Background
Current researchers produce methods and tools to evaluate and optimize the efficiency (from both time and spatial scales) of large-scale ML computations.

## Aim
Raise awareness about the carbon footprint of machine learning methods and to encourage further optimization and the rationale use of AI-powered tools

## Method
Create Cumulator, a simple API to evaluate the carbon footprint of communication and computation of a machine learning models which provides effortless integration within any python framework.

* Free software: MIT license

# Installation

Use the following command:

    pip install cumulator


# Documentation

At the moment Cumulator has the following functionalities: 

* Chronometer activation and deactivation
* Time aggregation (cumulative time of activation/deactivation) per instance of the cumulator class
* Display of the carbon footprint
Hence, to compare n different network topologies, one can create n cumulator instance and display the relative carbon footprint after computation.

Cumulator was as integrated within the Alg-E platform