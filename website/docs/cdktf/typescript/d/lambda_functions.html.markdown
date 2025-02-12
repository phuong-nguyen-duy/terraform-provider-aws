---
subcategory: "Lambda"
layout: "aws"
page_title: "AWS: aws_lambda_functions"
description: |-
  Terraform data resource to get a list of Lambda Functions.
---


<!-- Please do not edit this file, it is generated. -->
# aws_lambda_functions

Terraform data resource to get a list of Lambda Functions.

## Example Usage

```typescript
// Code generated by 'cdktf convert' - Please report bugs at https://cdk.tf/bug
import { Construct } from "constructs";
import { TerraformStack } from "cdktf";
/*
 * Provider bindings are generated by running `cdktf get`.
 * See https://cdk.tf/provider-generation for more details.
 */
import { DataAwsLambdaFunctions } from "./.gen/providers/aws/data-aws-lambda-functions";
class MyConvertedCode extends TerraformStack {
  constructor(scope: Construct, name: string) {
    super(scope, name);
    new DataAwsLambdaFunctions(this, "all", {});
  }
}

```

## Argument Reference

The resource does not support any arguments.

## Attributes Reference

In addition to all arguments above, the following attributes are exported:

* `functionNames` - A list of Lambda Function names.
* `functionArns` - A list of Lambda Function ARNs.

<!-- cache-key: cdktf-0.17.1 input-15dd8bea75f34968e0576610967430b8fdd9ec4cdceac038c68467145bb2f9a4 -->