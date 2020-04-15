# MIPS32-CPU-in-Logisim-ITA
I've been working on this project for about 3-4 weeks now. But the idea has been around for months, and I've been playing around and decided to make a MIPS CPU becasause what else is there to do in Coronacation?

It can run a rough version of assembly, and with a few work-arounds it should run most programs with ease. 

Things to add / improve:                                                                                                                                       
*  More instructions, e.g. more syscall functions.                                                                                                                
*  A TTY display with UTF-16 Characters.                                                                                                                               
*  A keyboard input.                                                                                                                                 
*  Write a small program that converts .txt, or .hex, into a Logisim-readable file for the ROM.                                                                    
*  Tidy up the space, and clean up the project.                                                                                                                      
*  Move the .circ file from Logisim-ITA to Logisim-EVO, so that I can port it to an FPGA of my liking. Maybe an ICE-breaker ICE40UP5K?                              
*  Learn Verilog or VHDL.                                                                                                                                      
*  Making a multicore variant would be so cool!                                                                                                                         
*  Add more IO peripherials, like SPI, or I2C.                                                                                                             
*  Add a PORTA or maybe PORTA and PORTB to the MIPS32.circ for GPIO or just "GPO"    

Big websites that have greatly helped my project excell in deleopment speed:                                                                                    
*  https://courses.missouristate.edu/KenVollmar/MARS/Help/SyscallHelp.html SYSCALL command list                                                                          
*  http://www.mrc.uidaho.edu/mrc/people/jff/digital/MIPSir.html MIPS instruction reference                                                                                            
*  https://asecuritysite.com/coding/asc2?val=0%2C255 UTF-16 Character list                                                                                                                                                                                                         
*  http://www.pitt.edu/~juy9/142/slides/L7-Single-Cycle-dp.pdf MIPS architecture overview 1                                                                                                                               
*  https://www.eg.bucknell.edu/~csci320/mips_web/ <<<<<<< Check that website out, it's AWESOME MIPS instruction converter to HEX                                                                          
*  https://en.wikibooks.org/wiki/MIPS_Assembly/Instruction_Formats Instruction formats                                                                                                        
*  https://cs233.github.io/mipstips.html Assembly optimization                                                                                                                                      
*  http://web.engr.oregonstate.edu/~walkiner/cs271-wi13/slides/02-MIPSArchitecture.pdf MIPS Architecture overview 2   
*  http://www.cs.uwm.edu/classes/cs315/Bacon/Lecture/HTML/ch05s03.html MIPS register list

Here is where you can download Logisim-ITA and Logisim-EVO:
*  http://www.logisim.altervista.org/                   <<Logisim-ITA
*  https://sourceforge.net/projects/logisimevolution/   << Logisim-EVO
