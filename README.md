```
module "aws_route53" {
    source  = "NODAR6/route53/aws"
    type = "NS"
    name = "test.example.com"
}

```