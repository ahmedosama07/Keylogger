# Keylogger


Repository for the Udemy Course: "Build an Advanced Keylogger using C++ for Ethical Hacking!" with instructor Ermin Kreponic

This keylogger is written in C++ and can be used on Windows 7,8,10 machines. To compile it in CodeBlocks, be sure to enable C++11 standards and create the WindowsAPI(-mwindows) flag.

This keylogger captures keyboard strokes using system hooks. It writes the keystrokes to a log file hidden in the AppData folder. In addition an email can be sent on a timer with the log file attached.
