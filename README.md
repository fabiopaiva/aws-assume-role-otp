# aws-assume-role-otp

AWS Assume Role OTP allows you to assume a role on AWS at the same time it generates the MFA token.

## Installation

```
pip install aws-assume-role-otp
```

## Usage

```bash
aws-assume-role-otp

```

### First time configuration

The first time you run this tool, it will ask you to inform:

* AWS Access Key ID
* AWS Secret Access Key
* Serial MFA Secret. [How to register device](https://docs.aws.amazon.com/singlesignon/latest/userguide/how-to-register-device.html)
* MFA ARN
* Roles and profiles


## Build locally

```
pip install build
python -m build
pip install dist/aws_assume_role_otp-<Version>-py3-none-any.whl
```
