# animations
Animations using Three.js and WebGL

These are some animations I've been working on to learn three.js.  It's mostly JavaScript.  

I've left some extra code in so you can alter as you like.

I've put the init() and animate() function calls at the bottom instead of at the top like most of the three.js examples.  Why?  Because browsers start executing the code as soon as it's downloaded, and browsers download from top to bottom.  Seems like a waste of time to have init() and animate() at the top trying to execute when the actual functions have yet to be downloaded.  Or, maybe, there's a reason that's done, but I haven't found it yet?

**The order that you add three.js libraries/modules to the index page is important.
**You'll need a server set up for the files to work.  I'm using Node.js.





WORKING EXAMLPES CAN BE FOUND ONLINE AS FOLLOWS:

og7.ejs   =>  https://secure-inlet-7727.herokuapp.com/og7   
                  --- Inspired by =>  http://solutiondesign.com/blog/-/blogs/webgl-and-three-js-creating-a-real-scene

animations2.ejs   =>  https://secure-inlet-7727.herokuapp.com/animations2    
                  --- Inspired by =>  http://threejs.org/examples/#webgl_geometry_colors_blender
                  
animations3.ejs   =>  https://secure-inlet-7727.herokuapp.com/animations3    
                  --- Inspired by =>  http://threejs.org/examples/#webgl_interactive_buffergeometry
                  
animations5.ejs   =>  https://secure-inlet-7727.herokuapp.com/animations5    
                  --- Inspired by =>  http://threejs.org/examples/#webgl_lod
                  
animations6.ejs   =>  https://secure-inlet-7727.herokuapp.com/animations6    
                  --- Inspired by =>  http://threejs.org/examples/#webgl_geometries
				  
animations7.ejs   =>  https://secure-inlet-7727.herokuapp.com/animations7
				  --- Inspired by =>  http://threejs.org/examples/#webgl_points_random
				  
animations8.ejs   =>  https://secure-inlet-7727.herokuapp.com/animations8
				  --- Inspired by all of the above and my interest in astronomy
				  
animations9.ejs   =>  https://secure-inlet-7727.herokuapp.com/animations9
				  --- Inspired by =>  http://threejs.org/examples/#webgl_geometry_extrude_splines

animations10.ejs   =>  https://secure-inlet-7727.herokuapp.com/animations10
				  --- Inspired by =>  http://threejs.org/examples/#webgl_geometry_extrude_splines
