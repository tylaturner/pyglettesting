pyglettesting
=============
import pyglet
from pyglet.gl import *
  
win = pyglet.window.Window()
  
@win.event
def on_draw():
        # Clear buffers
        glClear(GL_COLOR_BUFFER_BIT)
 
        # Draw some stuff
        #command that dictates what type of object to draw
        glBegin(GL_TRIANGLES)

        #for the colour of the current object
        glColor3f(1, 0, 0)
        
        #list of vertices for object
        glVertex2i(50, 50)
        glVertex2i(200, 200)
        glVertex2i(200, 300)

        #for the colour of the current object
        glColor3f(2, 5, 4)
        glVertex2i(100, 100)
        glVertex2i(300, 300)
        glVertex2i(100, 200)

        #for the colour of the current object
        glColor3f(3, 0, 5)

        #list of vertices for object
        glVertex2i(50, 50)
        glVertex2i(100, 100)
        glVertex2i(500, 300)

        #for the colour of the current object
        glColor3f(6, 0, 9)

        #list of vertices for object
        glVertex2i(50, 50)
        glVertex2i(500, 500)
        glVertex2i(500, 300)

        #for the colour of the current object
        glColor3f(3, 0, 5)

        #list of vertices for object
        glVertex2i(50, 50)
        glVertex2i(500, 500)
        glVertex2i(500, 300)

        #for the colour of the current object
        glColor3f(3, 0, 5)
        #list of vertices for object
        glVertex2i(300, 300)
        glVertex2i(100, 100)
        glVertex2i(20, 20)

        #for the colour of the current object
        glColor3f(2, 0, 7)
        #list of vertices for object
        glVertex2i(150, 150)
        glVertex2i(400, 400)
        glVertex2i(400, 300)


        #complete drawing verticies
        glEnd()
  
pyglet.app.run()
 
