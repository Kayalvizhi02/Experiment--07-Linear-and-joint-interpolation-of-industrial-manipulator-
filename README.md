# Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-

### Aim :
      To understand linear and joint interpolation of industrial manipulator and develop a program for the same 
      
### Equipment Required: 
      Instrial manipulator , teach pendant and associated program platform 
      
### Theory 
    The following interpolation schemes are available in most of the robot controllers.
1. Joint interpolation
2. Straight line interpolation
3. Circular interpolation
4. Irregular smooth motions (manual lead through programming).
#### Joint interpolation: 
The controller determines how far each joint must move to get from the first point defined in the programme to the next. It then selects the joint that
requires the longest time. This determines the amount of movement for other axes such that all the axes start and stop at the same time. Joint interpolation is the default procedure for many commercial robots.

#### Straight-line interpolation: 
In this interpolation, the robot controller computes the straight-line path between two points and develops the sequence of addressable point along the path for the robot to pass through.

#### Circular interpolation: 
This requires the programmer to define a circle in the
robot’s workspace. This is done by specifying three points that lie along the circle. The controller constructs the circle by selecting a series of points that lie closer to the circle. These movements are actually small straight lines. If the addressable points are dense then the linear approximation becomes very much like circle.


#### Manual lead through Programming: 
When the manipulator wrist is moved by the programmer to teach, the movements consist of combination of smooth motion segments. These segments are sometimes approximately straight lines or curves or back and forth motions. These movements are referred as irregular smooth motions and an interpolation is involved to achieve them.




![Robot-interpolation-PTP-LIN-CIRC](https://user-images.githubusercontent.com/36288975/201615171-d0886aaa-8220-4b0c-8a1d-3d8a5c69c76a.png)

### Figure -01 difference between P-P , joint and linear interpolation 

### Robot movements :
![image](https://user-images.githubusercontent.com/75413726/206203866-700afbef-718e-43a8-bd82-e0c474e552fd.png)
![image](https://user-images.githubusercontent.com/75413726/206203895-bbc5c953-fc21-43dd-805e-d78d753b6d46.png)
![image](https://user-images.githubusercontent.com/75413726/206203948-9db6677c-41fd-474b-ba18-209692350187.png)
![image](https://user-images.githubusercontent.com/75413726/206203991-0a721805-6cb7-4e11-87a4-d7c5d76659eb.png)
![image](https://user-images.githubusercontent.com/75413726/206204078-c31eb0c4-503b-4af2-8964-ca521260e821.png)
![image](https://user-images.githubusercontent.com/75413726/206204111-1ef8ea55-fb83-4fe0-a79b-7e68dcd00f34.png)
![image](https://user-images.githubusercontent.com/75413726/206204155-29f970f7-7569-4d91-9703-3d4c1a19bedc.png)
![image](https://user-images.githubusercontent.com/75413726/206204214-762c54ee-78fb-4621-b2b4-e5d6df04910d.png)

### Output:
![image](https://user-images.githubusercontent.com/75413726/206204280-188f36e0-3c92-49d0-be19-91018120ac78.png)
![image](https://user-images.githubusercontent.com/75413726/206204482-0b24b6da-0046-4c62-a723-59611377cc75.png)

### Results:  

A program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio has been executed successfully.
