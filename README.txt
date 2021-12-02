# **Panorama** 
### **Student :** *PATEL Shubhamkumar at M2 IMA*


This program is meant to take as input two images and generate a Panorama as an output.

#### In the file ***report.pdf*** you will have further explanation of how the provided result file was obtained and how to reproduce it.



## **Build the project** :

#### *Generate an executable binary Panorama for your distribution* :

- ***``` mkdir build ```***

- ***``` cd build ```***

- ***``` cmake ../CMakeLists.txt -B . ```***

- ***``` make ```***

- ***``` ./Panorama ```***

Once the binary Panorama generated and launched, two windows will be displayed with two images in each of them.

## **Generating a Panorama** :
### You need to sequentially select atleast 4 points on each images by ***LEFT*** clicking on the points of interest. Once you are satisfied with the pairs of points you can ***RIGHT*** click on any of the two images and get the resulting Panorama displayed on new window.

(PS : *Selected points will appear in **RED** or **GREEN** according to the window which was clicked.*)

#### At the end a file named ***Result.jpg*** will be generated with same Panorama image that was displayed for further analysis of the implementation.
