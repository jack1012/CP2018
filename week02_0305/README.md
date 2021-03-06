# Week02 Note

PPT Chap01s_matlab [download](https://github.com/jack1012/CP2018/raw/master/week02_0305/Chap01s_matlab.pdf )

# MATLAB Tutorial

## MATLAB	Environment
MATLAB	has	the	following	windows:
- Current Folder — Access your files.
- Command Window — Enter commands at the command line, indicated by the prompt (>>).
- Workspace — Explore data that you create or import from files.

![](https://github.com/jack1012/NA2018Spring/blob/master/0227/desktop.png)


## Learn to code with MATLAB
Question 1 
Compute 1+1/2+1/3+1/4+1/5 ... 1/40

### 1. Using Commands to compute

You can dirctly enter commands at command line
```Matlab
>> 1+1/2+1/3+1/4+1/5+1/6+1/7+1/8+1/9+1/10+1/11+1/12+1/13+1/14+1/15+1/16+1/17+1/18+1/19+1/20+1/21+1/22+1/23+1/24+1/25+1/26+1/27+1/28+1/29+1/30+1/31+1/32+1/33+1/34+1/35+1/36+1/37+1/38+1/39+1/40
```

MATLAB adds variable ans to the workspace and displays the result in the Command Window.
> ans = 4.2785

Note: Some commands 
> `clc` : Clear command window <br>
> `clear`: Clear all data at Workspace <br>
> `...` : Continue a statement to the next line <br> 
> `format long` : Set Command Window output display format. See to [[1]](https://www.mathworks.com/help/matlab/ref/format.html)   <br> 

```Matlab
>> 1+1/2+1/3+1/4+1/5+1/6+1/7+1/8+1/9+1/10 ... 
+1/11+1/12+1/13+1/14+1/15+1/16+1/17+1/18+1/19+1/20 ...
+1/21+1/22+1/23+1/24+1/25+1/26+1/27+1/28+1/29+1/30 ...
+1/31+1/32+1/33+1/34+1/35+1/36+1/37+1/38+1/39+1/40 
```
### 2. Creating and Running Script m-File

1. Click the New Script button on the Home tab.
2. After you create a script, you can add code to the script and save it. 

### Example 1
> Compute 1+1/2+1/3 ... 1/40

See to [test1.m](https://github.com/jack1012/CP2018/blob/master/week02_0305/test1.m)


