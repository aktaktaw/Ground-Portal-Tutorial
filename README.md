# Ground-Portal-Tutorial
A tutorial on how to create a plane ground portal AR with Spark AR without coding

# Overview
Outcome of these tutorial will gonna look like this

![overview-tutorial](https://github.com/aktaktaw/Ground-Portal-Tutorial/blob/main/screenshot-tutorial/overview-tutorial.gif)

# Requirements
- Basic knowledge in **Spark AR**
- Spark AR and Spark AR Player already installed in your computer and smartphone
- USB Cable

# To start the project
- Open Spark AR and choose **Object Reveal Template**
![Spark AR Main Menu](https://github.com/aktaktaw/Ground-Portal-Tutorial/blob/main/screenshot-tutorial/1.JPG)

- Next it'll show a basic template of the project
![Spark AR Project Scene](https://github.com/aktaktaw/Ground-Portal-Tutorial/blob/main/screenshot-tutorial/2.JPG)

- Then delete the unwanted for this object like the higlight in the **Scene Panel** and **Asset Panel**
![Scene Panel to delete](https://github.com/aktaktaw/Ground-Portal-Tutorial/blob/main/screenshot-tutorial/3.JPG)

- Open your Patch Editor to delete the unwanted patch node like shown below:
![5.1]()
![5.2]()
![5.3]()
![5.4]()
![5.5]()
![5.6]()

- Increase the radius of the hole of the portal in SDF Circle patch to 0.9 or any desire of your project
![5.8]()

- Import 3D Model from AR Library and search **Low Poly Mountain Scene** in search pop up from **AR Library Window**. Then click button import
![6]()
![7.1]()

- Once success import the 3D Model, drag and drop the **Low Poly Mountain Scene** into Scene Panel. By default your 3D Model inserted inside Focal Distance at Camera > focal Distance > [Your 3D Object]. Unchild it by simply click and drag your 3D model outside from Camera like show below
![7.2.4]()

- Scale up your3D Hole to 2.5 in **Y-Axis**
![7.2.7]()

- Scale down your 3D model to 0.005 for **X**, **Y** and **Z** in **Properties Panel**
![7.2.7.1]()

- Move your **Low Poly Mountain Scene** to align with **Hole Cylinder** like shown below:
 ![7.2.6]()

# Basically, you're done
To test out your project, connect your phone with USB cable to your computer and click button "Test on Device"

![7.3]()
