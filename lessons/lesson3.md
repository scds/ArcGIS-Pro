---
layout: default
title: Lesson 3 - Coordinate Reference Systems
nav_order: 3
parent: Lessons
---

{: .no_toc}  
# Lesson 3 - Coordinate Reference Systems 

<!-- This lesson will go into further detail about the symbology options for different types of data.

<details markdown="block" class="toc">
  <summary>
    Table of Contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

## Lesson Objectives
- Switch between basemaps in ArcGIS Pro.
- Learn about projections and coordinate systems and how they may affect maps.
- Get to know different symbology options based on different data types - numeric and thematic or categorical.
-->

## Projections and Coordinate Systems

Coordinate reference systems are a way of referencing the location of features on the earth's surface. There are two methods – geographic coordinate systems and projected coordinate 
systems.

### Geographic Coordinate Systems

Geographic coordinate systems express locations as angles from a point. They are made up of a series of *meridians* - lines of longitudes which converge at the poles, and *parallels* - lines of latitudes that run parallel and never meet.

<img src="img/GCS_slide.PNG" alt="Geographic coordinate systems" width="60%" align="center">

### Projected Coordinate Systems

Projected coordinate systems are a method of representing the earth in two dimensions. By projecting a round earth onto a flat surface, you introduce distortion. 
Locations in this case are represented as distances from a reference point. 
The example shown on this slide is the Mercator projection. As shown by the red grid lines, the areas of least distortion are closer to the equator, increasing as you get closer to the poles. 

<img src="img/Projection_slide.PNG" alt="Projected coordinate systems" width="60%" align="center">

### Why is this important?

Depending on which geographic or projected coordinate system you use, you can visually misrepresent your data which may also cause errors in measurement or result in datasets being offset from their locations and one another.

{: .new-title }
> Activity 2                                           
> 
> The following two maps show the provincial and territorial boundaries of Canada using two different projected coordinate systems - Mercator and Lambert Conformal Conic.
>
> Examine the maps and make note of differences between the two.

| Mercator Projection | Lambert Conformal Conic Projection |
|--------------|---------------|
| <img src="img/Canada_Mercator_Map.png" alt="Map of Canada using Mercator projection"> Scale 1:80,000,000| <img src="img/Canada_LCC_Map_Zoom.png" alt="Map of Canada using Lambert Conformal Conic projection"> Scale 1:27,500,000 |

## Symbology

<!-- Include a text version of your topic here. -->

### Thematic / Categorical Data
### Numeric Data

## Summary

<!-- - Remind the student about what they just learned.
- You can also note down any key information to keep in mind. -->

## Additional Resources (optional)
<!--
- Here, you can list some additional resources the student can access to learn more about this lesson. -->
