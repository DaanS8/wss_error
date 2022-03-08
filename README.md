# wss_error
## How to run

install ws: 

`npm i ws`

Run (you might have to install ts-node):

`npx ts-node main.ts`

## Generated certificates

    openssl genrsa -des3 -out myCA.key 2048
    openssl req -x509 -new -nodes -key myCA.key -sha256 -days 1825 -out myCA.pem
    openssl rsa -in myCA.key -text > private.pem
   
