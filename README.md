# ec2-instance-terraform
ec2 instance terraform

provider "aws" {
  region     = "ap-south-1"
  access_key = "dygyrfhjhhgf"
  secret_key = "sgdghgjhjty"
}
resource "aws_instance" "servers" {
  ami           = data.aws_ami.ubuntu.id (launch instance ami  sube linux id copy)
  instance_type = "t2.micro"
subnet_id = public id copy
security_groups = group id copy
key_name = aws_key_pair.id
  tags = {
    Name = "terraform server"
  }
}

resource "aws_key_pair" "key" {
  key_name   = "sample"
  public_key = "ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQD3F6tyPEFEzV0LX3X8BsXdMsQz1x2cEikKDEY0aIj41qgxMCP/iteneqXSIFZBp5vizPvaoIR3Um9xK7PGoW8giupGn+EPuxIA4cDM4vzOqOkiMPhz5XK0whEjkVzTo4+S0puvDZuwIsdiW9mxhJc7tgBNL0cYlWSYVkz4G/fslNfRPW5mYAM49f4fhtxPb5ok4Q2Lg9dPKVHO/Bgeu5woMc7RY0p1ej6D4CKFE6lymSDJpW0YHX/wqE9+cfEauh7xZcG0q9t2ta6F6fmX0agvpFyZo8aFbXeUBr7osSCJNgvavWbM/06niWrOvYX2xwWdhXmXSrbX8ZbabVohBK41 email@example.com"
}
save 

aws  cli install after cmd open  aws --version (aws cli check)2.60.0

access key id :yuhdjkqnnl 
secret key ;hhejjlyewwjwqo
default region : ap-south-1
default out put format: test , table, json.
go to power shell 
ssh-keygen
cd ./documents/
cd ./new folder/'
ls
terraform init
terraform validate
terraform plan
terraform apply
ec2 instance create : terraform server
key pair pem file create
go to power shell
ssh-keygen.exe-f sample
copy sample sample.pem
cd ..
cd ..
$path = "sample.pem"
icacls.exe $path /reset
icacls.exe $path /GRANT:R "$($env:USERNAME)= (R)"
icacls.exe $path inheritance:r
copleted process




