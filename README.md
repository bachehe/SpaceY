# SpaceY
2D game converted into 3D

In order to swap perspective ->

Line 270 in main.py

    def transform(self, x, y):
       #return self.transform_2D(x,y)
       return self.transform_perspective(x, y)
     
Change comment from return to another
:3
