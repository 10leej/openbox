Place these files in /~/.config/openbox  

# Keybinding  
META=Super key  
META+W = Close Window  
META+space = showdesktop toggle

META+R = Launcher (dmenu)  
META_T = Terminal (lxterminal)
META+B = Browser (firefox)
META+H = File Manager (thunar)

##Window Tiling  
 +--------+-------+   +---------------+  
 | META+q | ALT+e |   |     META+w    |  
 +-------+-------+    +---------------+  
 | META+z | ALT+c |   |     META+x    |  
 +--------+-------+   +---------------+  
 
 +--------+--------+   +---------------+  
 |        |        |   |               |  
 | META+a | META+d |   |     META+s    |  
 |        |        |   |               |  
 +--------+--------+   +---------------+  
SHIFT+META+s to minimize
I've configures these bindings to my personal preference, changing them is not very hard. Just change:
<keybind key="m-y-k-e-y-s">
to
<keybind key="y-o-u-r-k-e-y-s">
