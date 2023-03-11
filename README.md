# self-signed-certificate-without-ca
Shell script to generate self-signed certificates without CA using OpenSSL.

Create separate folder for all certificates

mkdir -p /etc/certs/ && cd /etc/certs/

Provide executable permission to the script
          
chmod u+x gen_certificates.sh
    
Add domain name as a -cn parameter for generation the certificate
          
./gen_certificates.sh -cn *.maggiminutes.com
