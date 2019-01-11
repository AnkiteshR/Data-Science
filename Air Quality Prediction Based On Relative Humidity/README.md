
#  Air Quality

## Abstract:
Contains the responses of a gas multisensor device deployed on the field in an Italian city. Hourly responses averages are recorded along with gas concentrations references from a certified analyzer.

## Air Quality of an Italian City
(https://archive.ics.uci.edu/ml/datasets/Air+quality)

The dataset contains 9358 instances of hourly averaged responses from an array of 5 metal oxide chemical sensors embedded in an Air Quality Chemical Multisensor Device. The device was located on the field in a significantly polluted area, at road level, within an Italian city. Data were recorded from March 2004 to February 2005 (one year) representing the longest freely available recordings of on field deployed air quality chemical sensor devices responses. Ground Truth hourly averaged concentrations for CO, Non Metanic Hydrocarbons, Benzene, Total Nitrogen Oxides (NOx) and Nitrogen Dioxide (NO2) and were provided by a co-located reference certified analyzer.

## Attributes of the dataset are:
- SNo	Attribute		      Description
- 0		Date		          Date (DD/MM/YYYY)
- 1		Time		          Time (HH.MM.SS)
- 2		CO(GT)		        True hourly averaged concentration CO in mg/m^3 (reference analyzer)
- 3		PT08.S1(CO)		    PT08.S1 (tin oxide) hourly averaged sensor response (nominally CO targeted)
- 4		NMHC(GT)		      True hourly averaged overall Non Metanic HydroCarbons concentration in microg/m^3 (ref. analyzer)
- 5		C6H6(GT)		      True hourly averaged Benzene concentration in microg/m^3 (reference analyzer)
- 6		PT08.S2(NMHC)	    PT08.S2 (titania) hourly averaged sensor response (nominally NMHC targeted)
- 7		NOx(GT)		        True hourly averaged NOx concentration in ppb (reference analyzer)
- 8		PT08.S3(NOx)	    PT08.S3 (tungsten oxide) hourly averaged sensor response (nominally NOx targeted)
- 9		NO2(GT)		        True hourly averaged NO2 concentration in microg/m^3 (reference analyzer)
- 10	PT08.S4(NO2)	    PT08.S4 (tungsten oxide) hourly averaged sensor response (nominally NO2 targeted)
- 11	PT08.S5(O3)		    PT08.S5 (indium oxide) hourly averaged sensor response (nominally O3 targeted)
- 12	T		              Temperature in Â°C
- 13	RH		            Relative Humidity (%)
- 14	AH		            AH Absolute Humidity

## Problem:
Humans are very sensitive to humidity, as the skin relies on the air to get rid of moisture. The process of sweating is your body's attempt to keep cool and maintain its current temperature. If the air is at 100-percent relative humidity, sweat will not evaporate into the air. As a result, we feel much hotter than the actual temperature when the relative humidity is high. If the relative humidity is low, we can feel much cooler than the actual temperature because our sweat evaporates easily, cooling us off. For example, if the air temperature e is 75 degrees Fahrenheit (24 degrees Celsius) and the relative humidity is zero percent, the air temperature feels like 69 degrees Fahrenheit (21 C) to our bodies. If the air temperature is 75 degrees Fahrenheit (24 C) and the relative humidity is 100 percent, we feel like it's 80 degrees (27 C) out.

## Objective:
So we will predict the Relative Humidity of a given point of time based on the all other attributes affecting the change in RH.
