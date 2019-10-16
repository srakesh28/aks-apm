#AKS-APM
![ScreenShot](https://github.com/srakesh28/aks-apm/blob/master/aks-apm.png)

Steps:

1. Create our support infrastructure: a VNET with 2 subnets.
2. Deploy an AKS cluster
3. Deploy an internal application to that AKS cluster
4. Deploy API management
5. Deploy our API definition to API management.



Commands:
Create a VNET with 2 subnets

Step 1: terraform init #this will download the Azure provider, only needed the first time you run terraform on this directory
Step 2: terraform plan 
Step 3: terraform apply
