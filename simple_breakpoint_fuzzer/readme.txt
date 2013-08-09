A simple proof of concept fuzzer written as a WinDbg script.  Place the wds files in the WinDbg installation directory, download radamsa and place it on the desktop, and place reloader.html on the desktop.  Get a base jpeg file and name it "base.jpg", place it on the desktop as well.  

- Open Internet Explorer
- Open WinDbg
- Attach to IE
- run -> $$>a<fuzzer.wds
- hit 'go'

Assumes the path to the desktop is C:\Users\admin\Desktop
