# Mirantis-Kubernet-Engine

How to install the Mirantis Kubernet Engine (MKE)
-------------------------------------------------
1. Deploy the VM's in ( On premis, cloud) and with any Linux flavour (Ubuntu, centos and RedHat Linux)

2. Install one bastion/normal server from where you have the password less conne
ctivity setup for all the nodes ( Master and Workers )

3. You can use any automation tool to deploy these VM's like ( ansible or terraform ).


4. Download the lauchpad on bastion/normal server for your relevant OS in cluster ( MAC, Linux and Windows) from the below site or use the attached launchpad.
  -  make the binary executable
  -  chmod +x launchpad
  -  export PATH=$PATH:/home/ubuntu/launchpad
  -  ./launchpad version
  -  ./launchpad register ( Put all your details i.e. name, professional email and company )
  -  ./launchpad init > launchpad.yaml ( use Launchpad to generate a template )

4. Update the lauchpad.yaml as per the requirement to deloy the MKE Cluster.
   for more info and option check https://www.mirantis.com/download/mirantis-cloud-native-platform/mirantis-kubernetes-engine/

5. Run the launchpad 
   - launchpad apply --config launchpad.yaml

6. Access the cluster and additionally you can add into the Mirantis Lens to manage.

7. Finish
