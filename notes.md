### Operating System: Software to manage a computer's resources for its users and applications
  * Execute user programs and make soling user problems easier
  * Make the computer sustem convenient to use

### Address Space: Set of rights of a process
  * Memory that the process can access
    * Includes:
      * Code/Data Space
      * Execution Stack
      * Heap
      * OS Address Space

 Modes:
  * Kernal Mode:
    * Execution with full privelages of the hardware
    * Read/Write to any memory, access any I/O device
    * Read/Wtite to any disk sector
    * Send/receive any packet

  * User Mode:
    * Limited privelages
    * Only those granted by the operating system kernal

  * In x86 --  mode stored in `EFLAGS` register
  * In MIPS -- mode stored in the `status` register