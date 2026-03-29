## Unidade 2

- [Manual Deploy Static Site to S3](https://www.youtube.com/watch?v=QkyQ9d0ttpo)
- [Terraform Deploy Static Site to S3](https://www.youtube.com/watch?v=bo0FqGPFRqA)
- [How To Install WSL on Win11](https://www.youtube.com/watch?v=_FoQrSyo7Wc)

## Unidade 3
- [What is Ansible?](https://www.youtube.com/watch?v=-CpED6_3iWM)
- [Manual Deploy EC2, Nginx and Website](https://www.youtube.com/watch?v=uGMwBooncQ4)
- [Terraform Deploy EC2](https://www.youtube.com/watch?v=v7VJc8eQh5E)
- [Ansible On Deployed EC2](https://www.youtube.com/watch?v=fvMjkliqhss)

Policy json
```json
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "PublicReadGetObject",
      "Effect": "Allow",
      "Principal": "*",
      "Action": "s3:GetObject",
      "Resource": "arn:aws:s3:::nome-do-seu-bucket/*"
    }
  ]
}
```
