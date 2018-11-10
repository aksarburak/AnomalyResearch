## AnomalyResearch

# Memory Bandwidth 

* Trying to find out a way for using non-temporal instructions in x86 architecture
  * These instructions don't follow the regular cache-coherency rules
  * The data will not be used soon, has to be written by this instruction so we can do effective caching for the data will be used after.
  * It is directly written to memory, no cache line is read and modified. 
  * How to use MOVNTQ instruction
    * https://www.felixcloutier.com/x86/MOVNTQ.html
    * https://x86.puri.sm/html/file_module_x86_id_198.html
  * 
