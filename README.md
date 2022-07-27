# BinaryNinja-RichPrecense
Posting this as a ""fix"" because the OG one was broken and a pain in the willy to fix.


# How-to
1. press `CTRL + ,` to open settings    
2. search for `Python` and click python in the bar    
3. you should see something for "site-packages folder", select that and put in `C:\Users\<username_edit_this>\AppData\Local\Vector35\BinaryNinja\plugins\python\Lib\site-packages` (they don't accept environment variables in the name, dunno why)    
4. go to command prompt and put in this `%LOCALAPPDATA%\Vector35\BinaryNinja\plugins\python\python.exe -m pip install pypresence`  
5. clone the github repo    
6. open the download in winrar, and extract it to `%APPDATA%\Binary Ninja\plugins`    
7. restart binary ninja and open a project/executable/whatever and it should appear on your status.
