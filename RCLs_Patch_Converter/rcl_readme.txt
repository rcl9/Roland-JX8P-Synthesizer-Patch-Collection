// JX8P Memory-Image to SysEx File Converter, by Robert Lansdale, Jan 18 2014

// Back in 1986 and 1987 Robert Lansdale purchased a JX8P Synth from Roland and programmed and/or collected 
// a number of 32-patch banks. Using his EPROM programmer + home-brew 8-bank RAM/ROM cartridge, he was able to
// create his own collection of memory-image-based banks. Around 2011 he was able to recover these memory images
// from his old 8" floppy disks. 

// This utility program loads in those 2k JX8P memory images of the external cartridge and turns them into "SysEx"
// files which can be sent back to the JX8P via a normal patch librarian. The 32 patches can be output as a single
// .sys file (+ a MIDI message to write each patch into the JX8P memory), or as 32 separate .sys files (with no
// MIDI message to write the patch into the JX8P memory).

// To download to the JX8P, use the "CJXP" Windows utility program. Turn on "System Exclusive" on the JX8P first.   
// Connect the Windows machine up to the JX8P via the "FastTrack Pro" device.
