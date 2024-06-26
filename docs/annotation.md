<p align="center">
  <img src="../figures/logo.png" height="150">
</p>

<div align="center">
    <b><font size="5">An industry-leading data provider in autonomous driving field</font></b>
    <sup>
      <a href="https://www.bodenai.com/">
        <i><font size="4">Website</font></i>
      </a>
    </sup>
  </div>

# Annotation Guideline

## Parking Slot
* **Corner Points**: The four corner points of the parking slot are defined in the counterclockwise direction, and the starting point (named 1) and the end point (named 4) are in the entry line. The points named 2 and 4 are used to determine the angle of the parking slot. Examples are shown in figure:

<p align="center">
  <img src="../figures/slot1.png" width="350">
  <img src="../figures/slot2.png" width="350">
  <img src="../figures/slot3.png" width="163">
</p>


* **Slot Status**: Whether the parking slot is occupied by something or empty
  * occupied
  * empty
* **Slot Type**: The shape of the parking slot
  * vertical
  * horizontal
  * slant
* **Slot Line Completeness**: Whether the line of the whole parking slot is comlete or in complete in the image. 
  * complete
  * incomplete
* **Corner Type**: The shape of the corner points. Only annotated for the points that form the entrance line
  * T

  <p align="left">
  <img src="../figures/T.png" height="200">
  </p>
  
  * L

  <p align="left">
  <img src="../figures/L.png" height="200">
  </p>
  
  * I
  
  
  <p align="left">
  <img src="../figures/I.png" height="150">
  </p>
  
  * U

  <p align="left">
  <img src="../figures/U.png" height="150">
  </p>
  
  * Other
 
 ## Freespace
  * **Categories**
    * freespace
 
 ## Semantic Segmentation
 * **Categories**
   * wheel_stop
   * drains
   * pedestrian
   * park_lock
   * obstacle
   * lane
   * ego
   * pillar
   * vegetation
   * curb
   * wall
   * slot_line
   * road_sign
   * vehicle
   * speed_bump
 
