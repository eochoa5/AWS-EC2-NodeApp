# AWS-EC2-NodeApp
SSH and SFTP into an EC2 Ubuntu instance on AWS. Deploy a Node App.

Commands used:

SSH:

  ssh -i filename.pem ubuntu@PUBLIC_DNS

  sudo apt-get update 

  sudo apt-get install libssl-dev g++ make

  wget https://nodejs.org/dist/v8.9.1/node-v8.9.1.tar.gz

  tar -xvf node-v0.10.32.tar.gz

  cd node-v0.10.32

  sudo apt-get python

  ./configure && make && sudo make install

  start your node server file 
  npm start &
  
  
  
  SFTP:
  
  WinSCP:
  
  hostname: PUBLIC_DNS
  username:ubuntu
  
  password: advanced ssh auth read private key pem file 
  
  
  
  
    
  


