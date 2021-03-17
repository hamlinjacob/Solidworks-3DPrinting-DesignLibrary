# Solidworks 3D Printing Design Library
I was sick of remodeling the same features over and over for common screws and fasteners for 3D printing, so I decided to make a design library of common features used for common fasteners used in 3D Printing. 

##What is a design library and what does this do? 
A design library allows you to add reusable features or parts into your Solidworks part or assembly. This is great if you don’t want to make the same part or feature over and over again.
For our use case in the 3D printing world, we use special geometry for basic shapes to allow us to print parts without interference while assembling. For example, if you print a basic circular through hole on a vertical face, due to the overhang on the top surface, that top surface will droop down and interfere with the fastener. You will either must reem or drill out the access plastic for a fastener to fit properly. If we instead make the circular hole a tear drop hole, we no long have the drooping issue, and our fastener can fit as expected. 

##Installation
Drag and drop the folder structure to
```sh
  C:\ProgramData\SOLIDWORKS\SOLIDWORKS 2020\design library
  ```
Replace the version year with whatever year you are using. 
