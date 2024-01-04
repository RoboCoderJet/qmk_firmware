# thekeeb

Description of the keyboard:

* Keyboard Maintainer: [Robo Coder Jet](https://github.com/RoboCoderJet)
* Hardware Supported: RP2040 Community Edition on Corne-inspired keyboards

Make example for this keyboard (after setting up your build environment):

    make thekeeb:default
    
Make example with Miryoku layout:

    qmk compile -c -j 0 -kb thekeeb -km manna-harbour_miryoku

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Quickly press the pysical reset button twice on the side of the PCB.