#What:  
1. import LEGO Dat/Ldr/Mpd into Blender
2. export Blender to LEGO Dat
  
  
#Usage:  
1. download Complete LDraw.org Parts Library( complete.zip) from  
   http://www.ldraw.org/download/get/complete/88.html  
   and decompress it with directory using winzip  
2. edit lego.cfg according to your installation in step 1  
3. enable this addon. then you can access this addon via file->import/export  
  
  
#Bugs:  
during import the ldraw\models\car.dat in Complete LDraw.org Parts Library( complete.zip)  
1. the addon has done 'bpy.ops.mesh.normals_make_consistent()', but when we re-calculate the  
   normals via ctrl+N, the mesh changes  
2. the addon has done 'bpy.ops.mesh.remove_doubles()' twice, but when we do 'remove doubles',  
   16,042 verts are reduced to 14,853 verts  
  
  
#To do:  
since I read "LDraw.org Standards: File Format 1.0.2" on http://www.ldraw.org/article/218.html,  
there are something I don't know now  
1. some line type 1 in MPD. for example,  
Official_LEGO_Models\Star Wars\7140 - X-Wing Fighter.mpd  
in Official_LEGO_Models.zip (http://www.ldraw.org/download/get/official_lego_models/88.html)  
1 16 0 0 0 1 0 0 0 1 0 0 0 1 7140 - Minifig - Luke Skywalker.ldr  
which is not listed in the document. Where can I find the reference?  
2. speed up  
  
  
#Website:  
https://github.com/retsyo/io_scene_legoldraw  
http://blenderartists.org/forum/showthread.php?378632-Addon-new-LEGO-Dat-file-IO&p=2919884#post2919884


