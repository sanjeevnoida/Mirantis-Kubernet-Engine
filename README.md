# Mirantis-Kubernet-Engine

How to install the Mirantis Kubernet Engine (MKE)
-------------------------------------------------
1. Deploy the VM's in ( On premis, cloud) and with any Linux falvour (Ubuntu, centos and RedHat Linux)

2. Install one bastion/normal server from where you have the password less conne
ctivity setup for all the nodes ( Master and Workers )

3. You can use any automation tool to deploy these VM's like ( ansible or terrafor ).

4. Create the lauchpad.yaml as per the requirement to deloy the MKE Cluster.

5. Run the launchpad 
   lauchpad apply --config launchpad.yaml

6. Access the cluster and additionally you can add into the Mirantis Lens.
