# CFD Analysis of Turbulent Flow in a 90° Pipe Bend

## Project Overview

This project investigates turbulent flow through a 90° pipe bend using Computational Fluid Dynamics (CFD). The study evaluates the performance of different turbulence models and spatial discretization schemes in predicting the flow field and velocity distribution within the bend.

The simulations consider a pipe bend with a curvature radius seven times the pipe diameter (\(R/D = 7\)) at a Reynolds number of 34,132. Four turbulence models are examined: the standard \(k\text{-}\varepsilon\), \(k\text{-}\omega\), Spalart–Allmaras, and Reynolds Stress Model (RSM). First- and second-order spatial discretization schemes are considered to assess their influence on the numerical predictions.

## Simulation Parameters

* **Geometry:** 90° pipe bend
* **Radius-to-diameter ratio:** \(R/D = 7\)
* **Reynolds number:** \(Re = 34132\)
* **Turbulence models:** Standard \(k\text{-}\varepsilon\), \(k\text{-}\omega\), Spalart–Allmaras, and Reynolds Stress Model (RSM)
* **Spatial discretization:** First-order and second-order schemes
* **Evaluation locations:** 45° and 75° along the bend

## Objectives

* Compare the predictive performance of different turbulence models.
* Investigate the influence of spatial discretization order on CFD results.
* Analyse velocity profiles at different locations along the pipe bend.
* Compare numerical predictions with available experimental measurements.
* Assess the capabilities and limitations of CFD approaches for turbulent internal flows.

## Key Findings

Based on the reported study, the standard \(k\text{-}\varepsilon\) and Spalart–Allmaras models showed better agreement with experimental measurements overall, while the \(k\text{-}\omega\) model demonstrated advantages in predicting near-wall velocity profiles.

## Significance

This project highlights the importance of turbulence-model selection and numerical discretization when simulating turbulent flow in curved pipes. CFD provides a computationally efficient means of investigating complex flow behaviour and can complement experimental studies.
