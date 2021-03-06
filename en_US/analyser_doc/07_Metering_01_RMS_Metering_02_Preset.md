# Preset
A number of presets covering widely and not so widely-used metering standards are provided.

![](include/Presets_RMS.png)

Available <link type="document" target="RMS">RMS</link> metering presets

## Custom
User defined values.

## Default
All-round settings with:

* From -48 to +18 dB range, referenced at -18dB.
* 160ms integration time, 16dB/s release, 1dB peak release and 60 frames peak hold.

## Ref -18dB A/B/C/K
Default settings with pre-equalization following either
normalized ANSI A/B/C or ITU-R BS.1170-2 weighting curves, referenced to -18dB.

## Ref -20dB A/B/C/K
Default settings with pre-equalization following either normalized ANSI A/B/C
or ITU-R BS.1170-2 weighting curves, referenced to -20dB.

## VU meter Standard
Standard
reference vu settings, with 300ms integration, 66/7dB/s release and peak release times, referenced
at 0VU/-4dBu/-18dBFS. The scale is non-linear and covers -20 to +3VU, complying with IEC
60268-17.

## K-System / VU
Linear scale, conforming to Bob Katz's recommendations,
referenced at either -12, -14 or -20dB. 300ms integration, 66.7dB/s release and 12dB/s peak release
times, 180 frames peak hold.

## K-System / Slow
Identical to K-System/VU, except
that integration times are doubled. This reflects Bob Katz's view that Vu-meter timings are
appropriate for speech, but that longer timings are better suited to music.

## DIN 45406
This preset conforms to the standard used many European broadcasters such as
French (PAD) and German (IRT) television. Integration time is 10ms for a 90% signal increase;
fall-back time is 1.7s per 20dB; with a linear scale covering a range from -50 to +5dB, referenced
at -9dBFS. The corresponding standards are DIN 45406, IEC 60268-1, and ARD Pfl.H.3/6.

## Nordic N9
5ms integration time for an 80% increase, fall-back time 1.7s per 20dB,
linear scale covering the range from -40 to +9dB, referenced at -18dBFS, according to IEC 60268-10/1
+ N9 supp.

## BBC Normal
10ms integration time for an 80% increase, fall-back time
2.8s per 24dB, custom scale with graduations spaced apart by 4dB, and 4 stands for the -18dBFS
reference, according to IEC 60268-10/2a.

## BBC Slow
Same as above except for
ballistics, where the integration time is changed to 69.2ms for an 80% increase, and 3.8s per 24dB
fall-back.

## EBU Normal
10ms integration time for an 80% increase, fall-back time
2.8s per 24dB, linear scale covering the range from -12 to +12dB, referenced at -18dBFS, according
to IEC 60268-10/2b.

## EBU Slow
Same as above except for ballistics, where the
integration time is changed to 69.2ms for an 80% increase, and 3.8s per 24dB fall-back.


