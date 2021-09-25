# CFn
This repository is created to store my serverless application configuration file.

## Image
![Application Image](https://blog.takudon3.com/wp-content/uploads/2021/02/image-2.png)

***

## Usage

* AWS Console
1. Create Host Zone in Route53
2. Create Certificate for API Gateway(System own region) and Cloudfront(eu-west-1).
3. Launch Serverless Network with creating stack from "serverless-base.yml".

* Your CLI Console
    * Please set up AWS CLI v2 before following procedure.
4. Clone this repository.
```bash
git clone https://github.com/Takudon/Serverless_HelloWorld.git
```
5. On "sam-app" directory, 



***

## Update
0.1     Initialize network configuration and web distribution.
0.2     Add sam-app (sample SAM application).
0.3     Update connectivity of SAM and serverless-base.
