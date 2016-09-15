http://www.kozco.com/tech/soundtests.html

https://github.com/sehe/opus

Opus Tools 0.1.9
https://chocolatey.org/packages/opus-tools/0.1.9

cisco/opus 
https://github.com/cisco/opus

xiph/opus-tools 
https://github.com/xiph/opus-tools


https://github.com/soundcloud/ogg/blob/master/include/ogg/ogg.h


opus_demo -e voip 48000 1 test.wav test_opus_demp.opus
opus_demo -d 48000 2 test.opus test.wav

opusenc input.wav output.opus 
opusenc --bitrate 160 input.wav output.opus 

opusdec --rate 48000 input.opus
opusdec --rate 48000 test_opus_demp.opus

Usage: 

opus_demo [-e] <application> <sampling rate (Hz)> <channels (1/2)>
         <bits per second> [options] <input> <output>
opus_demo -d <sampling rate (Hz)> <channels (1/2)> [options]
         <input> <output>

https://github.com/Junchul-kim/rhino

