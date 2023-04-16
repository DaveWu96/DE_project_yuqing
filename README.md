# DE_project_yuqing



# DataEngineering_tutoring_project_home


This repo contains the Spark code and HQL for Data Engineering practices.



### How to use key pair to log into edge node.
1. Generate a key pair:

  * For Linux/Mac: Use the following command in the terminal:

         ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

This command will create a public and private key pair in the default location (~/.ssh/id\_rsa and ~/.ssh/id\_rsa.pub).
  * For Windows: Use a tool like PuTTYgen to generate a key pair. Save the public and private keys (public\_key.pem and private\_key.ppk) to a safe location.
2. In remote server, go to .ssh folder, create a authorized_key file and paste your public key there.
3. Ensure the proper permissions are set on your private key file:

  * For Linux/Mac:


    chmod 600 ~/.ssh/id_rsa
  * For Windows: In PuTTYgen, when you save the private key (private\_key.ppk), the correct permissions are automatically applied.
4. Connect to the edge node using your private key:

  * For Linux/Mac: Use the following command in the terminal, replacing "user" with your username and "edge\_node\_ip" with the IP address or hostname of the edge node:


    ssh -i ~/.ssh/id_rsa user@edge_node_ip
  * For Windows: Open PuTTY and enter the edge node's IP address or hostname in the "Host Name (or IP address)" field. In the left pane, navigate to Connection \> SSH \> Auth, and click the "Browse" button to select your private\_key.ppk file. Click "Open" to initiate the connection.
5. If prompted, accept the edge node's host key by typing "yes" (Linux/Mac) or clicking "Yes" (Windows). You should now be connected to the edge node.