# Roland JX8P Synthesizer Patch Collection

This repository contains 15 Roland JX8P synthesizer patch banks, with up to 16 voices per bank, which were collected or created by me between 1985 and 1989.

Please also refer to my [Memory Cartridges for the Roland JX8P](https://github.com/rcl9/Roland-JX8P-Synthesizer-Memory-Cartridges).

Three variations of the patch files are being provided:

- Syx - SysEx - System exclusive binary files which the JX8P will accept through a MIDI connection. SysEx files are provided for each 16-bank RAM/ROM image and also as individual files for each patch. 

- SQS - Midi Quest patch librarian file format.

- Binary - 1:1 binary image captures (in the Roland MC16C memory cartridge format), 16 patches per file, 2k in size. The .ram file extensions are from patch banks of my "RAM cartridge" collection and the .rom file extensions are from patch banks of my "(EP)ROM cartridge" collection.

The SysEx files are basically mirror copies of the JX8P's System Exclusive MIDI binary data streams and can be loaded into any generic patch librarian or into a JX8P VST soft-synth. 

For those people who may not own a JX8P, you can easily use these same patches on the [PG-8P VST synth module](https://sites.google.com/site/mlvst0) written by Martin Luder as SysEx files.  It has been tested and verified against these various patches. After starting PG8X, press the red "LOAD" button on its UI and select one of the .sys files contained in this repo.

Please refer to the explanation below for the patch naming terminology and how to best use the patches.

## Special Naming Conventions

Many of my patches use a special naming convention to specify whether you need to put the JX8P in Unison, Flashing Unison or Flashing Solo ("Mono") modes. These correspond to the 3 buttons located on the JX8P called "Poly", ""Unison" and "Solo/Mono".

- FU/ - Put JX8P into 'Flashing Unison' mode
- U/  - Put JX8P into 'Unison' mode
- FS/ - Put JX8P into 'Flashing Solo' mode
- V/  - Velocity sensitive (others may not be marked as such)

## Some Personal Comments About Specific Patches

- Lao Chimes
  
  - Similar to chimes at start of Paranoimia (Art of Noise)
  - Sounds good sequenced with any music

- Fu/Awesome, Fu/Awesome2
  
  - Play a 3 note chord near the top of the keyboard to get a sequenced effect

- B Flt / MC
  
  - Play B Flat below Middle C, sounds like one of Images in Vogue's sounds

- Racing
  
  - Change decay and sustain of ENV2
  - Change ENV of VCF

- ST Bass
  
  - Change ENV2 attack to 0 to get bitey sound

- Plucky2
  
  - DCO-1 and 2 to 16-feet
  - ENV1 sustain to bring up background

- Argeggio1
  
  - Change tuning of DCO1 to get to different timbres

- Alfpiano1
  
  - Turn on XMOD to get Toy Piano

- Touch/Go
  
  - Change ENV1 attack
  - Hit keys quickly

- Effect2
  
  - Change LFO rate and waveform

- Cellosec1
  
  - Change ENV2 attack and decay for different cellos
  - Turn off chorus

- Wavy2
  
  - Turn on chorus
  - Change LFO rate to suit playing speed

- Armbass3
  
  - Has good range over the keyboard!
  - Turn on chorus to get very bright & good upper end

- FU/St Bass4
  
  - Turn off chorus & try POLY mode high up to get good Violin

- Neatbass2
  
  - Change phasing by varying LFO rate

- FS/Violin1
  
  - Try Flashing solo mode in bass end then do fast attack bass sequence
  - Throw in a bit of portamento to slide notes together
  - Turn off VCF LFO and route Vibrato Aftertouch to do Violin Vibrato

- Ultra1
  
  - Good for deriving other sounds
  - Try changing RES, ENV-2
  - Change timing speed by DCO-2 fine tune
  - Change timbre content with DCO-1 tune

- FU/Double
  
  - Change ENV-2 attack to around 5 for 2 note attack

- Popbass
  
  - Try in Unison mode with Fine tune all the way clockwise

- Simmons
  
  - Put on Flashing Solo mode, then use thumb to tap out this solo: 'h h h H', and hit harder on the last beat

- FU/Sample1
  
  - Play staccato like

- Distortion
  
  - For melody of Axel F with Attack 2 = 0
  - For chords of Van Halen JUMP

- FU/Bass15
  
  - Try VCA dynamics = VCF Dynamics = 1, filter velocity sensitive

- FU/Horror
  
  - Press B in second octave above middle C

- FU/Bass4
  
  - To raise pitch one octave use range 8' on DCO-1

## Effect Notes

- FU/Alias2
  
  - Hit 3 keys near top of keyboard and tune filter to get real metallic biting sound

- Choir2
  
  - Put into brilliant mode and Flashing Unison
  - Turn Aftertouch all the way up, pressure will now affect the voices
  - Press bass keys heavily to get backward sound

- Piano(x)
  
  - Turn on Chorus + Flashing Unison to make them sound better

- Organ1
  
  - Try this preset in Flashing Unison to get the opening StarTrek theme sound

- U/Pierce2
  
  - If Flashing Unison (FU) + brilliance on, press F# below middle C

- U/Richlow1
  
  - If Flashing Unison (FU) mode can make good beat near bottom of the keyboard

# Good Presets with Dynamics Off

- P27 Slapback
- P15 Upritebass
- P16 Synth Bass

## Contents of Each Patch Bank

jx8p-0.rom, Synth1:

```
alfpiano1.syx       arpegegio1.syx      bright.syx          cathedral.syx       cathedral2.syx      cathedral3.syx    
chariots.syx        convert.exe         distortion.syx      f-organ.syx         fu-jx-clav.syx      h organ.syx       
hammond1.syx        hammond2.syx        hammond3.syx        japanese 2.syx      japanese.syx        japanese3.syx     
lao chimes.syx      mays wind2.syx      quiet1.syx          scary.syx           scottish.syx        short-brit.syx    
toy piano.syx       u-synth6.syx        unison 1.syx        unison 2.syx        unison 4.syx        v- oasis.syx      
v-poly 1.syx        v-xylo1.syx         voice4.syx          
```

jx8p-1.rom, Bass lines:

```
armbass1.syx        armbass2.syx        armbass3.syx        bass 2.syx          bass 3.syx          bass 8.syx        
bass14.syx          bass7.syx           brassbass.syx       fs-popbass.syx      fu-bass 4.syx       fu-bass 6.syx     
fu-bass15.syx       fu-bass20.syx       fu-bass4.syx        fu-dirty.syx        fu-holdbas.syx      fu-metal.syx      
fu-powbass.syx      good bass.syx       madonabas2.syx      madonabass.syx      moog bass.syx       neatbass.syx      
neatbass2.syx       poppy s.syx         slidebass.syx       slidebass2.syx      synthbass2.syx      synthybass.syx    
voice12.syx         wablybass.syx       
```

jx8p-2.rom, Brass/string:

```
a-la brass.syx      brass1.syx          brass2.syx          ensemble a.syx      ensemble b.syx      ensemble c.syx    
frenchhorn.syx      fs-ponty.syx        fs-violin1.syx      fu-0rch2.syx        fu-arpeg 2.syx      fu-bass16.syx     
fu-choir 1.syx      fu-choir 2.syx      fu-orchsec.syx      fu-pad 1.syx        fu-soprano.syx      fu-stbass4.syx    
fu-strings.syx      king henry.syx      morebrass.syx       polybrass2.syx      sm-strings.syx      spicehorns.syx    
st bass.syx         st bass2.syx        stab orch.syx       stbass 5.syx        touch pad.syx       trumpet2.syx      
u-great up.syx      u-pierce2.syx       
```

jx8p-3.rom, Synth2:

```
b flt -m c.syx      backward.syx        boingy.syx          f-synth1.syx        fs-60 hz.syx        fu-awesom2.syx    
fu-awesome.syx      fu-harmon2.syx      fu-harmonc.syx      fu-metal2.syx       fu-synth4.syx       fu-ultra2.syx     
groul1.syx          metal bell.syx      midi evil.syx       neathigh.syx        outatune.syx        skippy.syx        
sound 1.syx         squishy.syx         synth2.syx          synth3-f.syx        u-britbras.syx      u-ultra 3.syx     
unison 3.syx        voice14.syx         voice2.syx          voice3.syx          voice4.syx          voice7.syx        
voice8.syx          voice9.syx          
```

jx8p-4.rom, Effects 1:

```
computer.syx        daffy2.syx          do eeee.syx         down up.syx         down-up.syx         effect 1.syx      
effect 2.syx        fu-double.syx       fu-ultra1.syx       fu-ultra4.syx       hitlowest.syx       mixed tone.syx    
mousey.syx          oooowwwwww.syx      singingbug.syx      sound 2.syx         u-space.syx         up-down2.syx      
v-bomber.syx        v-effect3.syx       wavy.syx            wavy2.syx           waydown.syx         weeee.syx         
weird.syx           weird10.syx         weird2.syx          weird3.syx          weird9.syx          wow oww.syx       
woww.syx            you eeee.syx        
```

jx8p-5.rom, Simulations:

```
0ldrhodes.syx       acoustic2.syx       agogobell2.syx      artic wind.syx      bells 2.syx         bells.syx         
big bell.syx        dixiebnjo.syx       elec organ.syx      flutey.syx          fs-carhorn.syx      fs-waves.syx      
futurscape.syx      hall bell.syx       horsetrot.syx       kalimba.syx         pipeorgan2.syx      protopiano.syx    
s-blocks.syx        simmons 2.syx       simmons.syx         siren.syx           softpiano.syx       solarwaves.syx    
spinet.syx          steam eng.syx       steelcups.syx       steeldrum2.syx      steeldrum3.syx      u-storm.syx       
v simmons.syx       water.syx           
```

jx8p-6.rom, Synth3:

```
babytalk.syx        benson axe.syx      chopsticks.syx      click.syx           emer-axe.syx        ensemble 2.syx    
fu-elec 2.syx       fu-horror.syx       fu-lfofade.syx      fu-sample1.syx      fu-wicked.syx       fuzzemboy.syx     
hit me.syx          hollowpluk.syx      jumpsynth.syx       kaplucky.syx        lead 1.syx          lfo decay.syx     
metropolis.syx      mod env1.syx        moodyblues.syx      musicbox 3.syx      noise eee.syx       plucky2.syx       
pw wow.syx          ree row.syx         rubber.syx          sad.syx             simple.syx          touch-go.syx      
u-dist4.syx         voice15.syx         
```

jx8p-7.rom, Effect 2:

```
air raid.syx        b u.syx             back-4th.syx        bugs.syx            cosmic.syx          drugged.syx       
engine.syx          fs-jarre.syx        fu-alias2.syx       fu-fx 1.syx         fu-mix 1.syx        fu-oh my.syx      
fu-quakker.syx      fu-richlow.syx      fu-tapkey3.syx      high tones.syx      jx-phaser.syx       landing.syx       
piercing.syx        pow.syx             racing.syx          radio.syx           s-weird.syx         sweep 1.syx       
tap key.syx         tap key2.syx        u-hit 77.syx        u-hit2 77.syx       u-lowest.syx        uv-bird 1.syx     
very slow.syx       weird p.syx         
```

jx8p-0r.ram, Synth1:

```
big pad.syx         el. organ.syx       el.guitar.syx       elec-grand.syx      f-x - ii.syx        fat blip.syx      
frenchorn2.syx      fu-choir3.syx       fu-choir4.syx       fu-heavy1.syx       fu-s-organ.syx      fu-shadow.syx     
funkclav.syx        grov axe.syx        histrings2.syx      piano7.syx          quick bow.syx       richstrgs.syx     
roland fat.syx      slow bow.syx        smoothorgn.syx      smoothsynt.syx      softlead.syx        solosynth.syx     
sqz-wind.syx        stabbrass2.syx      synthiclav.syx      u-dream.syx         u-flatbras.syx      v-hit high.syx    
violasynth.syx      zawinul 5.syx       
```

jx8p-1r.ram, Bass Lines:

```
fu-1984.syx         fu-bachbas.syx      fu-bassend.syx      funk bass.syx       jaco bass.syx     
madonabas3.syx      v-slime 2.syx       v-slimebas.syx      
```

jx8p-2r.ram, Digital Orchestra:

```
bassviola.syx       brass 1.syx         brass 2.syx         brass 3.syx         celeste.syx         clarinet.syx      
english hr.syx      flute.syx           frenchorns.syx      harp.syx            horn 1.syx          horn 2.syx        
koto-llc.syx        kurzweil 2.syx      kurzweil.syx        oboe.syx            piccolo.syx         pluckstrgs.syx    
snare drum.syx      softbells.syx       steeldrums.syx      strg-bells.syx      stringpad1.syx      stringpad2.syx    
stringpad3.syx      trumpet.syx         tuba.syx            violin.syx          warmstring.syx      waterglass.syx    
woodwinds.syx       woodwinds2.syx      
```

jx8p-3r.ram, Synth2:

```
birdland.syx        echomallet.syx      lead strng.syx      mell0tron.syx       melonchoir.syx    
nutronpluc.syx      oxygene b..syx      pipeorgan3.syx      x77 chorus.syx      
```

jx8p-4r.ram, Effects 1:

```
catsinheet.syx      fs-rush.syx         fu-lowrand.syx      fu-swpchd.syx       introsweep.syx      milapead.syx      
u-touch me.syx      why why.syx         
```

jx8p-6r.ram

```
acoustic2.syx       bass7.syx           bright.syx          cathedral2.syx      frenchhorn.syx      fs-violin1.syx    
fu-bass15.syx       fu-bass16.syx       fu-elec 2.syx       fu-jx-clav.syx      fu-stbass4.syx      fu-tapkey3.syx    
funk bass.syx       hammond2.syx        histrings2.syx      japanese.syx        lao chimes.syx      mays wind2.syx    
nutronpluc.syx      plucky2.syx         polybrass2.syx      slidebass.syx       spinet.syx          stabbrass2.syx    
stringpad3.syx      synth3-f.syx        synthybass.syx      u-great up.syx      unison 2.syx        v-poly 1.syx      
v-slimebas.syx      
```

jx8p-7r.ram, Originals:

```
ac. guitar.syx      bomb.syx            celeste.syx         cowbell.syx         crest ech0.syx      doublebass.syx    
filt.fl0w.syx       glock bell.syx      high bell.syx       hold pedal.syx      hollow pad.syx      invertsync.syx    
laser gun.syx       metal lead.syx      mira.syx            open wide.syx       organ 3.syx         polybrass2.syx    
res lead 2.syx      roto-piano.syx      salamand.syx        steeldrums.syx      strings 3.syx       strings 4.syx     
synth bite.syx      touch 5 th.syx      touch ow.syx        u f o.syx           vidiots.syx         wave--gull.syx    
wet brass.syx       xylophone.syx       
```
