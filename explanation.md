vars 
  - Holds the variables for docker images,repo url and ports

roles

  role 1
     - attempts to install git and docker id not available

  role 2
      - clones the respository

  role 3 
      - builds up mongo db image and runs it

  role 4 
      - builds up the backend image and runs it

  role 5 
      - builds up client image and runs it

  role 6
      - tries to provision the same server but using terraform.
        this section however wasnt so clear to me as i could not fully grasp the process
    
