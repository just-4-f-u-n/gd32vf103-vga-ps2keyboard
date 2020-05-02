# GD32vf103 vga ps2keyboard Controller
## Foreword
   This is a small project for gd32vf103,an excelent RISC-V microcontroller .However , there are not many projects written by this processor .I decide to share the debugging process and how it works here.This is just a basic demo ,later I'll try to prefect this project and add more features .

## PS2 Keyboard
  PS2 keyboard interface was widely used a few years ago(I'm still using ps2 keyboard and mouse now) and its sequence in time is easy ,so I decide to use it as human-computer interaction.
  ### ps2 interface 
  We only need to use 4of the 6lines to drive the ps2 keyboard they are 
>PS2PIN -> GD32vf103PIN   
4    ->  5v    
3 -> GND   
5(clk)->PA0   
1(data) -> PA3

easy isn't it?

### ps2 sequence in time 
  
# VGA

>VGAPIN -> GD32VF103   
HSYNC ->PB0   
VSYNC -> PB6   
GREEN->PA7
   


# ...........updating..............
this is not the latest version

still working on  support of lua and basic language  maybe a gui for it     
https://blog.csdn.net/Adancurusul/article/details/105764387
my blog about it is here  
   
https://github.com/Adancurusul/some_tiny_interpreters
and this is a basic interpreter 
       
chen.yuheng@nexuslink.cn     


