# Component Tester OLED 
> For ATMega328 based tester and SSD1306 OLED Driver (128x64px)

#### Forked from [TransistorTester by Markus F.](https://github.com/svn2github/transistortester)
---
## Instructions to compile code
1. GoTo mega328_I2C_OLED and start terminal in folder
2. Make required changes to MakeFile (if no desired changes then move to next step)
3. Type the commands in following order
```
make clean
```
```
make all
```
4. Now connect your component tester to PC via USBasp Programmer
```
make fuses
```

```
make upload
```
5. Enjoy using your component tester 🥳
