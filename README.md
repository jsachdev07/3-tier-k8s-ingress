In the frontend folder, there is a file react-deploy.yaml, I have hardcoded the Ingress IP in it
Ingress IP will be different in your case
Kindly after deploying all frontend/backend/database/Ingress
once you see IP of ingress
please update frontend deployment with correct Ingress IP
kubectl edit deploy frontend
