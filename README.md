+ screen https://item.taobao.com/item.htm?id=553347108316
+ micro USB公头
+ 小`自锁开关` 2个 https://item.taobao.com/item.htm?id=547241519321
+ 导线 https://item.taobao.com/item.htm?id=41296905861
+ micro sd 卡
+ 电池 https://item.taobao.com/item.htm?id=561178154858
+ 充电宝主板 J款主板 https://item.taobao.com/item.htm?id=564585695195

# Install

cp boot/* `<boot directory>`

# 制作
+ 购买`screen`，让卖家焊接到`Raspberry Pi Zero W`。
+ `micro sd`写入`Raspbian`，安装驱动（`Install`）。
+ 12(`GPIO 18`)和14(`GND`)间连一个`自锁开关` 用来控制背光。
+ 去掉`电池`的`保护板`，连到`充电宝主板`。
+ `充电宝主板`的USB输出的5V经过`自锁开关`，连到`micro USB公头`。
+ `充电宝主板`的USB输出的GND连到`micro USB公头`。
+ `micro USB公头`插到`Raspberry Pi Zero W`上。
