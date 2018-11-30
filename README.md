# googleiotcore
#googleiotcore

google-api-python-client==1.6.3
google-auth-httplib2==0.0.2
google-auth==1.0.2
google-cloud==0.27.0

https://cloud.google.com/iot/docs/how-tos/credentials/keys
https://github.com/ARM-software/Cloud-IoT-Core-Kit-Examples/blob/master/CPUTemp/readme.md

sudo python pi_cpu_temp_mqtt.py --project_id=agri-drive-iot --registry_id=Agri-Drive-IoT --device_id=agri-device-1 --private_key_file=rsa_private.pem --algorithm=RS256 --ca_certs=roots.pem --cloud_region=asia-east1
