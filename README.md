# 🏗️ Overlapping Ellipses – Monte Carlo Simulation
## 📜 Overview
This project estimates the overlapping area of two ellipses using a Monte Carlo simulation with a pseudo-random number generator (PRNG). The simulation randomly generates points within a bounding box and counts the proportion of points that fall within both ellipses to approximate the overlapping area.

## 🎯 Problem Explanation
The goal is to compute the area of intersection between two ellipses using random sampling instead of direct analytical methods. The approach involves:
1. Defining the geometric properties:
- Creating a Point class to represent 2D coordinates.
- Creating an Ellipse class that defines an ellipse using two focal points and its major axis width.
2. Estimating the Overlapping Area:
- Randomly generating a large number of points within a bounding box that encloses both ellipses.
- Counting how many of these points fall within both ellipses.
- Using the ratio of overlapping points to total points to estimate the intersection area.
 
## 📊 Example Output
Ellipse(Point(0,0), Point(0,0), 4) has area 12.566  
Ellipse(Point(1,1), Point(2,2), 4) has area 15.708  
5000 out of 100000 generated points are in both ellipses.  
The overlap of the two has area 7.85.  
