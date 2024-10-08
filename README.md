```mermaid
graph LR
A(policy) --> B(permission) --> C(IAM Group)
C --> D(User)
D --> E(Password)
D --> F(Credential)
B --> G(Role)
G --> H(AWS Resource)
G --> I(Other Account User)


## Cat is cut.
![enter image description here](https://memeprod.ap-south-1.linodeobjects.com/user-template/ad95a415641cee235d6c6b3dd35a19ca.png)
