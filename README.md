# Crane-TicTacToe
Crane-controlled Tic-Tac-Toe.
Link to WebGL Gameplay: https://icmabad.github.io/cranetictactoe/

## Objective
As the last project in our learning process, we will combine everything we have learned and build a (hopefully) useful application. Here are the requirements:

 
## Approaches:
We will work in groups of two, max group size is 3. No one person can work on this alone.

You are free to design propose anything, however, your application must include the following technical features:

1.       A purpose: you want to be able to describe the purpose of your application precisely in a short paragraph (e.g., 5 sentences). This requirement is to ensure you do not propose an overly complex system. Your description and the actual app you build should correspond.

a.        Friendly layout and UI that makes sense

 

2.       Work with graphical objects:

a.        SceneNode hierarchy, of at least three generations

b.       Direct manipulation of SceneNode objects (manipulation NOT through GUI, rather select and manipulate SceneNode directly, as what we have done in MP5)

                                                               i.      You only need to support the direction manipulating rotation for second or third generation node.

c.        This hierarchy must be build based on our SceneNode/NodePrimitive classes

d.       NOTE: Watch out for SceneNode Hierarchy culling problem (Camera thinks the primitives are all located at the origin and ended up not displaying anything!!)

                                                               i.      Work around this problem by defining Unity GameObjects surrounding your hierarchy

 

3.       Object interaction:

a.        Two other objects: in addition to the SceneNode hierarchy object, your world must include at least two other objects

b.       The leave of your SceneNode hierarchy must interact with these two objects in some meaningful manner (e.g., finger on a moving arm collide with the object and create effect, or, the finger can attract or push the objects)

                                                               i.      This requirement is for you to demonstrate your system is capable of keeping track of and interact with the hierarchy

 

4.       Illumination and texture: the shader you used for the hierarchy should support simple diffuse illumination and display a friendly texture

 

5.       Two Different Views and Camera manipulation

a.        At least two viewports

b.       User must be able to manipulate the cameras in meaningful manner

6.       For grad students (undergrad extra credits)

a.        You have completed with your technology investigation. Now, generalize your results into a meaningful interactive graphical application that includes the above functionality.

b.       For demo purposes, you should have a solution of recording your application and playing the recording in class.

                                                               i.      If you want to, and if you practice, you can perform your demo live during our presentations. But, watch the time limit!

c.        WATCH OUT!! You only have two weeks for this final project. You CANNOT afford to wait till after MP5 is due before you begin.

d.       Undergrad:

                                                               i.      You will receive automatic 20-point extra credit if you work on AR/VR devices, or, if you work with a networked application.
