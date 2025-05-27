# Terraform-modules
------
bevat terraform manifests die vanuit main manifests kunnen worden aangeroepen

Dit kan door in de main.tf de volgende regels op te nemen:

module "provider" {
  source = "git::https://github.com/s1199469/terraform-modules.git//providers.tf
  
 Hiermee wordt de module opgehaald uit de terraform-modules github repository 