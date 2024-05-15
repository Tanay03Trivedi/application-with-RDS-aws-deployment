# deploying application on below architecture

![Screenshot 2024-05-15 174627](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/0eb887ea-a580-4c7c-9745-91fa0a4385cf)

## step-1 VPC creation

![Screenshot 2024-05-15 194406](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/25949ec6-fb7b-48b6-b401-12b8772e0aaf)

## step-2 create security group as below

![Screenshot 2024-05-15 200420](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/8a3c4359-02a5-48f2-9388-bc2502b76011)

## step-3 creating  auto scalling group and deploying instance in private subnets and creating a bastion host on public subnet

![Screenshot 2024-05-15 200010](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/c7cd62f3-02f8-4bae-825d-f90813714c3a)

![Screenshot 2024-05-15 200853](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/fc51a19e-20cf-4b58-847c-ed6b0d6b3f47)

![Screenshot 2024-05-15 201045](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/b76ece90-9bc9-4e8c-8660-e55bd8bb3a70)

![Screenshot 2024-05-15 201147](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/43b3ca82-13f3-4000-b0f6-22e96e904621)

![Screenshot 2024-05-15 201339](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/65e5566f-045c-4c01-a745-2fd57d76cebd)

![Screenshot 2024-05-15 201644](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/e2f25e0a-90ca-444c-9ab3-1ef2be8e51ec)

## install depedences of application on private instances using bastion 

![image](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/a4aadcb9-d873-4537-9e06-f85c252c1409)
### do same on 2nd instance also

## create s3 bucket, RDS and read replica

### s3

![Screenshot 2024-05-15 204241](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/1a76f614-6cec-4f9d-99dd-7920fd0bd2d9)

### RDS

![Screenshot 2024-05-15 204452](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/3e0600d7-554d-42c5-859e-670c227b441b)

![Screenshot 2024-05-15 204459](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/4be33ddc-fd46-4ae8-ae44-ebb4e8aa4dbb)

![Screenshot 2024-05-15 204505](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/27eeffb1-b7d3-4a58-8694-4e80d45558eb)

![Screenshot 2024-05-15 204510](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/4411fc60-2307-4396-b69d-c8ccb3b64064)

![Screenshot 2024-05-15 204521](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/d3444ae9-7439-4f7a-aca4-1716efafd8fd)

### Read replica in diffrent az

![Screenshot 2024-05-15 205517](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/0ca1fbc1-0cdf-4ad4-81f8-07e2a0763efc)

![Screenshot 2024-05-15 205528](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/6f8754e9-251a-472a-86d9-bbcd6d52b147)

![Screenshot 2024-05-15 205535](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/e930a990-f53f-45aa-bfcd-bc4daa9502ca)

## create a IAM role to give instance access of s3 and attch that role to private instances

![image](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/e2f97ef1-55bc-44c0-b9c5-68bbe6840113)

![Screenshot 2024-05-15 210045](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/e9523dae-ed56-4d83-8da0-4da2dde9074a)

## install mysql client and access rds

![Screenshot 2024-05-15 211102](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/32e0db2d-b44e-401a-adbb-6593eb60b0ab)

![image](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/07009844-a5d0-4f1b-9e8b-3d7575c700eb)

## run application on both instances

![Screenshot 2024-05-15 213129](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/86ef8b52-d7f8-4264-9e7d-3a5655fb2dc6)

## Test with Application Loadbalancer

![Screenshot 2024-05-15 215847](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/8597ce5d-e652-4e19-8bc9-17f3b398763e)

![Screenshot 2024-05-15 215801](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/bb8237f0-ae49-44fd-b40c-944211707a96)

![Screenshot 2024-05-15 220051](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/1305db30-e631-45a0-8422-6993bd695a09)

![Screenshot 2024-05-15 220318](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/0d6ac5fa-96e0-4c51-a4d2-7714209fd9e0)

## create cloud front 

![Screenshot 2024-05-15 220554](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/4e4e989a-a695-4959-856e-52db62a53783)

![Screenshot 2024-05-15 220717](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/d4bc565c-aa9f-4f74-ba5c-b8f5455480ac)

![Screenshot 2024-05-15 220724](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/acd72067-fe9a-4a15-b345-a3c3198358c4)

![Screenshot 2024-05-15 220728](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/ad4d2f18-e876-43cb-b68d-049f2e13df77)

![Screenshot 2024-05-15 221349](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/af3c8214-9bd8-4e27-96a6-05a6847b5c24)

![Screenshot 2024-05-15 221328](https://github.com/Tanay03Trivedi/fully-funcation-aws-application-deployment/assets/160705084/32f23799-1f56-4ce0-a44c-054734819a3e)





