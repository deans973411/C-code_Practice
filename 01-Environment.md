# 01-0-Environment  
####  Dean Lin  

I choise Microsoft Visual Studio Code be my main C-code edit IDE. In this chepter, we install IDE step by step

### 0. Why Use IDE
   Tranditional coding way are text editor and IDE（Integrated Development Environment）, IDE is friendly for newbie because of its Design Environment & Integration Debugging Environment, its convenient plugins make easier than text edit debug mode.  
   #### When use text editor?
   The shortcoming on IDE is system occupy, I should change to text edit mode when execution speed unacceotable or you want to explore coding process.  
   On Visual Studio Code, environment usage rate is lower than Visual Studio because VS have advance devlopement tools but VSC not.
   |Software|Visual Studio Code|Visual Studio|
   |:---:|:---|:---|
   |**Company**|Microsoft|Microsoft|
   |**Licence**|Paid|Free|
   |**Positioning**|Inculde product devlopement cycle <br>needing, UML tool, code control, IDE...|Lite code editor|
   |**Process Speed**|Relatively Slow|Lite and Fast|
   |**Suggest User**|Devlopement spend a lot of time|Short-term devlopement|  
     
   MSYS2 Download [Link](https://www.msys2.org/)  
   if you change to text edit, you can try MSYS.
   MSYS is a shell whice build on windows similar Cygwin  
   [Install Link](https://github.com/deans973411/C-code_Practice/blob/main/01-1-MSYS2.md#01-1-msys2)  
### 1. Install Visual Studio Code
   Download [Link](https://code.visualstudio.com/) on Visual Studio code official website  
### 2. Install C-code comiler
   MinGW Download [Link](https://sourceforge.net/projects/mingw/files/)  
   
   MinGW is transplant GCC compiler and GNU Binutils to win32 system, produce project which can be executed on windows 32x 64x.  
     &emsp;(1) Started download on official website and standard install process.  
     &emsp;(2) After installed, choise basic and g++ in the windows, and click upper left installation > Apply Change  
     &emsp;(3) After install package, we should path on system.  
   
   > Right click windows icon > option > system > about > system-info > advance system setting > environment-variable > system-variable > click path > edit... 
    
   Add a new variable inside `path` C:\MinGW\bin : which default path for MinGW. Restart your computer.
### 3. Install C/C++ plugin
   Choise C/C++ basic plugin on VSC, and start coding.
