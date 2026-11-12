Converted source files
=====================

Shell:
  chmod +x address_book.sh
  ./address_book.sh

C programs (compile on Linux / WSL with GCC):
  gcc process_control_fork_wait.c -o process_control_fork_wait && ./process_control_fork_wait
  gcc producer_consumer.c -o producer_consumer -pthread && ./producer_consumer
  gcc dining_philosophers.c -o dining_philosophers -pthread && ./dining_philosophers
  gcc bankers_algorithm.c -o bankers_algorithm && ./bankers_algorithm
  gcc fifo_client.c -o fifo_client && gcc fifo_server.c -o fifo_server
  gcc pipes.c -o pipes && ./pipes
  gcc c_look.c -o c_look && ./c_look
  gcc scan.c -o scan && ./scan
  gcc sstf.c -o sstf && ./sstf

FIFO client/server must be run in separate terminals, from the same working directory.
These files preserve the source extracted from the supplied DOCX documents; they have not been reviewed, corrected, or tested.
