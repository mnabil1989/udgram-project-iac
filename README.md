# Deploy a high-availability web app using CloudFormation
First we should run 
#sh utils/create-stack.sh iam-stack iam/iam-stack-template.yml iam/iam-parameters.json
 
#sh utils/create.sh infra-stack network/network-stack-template.yml network/network-parameters.json

#sh utils/create-stack.sh bastion/bastion-stack-template.yml bastion/bastion-parameters.json


#sh utils/create-stack.sh s3-stack bucket/udagram-s3.yaml bucket/udagram-s3.json


#aws s3 cp udagram.zip s3://udagram-s3-store/udagram.zip


#sh create.sh web-stack servers.yml servers.json

You can access to the final website using this LoadBalancer [link](http://webse-webap-1jwq89zq2hb3o-1982463860.us-west-2.elb.amazonaws.com/)
