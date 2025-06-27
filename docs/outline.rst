.. _abm_documentation_outline:

=================================
ABM Documentation Outline
=================================

This document provides a structured outline for the Metro Vancouver Activity-Based Model (ABM) documentation.

.. contents::
   :local:
   :depth: 2

1. Introduction
===============
   - 1.1. Purpose and Scope of the Model
   - 1.2. Overview of the Activity-Based Modeling Approach
   - 1.3. Modeling Area and Geographic Scope
   - 1.4. History and Evolution of the Model

2. Model Theoretical Framework
==============================
   - 2.1. Core Concepts of Activity-Based Models
   - 2.2. Behavioral Assumptions
   - 2.3. Model Structure Overview (Flowchart)
   - 2.4. Key Differences from Trip-Based Models

3. Model Inputs & Data Sources
================================
   - 3.1. Synthetic Population
      - 3.1.1. Population and Household Data (e.g., Census, PUMS)
      - 3.1.2. Population Synthesis Process
   - 3.2. Land Use and Economic Data
      - 3.2.1. Zonal System (e.g., TAZs)
      - 3.2.2. Employment Data
      - 3.2.3. School and University Data
   - 3.3. Transportation System & Networks
      - 3.3.1. Roadway Network
      - 3.3.2. Public Transit Network (Routes, Schedules, Fares)
      - 3.3.3. Active Transportation Network (Bikeways, Walkways)
   - 3.4. Behavioral and Survey Data
      - 3.4.1. Household Travel Surveys
      - 3.4.2. Stated Preference Surveys

4. Core Model Components
========================
   - 4.1. Long-Term Choice Models
      - 4.1.1. Usual Workplace Location Choice
      - 4.1.2. Usual School Location Choice
   - 4.2. Daily Activity and Travel Pattern Models
      - 4.2.1. Daily Activity Pattern Generation (e.g., Mandatory, Maintenance, Discretionary)
      - 4.2.2. Tour Generation and Purpose
   - 4.3. Tour-Level Choice Models
      - 4.3.1. Primary Destination Choice
      - 4.3.2. Time of Day Choice
      - 4.3.3. Mode Choice
   - 4.4. Trip-Level Choice Models (Intra-Tour)
      - 4.4.1. Intermediate Stop Generation
      - 4.4.2. Intermediate Stop Location and Purpose
   - 4.5. Network Assignment
      - 4.5.1. Highway Assignment
      - 4.5.2. Transit Assignment

5. Model Outputs
================
   - 5.1. Key Output Files and Formats
   - 5.2. Trip Tables (By purpose, mode, time of day)
   - 5.3. Network Performance Metrics (VMT, VHT, Congestion)
   - 5.4. Accessibility Measures
   - 5.5. Equity Analysis Outputs

6. Model Calibration and Validation
===================================
   - 6.1. Calibration Strategy and Targets
   - 6.2. Validation Against Observed Data
      - 6.2.1. Screenline Counts
      - 6.2.2. Transit Ridership
      - 6.2.3. Travel Time Comparisons
   - 6.3. Sensitivity and Reasonableness Testing

7. Software and Implementation
==============================
   - 7.1. Modeling Software and Platform (e.g., CT-RAMP, DaySim)
   - 7.2. Hardware Requirements
   - 7.3. Model Run Times
   - 7.4. Directory Structure and Key Scripts

8. Appendices
=============
   - 8.1. Glossary of Terms
   - 8.2. Model Parameters
   - 8.3. References
