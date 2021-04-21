# MCBasic
 Micro Color Basic Games by Jim Gerrie for Greg Dionne's MCBasic

These programs are original programs by me for testing the TRS-80 BASIC compiler "MCBASIC" being developed by Greg Dionne: https://github.com/gregdionne/mcbasic?fbclid=IwAR128xMwCiP_CnpsfA_7xRaYyY_5USt_44tGgdkYA33TmpdomFpNzVV-1_M

These programs can also be used with the Quicktype feature of the VMC10 emulator by James the Animal Tamer.  (Be sure to type NEW before Quicktyping).

Most require the use of the 16K RAM expander.  With the emulator, 
Configure >> Memory... and select these two options:
* RAM Normal (as sold in stores) 
* +16K RAM Expansion (as sold in stores)

If you have a real MC10, you'll need a real MC10 16K RAM expander.

To use one of these programs you will need to compile them using Greg's Basic compiler and then assembled using TASM6801.  That will produce a .c10 virtual cassette file that can be loaded into into the emulator using the standard CLOADM command and then EXEC.  To use on a real MC-10 you would need to convert the .c10 file to a WAV sound file.  Use the C10TOWAV utility (in the Tools directory of VMC10) to make a WAV file.  Such WAV files can be played back to an MC-10 connected to your PC, or it could be played back and recorded by an cassette recorder connected to your PC.
