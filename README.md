# self-signed-certificate-without-ca
Shell script to generate self-signed certificates without CA using OpenSSL.

Provide executable permission to the script

     mkdir -p /etc/certs/ && cd /etc/certs/

    chmod u+x gen_certificates.sh
    ./gen_certificates.sh -cn *.maggiminutes.com
