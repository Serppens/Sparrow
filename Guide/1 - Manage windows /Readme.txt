Recommend watching in order, starting with the set theme. I'll leave it in sequence as I don't intend to always repeat all the previous commands

Video example:
https://youtu.be/Wk453MfJNUU?si=RsN_PBkGECRqifo4


"0 - Add the file toInt.HC.Z from this repository to the /Adam directory. Then, go to /Home/MakeHome.HC.Z and the MakeHome in the root folder, for example 'C:/' and include the toInt.HC.Z file exactly as it is in this repository. Then, restart the system."

"1 - If not already done, create a file named config.txt in the root folder and write on the desired line where you want it to store the configuration. If you write the window numbers on line 2 of the file you created, then the system will read it on line." 
// analyzing the code of the HomeSys.HCC.Z file from this repo, you will understand better on line 59."

"2 - The HomeSys file is where the windows are generated, so you will also need to compare the code starting from line 55 of this repository with yours and replace it with the one from the repository."
  Examples from commands in HomeSys:
    user1=User *Generate first window* then in loop it generate as many as you want*
    ACInit("/*;!*/Bible.TXT*"); Here is where it initiates the suggestions window that is located on the right side of the screen
    The command XTalk(user1, "#include once") has if you remove it it will stop asking if you want to take a tour

"3 - After that, simply restart the system, and the number of windows you entered on the line will be displayed."


New command
toInt() - same as stoi

Commands created by Terry to manage windows
WinMax() - Maximize a window
WinVert() - Split a window vertically
WinHorz() - Split a window horizontally"
