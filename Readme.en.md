## What's PSD2HTML?

Just as the name says, PSD2HTML is a tool to generate a static html page along with the image resources required from Photoshop PSD file.   

## What's the Difference Between PSD2HTML and PS's Build-in Html Export Functionality?

Photoshop has a build-in html export functionality, but the main problem is that we cann't edit the output html file's text, not to say the font-styles, etc. All The texts are parts of the image file. It's quite inconvenient for web page editors.<br/>
However, PSD2HTML cope with this situation much better. **The images and texts are seperated!** As a matter of fact, if the font been used is listed in PSD2HTML/lib/web-fonts.jsx, then the texts will be seperated, or the texts will be parts of the image file.<br/>

## Usage:
**The PS plugin version can be installed this way:<br/>**
- Copy PSD2HTML directory and PSD2HTML.jsx to (PS installation directory)\Presets\Scripts\ <br/>
- Restart Photoshop<br/>
- Open the psd file you want to process, choose PSD TO HTML menu item in Help menu. And the plugin will do the rest for you. All the Html and image files will be generated. <br/>

**There is also a Node Version Html Generator:<br/>**
- To generate html pages by node server, you should upload the *.txt and *.png files generated by this plugin, and the server will generate the html file and image slices required, pack all the resources up, finally, provide a download link. For more information, see the readme file in server directory.

