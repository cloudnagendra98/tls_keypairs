After terraform apply we do execute below commands

terraform output
terraform output -raw private_key
terraform output -raw private_key > my.pem

terraform output
terraform output -raw public_key 
terraform output -raw public_key > my.pub 