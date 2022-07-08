# MEC-Sustainability

[DRAFT]

## The Goal
This goal of MEC sustainability is to build ETSI compliant, **3rd Party hosted MEC services** for sustainability transparency. It is the hope of this project that this service can bring additional awareness to the application developer community about the impacts of software, infrastructure, and location of compute can have on the world we live in.

## The MEC Service
The ETSI MEC Sustainability Service (MSS) provides both visibility and actionable insights to edge application developers who would like to participate in the 17 sustainability development goals outlined here: [17 SDGs](https://sdgs.un.org/goals)

## The Service Definition for SDG Visibility

Reference: [ETSI GS MEC 016 V2.1.1 (2019-04](https://www.etsi.org/deliver/etsi_gs/mec/001_099/016/02.01.01_60/gs_mec016v020101p.pdf)

**Example:** Goal 7 - Ensure access to affordable, reliable, sustainable and modern energy for all


|  Attribute name |  Data type |  (MSS) | Description  |
|---|---|---|---|
| >>appName  | String  |  G71_Power_Effecient_Optimization | Name of the MEC application. The length of the value shall not exceed 32 characters.  |
| >>appDescription  | String  |  G7 - 1 Provides real-time data stream for measuring power consumption on MEC platform | Human readable description of the MEC application  |
