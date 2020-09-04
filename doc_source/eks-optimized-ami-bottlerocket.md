# Amazon EKS optimized Bottlerocket AMIs<a name="eks-optimized-ami-bottlerocket"></a>

The Amazon EKS optimized Bottlerocket AMI is built on top of [Bottlerocket](https://docs.aws.amazon.com/bottlerocket/)\. The AMI is configured to work with Amazon EKS and it includes containerd and  `kubelet` \.

Select a link in the following table to view the latest Amazon EKS optimized Bottlerocket AMI ID for a region and Kubernetes version\. You can also retrieve the IDs with an AWS Systems Manager parameter using different tools\. For more information, see [Retrieving Amazon EKS optimized Bottlerocket AMI IDs](retrieve-ami-id-bottlerocket.md)\.

------
#### [ Kubernetes version 1\.17\.9 ]


| Region | x86 | Arm | 
| --- | --- | --- | 
| US East \(Ohio\) \(us\-east\-2\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/x86_64/latest/image_id/description?region=us-east-2) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/arm64/latest/image_id/description?region=us-east-2) | 
| US East \(N\. Virginia\) \(us\-east\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/x86_64/latest/image_id/description?region=us-east-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/arm64/latest/image_id/description?region=us-east-1) | 
| US West \(Oregon\) \(us\-west\-2\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/x86_64/latest/image_id/description?region=us-west-2) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/arm64/latest/image_id/description?region=us-west-2) | 
| Africa \(Cape Town\) \(af\-south\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/x86_64/latest/image_id/description?region=af-south-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/arm64/latest/image_id/description?region=af-south-1) | 
| Asia Pacific \(Hong Kong\) \(ap\-east\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/x86_64/latest/image_id/description?region=ap-east-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/arm64/latest/image_id/description?region=ap-east-1) | 
| Asia Pacific \(Mumbai\) \(ap\-south\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/x86_64/latest/image_id/description?region=ap-south-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/arm64/latest/image_id/description?region=ap-south-1) | 
| Asia Pacific \(Tokyo\) \(ap\-northeast\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/x86_64/latest/image_id/description?region=ap-northeast-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/arm64/latest/image_id/description?region=ap-northeast-1) | 
| Asia Pacific \(Seoul\) \(ap\-northeast\-2\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/x86_64/latest/image_id/description?region=ap-northeast-2) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/arm64/latest/image_id/description?region=ap-northeast-2) | 
| Asia Pacific \(Singapore\) \(ap\-southeast\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/x86_64/latest/image_id/description?region=ap-southeast-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/arm64/latest/image_id/description?region=ap-southeast-1) | 
| Asia Pacific \(Sydney\) \(ap\-southeast\-2\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/x86_64/latest/image_id/description?region=ap-southeast-2) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/arm64/latest/image_id/description?region=ap-southeast-2) | 
| Canada \(Central\) \(ca\-central\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/x86_64/latest/image_id/description?region=ca-central-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/arm64/latest/image_id/description?region=ca-central-1) | 
| Europe \(Frankfurt\) \(eu\-central\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/x86_64/latest/image_id/description?region=eu-central-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/arm64/latest/image_id/description?region=eu-central-1) | 
| Europe \(Ireland\) \(eu\-west\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/x86_64/latest/image_id/description?region=eu-west-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/arm64/latest/image_id/description?region=eu-west-1) | 
| Europe \(London\) \(eu\-west\-2\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/x86_64/latest/image_id/description?region=eu-west-2) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/arm64/latest/image_id/description?region=eu-west-2) | 
| Europe \(Milan\) \(eu\-south\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/x86_64/latest/image_id/description?region=eu-south-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/arm64/latest/image_id/description?region=eu-south-1) | 
| Europe \(Paris\) \(eu\-west\-3\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/x86_64/latest/image_id/description?region=eu-west-3) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/arm64/latest/image_id/description?region=eu-west-3) | 
| Europe \(Stockholm\) \(eu\-north\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/x86_64/latest/image_id/description?region=eu-north-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/arm64/latest/image_id/description?region=eu-north-1) | 
| Middle East \(Bahrain\) \(me\-south\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/x86_64/latest/image_id/description?region=me-south-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/arm64/latest/image_id/description?region=me-south-1) | 
| South America \(São Paulo\) \(sa\-east\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/x86_64/latest/image_id/description?region=sa-east-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.17/arm64/latest/image_id/description?region=sa-east-1) | 

------
#### [ Kubernetes version 1\.16\.13 ]


| Region | x86 | Arm | 
| --- | --- | --- | 
| US East \(Ohio\) \(us\-east\-2\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/x86_64/latest/image_id/description?region=us-east-2) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/arm64/latest/image_id/description?region=us-east-2) | 
| US East \(N\. Virginia\) \(us\-east\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/x86_64/latest/image_id/description?region=us-east-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/arm64/latest/image_id/description?region=us-east-1) | 
| US West \(Oregon\) \(us\-west\-2\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/x86_64/latest/image_id/description?region=us-west-2) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/arm64/latest/image_id/description?region=us-west-2) | 
| Africa \(Cape Town\) \(af\-south\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/x86_64/latest/image_id/description?region=af-south-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/arm64/latest/image_id/description?region=af-south-1) | 
| Asia Pacific \(Hong Kong\) \(ap\-east\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/x86_64/latest/image_id/description?region=ap-east-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/arm64/latest/image_id/description?region=ap-east-1) | 
| Asia Pacific \(Mumbai\) \(ap\-south\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/x86_64/latest/image_id/description?region=ap-south-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/arm64/latest/image_id/description?region=ap-south-1) | 
| Asia Pacific \(Tokyo\) \(ap\-northeast\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/x86_64/latest/image_id/description?region=ap-northeast-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/arm64/latest/image_id/description?region=ap-northeast-1) | 
| Asia Pacific \(Seoul\) \(ap\-northeast\-2\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/x86_64/latest/image_id/description?region=ap-northeast-2) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/arm64/latest/image_id/description?region=ap-northeast-2) | 
| Asia Pacific \(Singapore\) \(ap\-southeast\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/x86_64/latest/image_id/description?region=ap-southeast-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/arm64/latest/image_id/description?region=ap-southeast-1) | 
| Asia Pacific \(Sydney\) \(ap\-southeast\-2\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/x86_64/latest/image_id/description?region=ap-southeast-2) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/arm64/latest/image_id/description?region=ap-southeast-2) | 
| Canada \(Central\) \(ca\-central\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/x86_64/latest/image_id/description?region=ca-central-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/arm64/latest/image_id/description?region=ca-central-1) | 
| Europe \(Frankfurt\) \(eu\-central\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/x86_64/latest/image_id/description?region=eu-central-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/arm64/latest/image_id/description?region=eu-central-1) | 
| Europe \(Ireland\) \(eu\-west\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/x86_64/latest/image_id/description?region=eu-west-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/arm64/latest/image_id/description?region=eu-west-1) | 
| Europe \(London\) \(eu\-west\-2\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/x86_64/latest/image_id/description?region=eu-west-2) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/arm64/latest/image_id/description?region=eu-west-2) | 
| Europe \(Milan\) \(eu\-south\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/x86_64/latest/image_id/description?region=eu-south-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/arm64/latest/image_id/description?region=eu-south-1) | 
| Europe \(Paris\) \(eu\-west\-3\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/x86_64/latest/image_id/description?region=eu-west-3) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/arm64/latest/image_id/description?region=eu-west-3) | 
| Europe \(Stockholm\) \(eu\-north\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/x86_64/latest/image_id/description?region=eu-north-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/arm64/latest/image_id/description?region=eu-north-1) | 
| Middle East \(Bahrain\) \(me\-south\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/x86_64/latest/image_id/description?region=me-south-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/arm64/latest/image_id/description?region=me-south-1) | 
| South America \(São Paulo\) \(sa\-east\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/x86_64/latest/image_id/description?region=sa-east-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.16/arm64/latest/image_id/description?region=sa-east-1) | 

------
#### [ Kubernetes version 1\.15\.11 ]


| Region | x86 | Arm | 
| --- | --- | --- | 
| US East \(Ohio\) \(us\-east\-2\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/x86_64/latest/image_id/description?region=us-east-2) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/arm64/latest/image_id/description?region=us-east-2) | 
| US East \(N\. Virginia\) \(us\-east\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/x86_64/latest/image_id/description?region=us-east-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/arm64/latest/image_id/description?region=us-east-1) | 
| US West \(Oregon\) \(us\-west\-2\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/x86_64/latest/image_id/description?region=us-west-2) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/arm64/latest/image_id/description?region=us-west-2) | 
| Africa \(Cape Town\) \(af\-south\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/x86_64/latest/image_id/description?region=af-south-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/arm64/latest/image_id/description?region=af-south-1) | 
| Asia Pacific \(Hong Kong\) \(ap\-east\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/x86_64/latest/image_id/description?region=ap-east-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/arm64/latest/image_id/description?region=ap-east-1) | 
| Asia Pacific \(Mumbai\) \(ap\-south\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/x86_64/latest/image_id/description?region=ap-south-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/arm64/latest/image_id/description?region=ap-south-1) | 
| Asia Pacific \(Tokyo\) \(ap\-northeast\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/x86_64/latest/image_id/description?region=ap-northeast-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/arm64/latest/image_id/description?region=ap-northeast-1) | 
| Asia Pacific \(Seoul\) \(ap\-northeast\-2\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/x86_64/latest/image_id/description?region=ap-northeast-2) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/arm64/latest/image_id/description?region=ap-northeast-2) | 
| Asia Pacific \(Singapore\) \(ap\-southeast\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/x86_64/latest/image_id/description?region=ap-southeast-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/arm64/latest/image_id/description?region=ap-southeast-1) | 
| Asia Pacific \(Sydney\) \(ap\-southeast\-2\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/x86_64/latest/image_id/description?region=ap-southeast-2) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/arm64/latest/image_id/description?region=ap-southeast-2) | 
| Canada \(Central\) \(ca\-central\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/x86_64/latest/image_id/description?region=ca-central-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/arm64/latest/image_id/description?region=ca-central-1) | 
| Europe \(Frankfurt\) \(eu\-central\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/x86_64/latest/image_id/description?region=eu-central-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/arm64/latest/image_id/description?region=eu-central-1) | 
| Europe \(Ireland\) \(eu\-west\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/x86_64/latest/image_id/description?region=eu-west-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/arm64/latest/image_id/description?region=eu-west-1) | 
| Europe \(London\) \(eu\-west\-2\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/x86_64/latest/image_id/description?region=eu-west-2) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/arm64/latest/image_id/description?region=eu-west-2) | 
| Europe \(Milan\) \(eu\-south\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/x86_64/latest/image_id/description?region=eu-south-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/arm64/latest/image_id/description?region=eu-south-1) | 
| Europe \(Paris\) \(eu\-west\-3\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/x86_64/latest/image_id/description?region=eu-west-3) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/arm64/latest/image_id/description?region=eu-west-3) | 
| Europe \(Stockholm\) \(eu\-north\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/x86_64/latest/image_id/description?region=eu-north-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/arm64/latest/image_id/description?region=eu-north-1) | 
| Middle East \(Bahrain\) \(me\-south\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/x86_64/latest/image_id/description?region=me-south-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/arm64/latest/image_id/description?region=me-south-1) | 
| South America \(São Paulo\) \(sa\-east\-1\) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/x86_64/latest/image_id/description?region=sa-east-1) | [View AMI ID](https://console.aws.amazon.com/systems-manager/parameters/aws/service/bottlerocket/aws-k8s-1.15/arm64/latest/image_id/description?region=sa-east-1) | 

------