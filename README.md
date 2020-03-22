# TCPIP-AUTOSAR-stack-4.3.1

//**************************************** 
//
// ---------- Memory options ----------RAM
//

#define MEM_SIZE                          (6* 1024) memory for application data and created headers
#define MEMP_NUM_UDP_PCB                  4     // NO_OF TCB control block
#define MEMP_NUM_TCP_PCB                  4     // NO_OF TCB control block
#define MEMP_NUM_TCP_SEG                  16    // NO of segments
#define PBUF_POOL_SIZE                    16    // Default 16, NO of the pbufs handed to the stack from the hardware  each one is 512 
                                                //so to get the total size can be used 16*512

 stack should be not less than 3000
 //*****************************************************************************
 
