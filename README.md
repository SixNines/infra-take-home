# infra-take-home

Create a CLI application that can be used to create cloud infrastructure for hosting a simple static web page with nginx on an AWS EC2 server.

    - The application should be hosted on AWS.
    - The static web page should display a single word and this should be set using the CLI command.
    - The nginx server should live on an EC2 instance running ubuntu.
    - The nginx server should be configured in the user data portion of the EC2 instance.
    - The nginx server should run on boot of the instance and start automatically if the server is terminated. 
    - calls to AWS should be made with either terraform or Boto(can use language equivalents)
    - The CLI should have one command 
        - create 
            - This should take a single word that will be displayed on the static web page
            - The command should return the I.P address of the web page after a successful run. 
