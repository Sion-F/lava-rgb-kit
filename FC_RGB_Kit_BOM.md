# Bill of materials
|Item|Reference|Qty|Value|Footptint|Comment|BuyLink|
|-|-|-|-|-|-|-|
|1|C1, C4, C5, C6, C9, C10, C11, C12, C13, C15, C16, C23, C24, C25, C26, C27, C28, C29, C30, C31, C32, C33, C34|23|0.1uF|C0402|无源元件，没有推荐，随便买|-|
|2|C2, C37|2|0.1uF|C0805|-|-|
|3|C3, C7, C8|3|0.2nF|C0402|-|-|
|4|C14|1|27pF|C0402|-|-|
|5|C17, C18, C19, C21, C22|5|220uF|C1206|-|-|
|6|C20|1|47nF|C0402|-|-|
|7|C35|1|0.1uF|C0603|-|-|
|8|C36|1|2.2uF|C0805|-|-|
|9|C38|1|22uF|C0805|-|-|
|10|L1|1|68uH|L0805|-|-|
|11|R1, R5, R6, R7|4|100R|R0402|-|-|
|12|R2, R4|2|680R|R0402|-|-|
|13|R3, R11, R19|3|10k|R0402|-|-|
|14|R8|1|13k|R0402|-|-|
|15|R9|1|16k|R0402|-|-|
|16|R10|1|18k|R0402|-|-|
|17|R12|1|300R|R0402|-|-|
|18|R13, R14, R15, R16, R17, R18|6|75R|R0402|-|-|
|19|R20, R21, R22, R23|4|10k|R0603|-|-|
|20|U1|1|SGM8051|SOT-23-5|挑最便宜的|https://item.taobao.com/item.htm?spm=a1z09.2.0.0.50a72e8dbeVkLV&id=764872569592&_u=9ud9nbf3ef4&skuId=5264000229039|
|30|U2|1|LMV7219|SOT-23-5|优信|https://item.taobao.com/item.htm?spm=a1z09.2.0.0.50a72e8dbeVkLV&id=570329026347&_u=9ud9nbf99a0|
|31|U3|1|BH7240|LQFP48|最便宜的就行。|https://detail.tmall.com/item.htm?id=678406432109&spm=a1z09.2.0.0.50a72e8dbeVkLV&_u=9ud9nbf091d|
|32|U4|1|TLV3502|SOP-8|最便宜的就行。|https://item.taobao.com/item.htm?spm=a1z09.2.0.0.50a72e8dbeVkLV&id=710825969848&_u=9ud9nbf987d|
|33|U5, U8|2|SN74LVC4245APWR|TSSOP24|TI原厂。优信的就可以。|https://item.taobao.com/item.htm?spm=a1z09.2.0.0.50a72e8dbeVkLV&id=581831946773&_u=9ud9nbf4517|
|34|U6|1|LCMXO2-1200HC-4TG100I|TQFP100|我在淘宝随便挑了一个最便宜的，结果发来是拆机片。三片中有一片JTAG可以认到以及烧写，但某个IO对地短路，无法使用。另外两片虽说功能正常，但焊接时都有隐蔽的不良导致图像异常。如果不能从现象倒退原理，就必须用高倍放大镜仔细检查每一个引脚|-|
|35|U7, U9|2|SN74LVC541APW|TSSOP20|TI原厂，优信的就可以。|https://item.taobao.com/item.htm?spm=a1z09.2.0.0.50a72e8dbeVkLV&id=581831962154&_u=9ud9nbfa2df|
|36|U10|1|MCP1703|SOT-89|澳洲套件的作者踩过坑。我买的1块2的，反正没翻车，但已经下架，就不提供链接了|-|
|37|U11|1|RP2C02|PDIP-40-BP|裸针。你要是闲得发慌，可以从圆孔的IC座拆。如果不那么闲，搜索的关键词是PIN针。|https://item.taobao.com/item.htm?spm=a1z09.2.0.0.50a72e8dbeVkLV&id=20005673097&_u=9ud9nbf80ac&skuId=71175630474|

## PPU插座 
PPU的插座使用裸针直接焊接在电路板上。优点是可以省下座子的高度。  
东西长这样  
![img](/img/BarePin.jpg)  
焊接的效果如图  
![image](/img/board.jpg)  

## BOM中未体现的
FC上拆掉PPU后安装的座子，以及Lava Kit板上的排针。许多人喜欢用圆孔IC座+圆孔针，也算一个方案。我更喜欢用塑高7mm的圆孔排母。这种排母可以插普通2.54mm排针，因此你可以买3U镀金的，看起来更亮一些，组合起来的高度恰好足够给CPU也装个圆孔座子。  
(PPU使用裸针省下的高度在这里浪费掉了)  
![img](/img/7mmFemaleHeader.jpg)  