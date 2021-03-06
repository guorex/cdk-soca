[![awscdk-jsii-template](https://img.shields.io/badge/built%20with-awscdk--jsii--template-blue)](https://github.com/pahud/awscdk-jsii-template)
[![NPM version](https://badge.fury.io/js/cdk-soca.svg)](https://badge.fury.io/js/cdk-soca)
[![PyPI version](https://badge.fury.io/py/cdk-soca.svg)](https://badge.fury.io/py/cdk-soca)
![Release](https://github.com/pahud/cdk-soca/workflows/Release/badge.svg)

# Welcome to `cdk-soca`

`cdk-soca` is an AWS CDK construct library that allows you to create the [Scale-Out Computing on AWS](https://aws.amazon.com/tw/solutions/implementations/scale-out-computing-on-aws/) with AWS CDK in `TypeScript` or `Python`.


# Sample 

```ts
import * as soca from 'cdk-soca';

// create the CDK application
const app = new App();

// create the stack in the CDK app
const stack = new Stack(app, 'soca-testing-stack');

// create the workload in the CDK stack
new soca.Workload(stack, 'Workload');
```

That's all!



