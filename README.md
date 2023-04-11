# INT301_hardware-and-operating-system-detail

# display an overview of all the hardware and operating system details

  1: Open the Terminal
  2: Install the necessary software
      sudo apt-get update
      sudo apt-get install lshw neofetch
  3: Display hardware information with lshw
      sudo lshw
      
  This will display a lot of information, including details about the CPU,
  memory, storage devices, network adapters, and more

  4: Display system information with neofetch
      neofetch
  This will display information about the operating system, desktop environment, kernel version, CPU, memory, and more.
  
  5: Save the output to a file
      sudo lshw > hardware_info.txt
      neofetch > system_info.txt
  This will save the output of the lshw command to a file named hardware_info.txt and the output of the neofetch command to a file named system_info.txt.

# live monitoring to show the temperature and current usage of various hardware components.

--------------------------- PSENSOR ----------------------------------------------------------------------
  Psensor is a GUI tool in Ubuntu that allows you to monitor the temperature of your CPU, GPU, and other hardware components. 
  Here are the steps to set up live monitoring with psensor.
                • Install Psensor
                     sudo apt-get install psensor
                • Launch Psensor
                      psensor
                • Configure Psensor
                • Done
