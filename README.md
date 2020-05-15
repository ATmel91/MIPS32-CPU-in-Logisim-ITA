# MIPS32-CPU-in-Logisim-ITA

Brief description on the current status of the MIPS CPU (5-15-2020)
*  It can run a rough version of assembly, and with a few work-arounds, such as using differnt compatible instructions in the .asm it should run most programs just fine.
*  TTY display is not working nor are the HEX displays. Need to fix SYSCALL print int / string.
*  Need to figure out how to add a keyboard desperately.
*  SLL and SRL are broken.
*  Still need to add XOR and XORI
*  Something happened to SYSCALL exit, so I need to fix that.

Already working instructions:
*  add,
*  addi, 
*  addiu,
*  and, 
*  andi, 
*  or, 
*  ori, 
*  sub, 
*  slt, 
*  slti,
*  beq, 
*  bne, 
*  bgtz,
*  j.

Instructions yet to be added:
*  addu, 
*  subu, 
*  sb, 
*  lb, 
*  jal,
*  jr, 
*  bltz,
*  blez, 
*  bgezal, 
*  mfhi,
*  mflo,
*  sllv,
*  srlv,
*  lui, 
*  sll,
*  srl, 
*  xor, 
*  xori,
*  syscall (print int, print str, read str, print char, read char).

Things to add / improve / do:                                                                                                                                       
*  More instructions, and syscall functions.                         
*  A TTY display to display UTF-16 Characters.                                                                                                                                                                                                                                                              
*  Get a better grasp on assembly language, and write my first mips program.
*  As a long-term goal, write a version of basic and get it to run, the MIPS CPU.
*  Tidy up the space, clean up the project, and organize ***everything***                                                                                                                      
*  Move the .circ file from Logisim-ITA to Logisim-EVO, so that I can port it to an FPGA of my liking. Maybe an ICE-breaker ICE40UP5K?                              
*  Learn Verilog or VHDL.                                                                                                                                      
*  Making a multicore variant would be so cool, but a superscalar mutli-core MIPS would be even cooler.                                                                                                                         
*  Add IO peripherials, like an RGB display and keyboard input.                                                                                                                                                                                                                
*  Add a PORT for GPIO. Short-term goal: turn a pin on and off, long-term goal: drive a TTY display, and combinational logic.
*  Very ambitious long-term goal: Turing-Complete the project and close it up.

Helpful websites I used to launch project:                                                                                                                                                                                                
*  https://courses.missouristate.edu/KenVollmar/MARS/Help/SyscallHelp.html << SYSCALL command list                                                                          
*  http://www.mrc.uidaho.edu/mrc/people/jff/digital/MIPSir.html << MIPS instruction reference                                                                                            
*  https://asecuritysite.com/coding/asc2?val=0%2C255 << UTF-16 Character list                                                                                                                                                                                                         
*  http://www.pitt.edu/~juy9/142/slides/L7-Single-Cycle-dp.pdf << MIPS architecture overview 1                                                                                                                               
*  https://www.eg.bucknell.edu/~csci320/mips_web/ << MIPS instruction converter to HEX                   
*  https://en.wikibooks.org/wiki/MIPS_Assembly/Instruction_Formats << Instruction formats                                                                                                                                       
*  https://cs233.github.io/mipstips.html << Assembly optimization                                                                                                                                                              
*  http://web.engr.oregonstate.edu/~walkiner/cs271-wi13/slides/02-MIPSArchitecture.pdf << MIPS Architecture overview 2                               
*  http://www.cs.uwm.edu/classes/cs315/Bacon/Lecture/HTML/ch05s03.html << MIPS register list                                     

Here is where you can download Logisim-ITA and Logisim-EVO:
*  http://www.logisim.altervista.org/ << Logisim-ITA                                                                                                       
*  https://sourceforge.net/projects/logisimevolution/ << Logisim-EVO                                                                      

Here is where you can get MARS (MIPS Assembler and Runtime Simulator)
*  http://courses.missouristate.edu/KenVollmar/MARS/ << MARS                                                                                                        
