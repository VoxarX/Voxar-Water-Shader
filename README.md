# Vox's Water Shader

I am a stupid moron and i like to use shadergraph like a baby even though I am actually a real programmer..
This nice comment was said by my friend [AlignedCookie88](https://github.com/AlignedCookie88)  as I am writing this Markdown in college.

# BEFORE WE PROCEED
# THIS SHADER ONLY WORKS ON ORTHOGRAPHIC CAMERA


# How it works:

In orthographic camera there is no z value hence we cannot get the depth directly to add the edge foam. However the gracious Cyan has made a blog teaching how to get dem depth in an orthographic camera 
[Orthographic Depth - Cyan](https://cyangamedev.wordpress.com/2020/03/05/orthographic-depth/) 

So basically what happens is you get the scene depth node and we are going to use the reverse Z sign and we gonna compare both of them and the result from running the scene depth node through the one minus node to get an output from 0 - 1
