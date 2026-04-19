This is a GUI **specifically** designed to reduce the headache of installing RDP Wrapper on your system, say if its incompatible, or you don't have any of the files, this executable has got you covered.

This program is held on with 2 programs
- RDP Offset Finder (https://github.com/llccd/RDPWrapOffsetFinder)
- RDP Wrapper (https://github.com/stascorp/rdpwrap)
Huge thanks to these 2 people for allowing this program to exist.

This tool does interact with termsrv.dll so the anti-virus does detect it as a threat, the best solution is to put it into a folder that you've marked with an exclusion.
- I've included the source file to proove anything i've added to it isnt mallicious in any way.

How to use
- If you dont have RDP installed at all follow this guide
- Step One: Click **Install RDPWrap** on the top. It'll tell you its in a folder in your downloads, go into that folder and run install.bat and wait.
- Step Two: Click **Run Offset Finder**, this will generate the updated offsets due to RDPWrap being out of date since 2017.
- Step Three: Click **Append to INI**, this will automatically add these offsets to the ini file RDP Wrap uses to allow functionality
- Step Four: Click **Restart RDP Service**, this does exactly what it says it does. If you dont, RDPWrap will not function.

And you're done! RDP Wrap is fully installed.
