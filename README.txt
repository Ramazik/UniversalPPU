Release date: August 11, 2014

Contained within is all the information you should need to build and program your very own Universal PPU.

Here are the brief programming instructions:
1. Load the microcontroller with the firmware.  You will need a Pickit or equivalent programmer to do this.
2. Load PaletteMaker.  Write out a palette file.
3. Connect the Universal PPU to your computer via a USB cable.
4. Load UniversalPpuConfig.  Connect to your Universal PPU.
5. Under the FPGA tab, load universalppu.bin (NOT universalppu.bit).  Write the FPGA.
6. Under the Palette tab, load your palette file.  Write it.

And that's it!  Good luck!

Please note that there is no warranty nor any support offered for the contents of this archive.  
Assembling your own Universal PPU is strictly at your own risk.


============================================================================================================
Источник, откуда был взят исходный проект:
https://web.archive.org/web/20140615000000*/http://www.universalppu.com/

Автор проекта впервые опубликовал исходники после заявления о том, что он не будет продолжать проект:
https://web.archive.org/web/20141016193656/http://www.universalppu.com/?p=347
August 11, 2014
Source Release
------------------------------------------------------------------------------------------------------------
Есть важное замечание, но мне не известно на сколько оно актуально к содержанию данного репозитория:
https://web.archive.org/web/20141016193656/http://www.universalppu.com/?p=347

Копия текста:
August 23, 2014
Important note about Universal PPU
This is a note to those wishing to build their own Universal PPU.

Resistors R29, R30, R18, R31, R33, R34, R36, R37, R39, R40, R42, R43, R45, R46, R48, and R49 are shown as 0-ohm resistors in the design.
They are present to either pull the data bus up or down while the FPGA is being initialized.  ONLY ONE OF EACH PAIR SHOULD BE POPULATED.  
It was an experiment I was never able to complete, and I populated none of them on my own Universal PPUs to no ill effect.

IF YOU POPULATE BOTH RESISTORS OF ANY PAIR, YOU ARE SHORTING OUT THE POWER SUPPLY.  DON’T DO THAT.
------------------------------------------------------------------------------------------------------------
В репозиторий добавлен файл UniversalPPU1.zip
Ссылка на файл UniversalPPU1.zip была размещена на форуме:
https://forums.nesdev.org/viewtopic.php?t=17111
Сохранил данную страницу в archive.org в полном виде, т.к. имеющиеся копии были с испорченной разметкой
https://web.archive.org/web/20231012185345/https://forums.nesdev.org/viewtopic.php?t=17111%2A
Прямая ссылка на UniversalPPU1.zip:
https://drive.google.com/uc?export=download&id=1aUYXb2pQuuyaC6Eyj6SBrCL_i7MmsYgZ

Я не сравнивал содержимое репозитория и содержимое файла UniversalPPU1.zip. 
Возможно содержимое одинаковое, возможно есть различия.
------------------------------------------------------------------------------------------------------------
