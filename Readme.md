# The Future of Computing

Infrastructure as code, also referred to as IaC, is an IT practice that codifies and manages underlying IT infrastructure as software. The purpose of infrastructure as code is to enable developers or operations teams to automatically manage, monitor and provision resources, rather than manually configure discrete hardware devices and operating systems. Infrastructure as code is sometimes referred to as programmable or software-defined infrastructure.

## Class Notes: -

On server side there are two types of programes to be run one is distributed system (cloud computing) and the other one is Decentralized systems (blockchains).

[Comparison – Centralized, Decentralized and Distributed Systems](https://www.geeksforgeeks.org/comparison-centralized-decentralized-and-distributed-systems/)

- Centralized system

  - Multiple nodes (clients) are connected to single central node(server). These are vertically scaleable and can go down in case of high traffic. We can't scale these systems on ad hoc basis. These systems are easy to secure, have smooth personal experience, dedicated resources, can be updated quickly and ability to detach a node easily.

- Decentralized

  - Each node makes its own decission and final decission is based on aggregate of all the nodes. No signle node where we can send a request and recieve a response. These systems lack global clock, there are multiple central units and dependant failure of components. Vertical scaling is possible with peer-to-peer architecture. There can be problem of coordination at the enterprise level and not suitable for small systems and no way for regulizing a node. With this system it is difficult to achieve global big tasks, no regulatory oversight, difficult to know which node failed or responded.

- Distributed
  - All nodes are connected and final result is collective effort of all the nodes. When a request is made response is genrated by multiple nodes. Sames goes with serverless systems. Both scalings can be done here. In this system difficult to design and debug algorithms for the system. no common clock causes difficulty in the temporal ordering of events/transactions and difficult for a node to get the global view of the system and hence take informed decisions based on the state of other nodes in the system. Low latency than centralized system, difficult to achieve consensus and conventional way of logging events by absolute time they occur is not possible here

[Blockchain vs Cloud Computing](https://www.upgrad.com/blog/blockchain-vs-cloud-computing/) -

- Cloud is cyberspace where we can access data online while blockchain is encrypted system which stores data in protected data base. Data in blockchain is im-muteable and muteable for cloud. Blockchain is a ledger to keep the records while cloud provide services such as Saas, IaaS and PaaS. Both blockchain and cloud computing are playing a vital role in changing enterprises’ work environments and the way traditional computing works.

[What is cloud computing?](https://www.zdnet.com/article/what-is-cloud-computing-everything-you-need-to-know-about-the-cloud/)

- In cloud computing we utalize remote servers and can have three type of services (IaaS, PaaS and SaaS). It has a 20% increase every year.

[What is Serverless Computing](https://www.onelogin.com/learn/serverless-computings)

- With current methods of development developer writes the code and with help of ops team infrastructure plan is prepared and servers are purchased wuth risk of breakdown due to high usage and new servers requirement this cycle goes on. With serverless computing we develop the code in all the rest is upto the cloud provider. Serverless is infinte scaleable, no charges if no usage but these systems are difficult to develop as we need to define event driven architecture.

[Promising trends in the serverless infrastructure market](https://betanews.com/2021/07/07/trends-serverless-infrastructure/)

- Security improvements
- Lack of standardization
- Improved application testing
- Expansion into hybrid IT
- Better monitoring
- Creating more use cases

[Infrastructure as Code](https://searchitoperations.techtarget.com/definition/Infrastructure-as-Code-IAC)

- It is an IT practice that codifies and manages underlying IT infrastructure as software. It gives us speed and efficiency, consistency and alignment with devOps. Using this practice we have a problem of which language to use. AWS created CDK, before that we need to write for cloudformation which is based on YML and being a very diificult language cloud became difficult. With CDK we can write in any prefered langaugae and it converts it into cloudformation format.

[CDK or Terraform?](https://medium.com/swlh/cdk-or-terraform-88a464bedf9e)

- Working with terraform is like working with YML files but with CDK we can programe in any language.

[What is AWS CDK, and why should your DevOps teams use it?](https://www.nclouds.com/blog/what-is-aws-cdk-and-why-should-your-devops-teams-use-it/)

- CDK is prefered as working along ith AWS it works with terraform too. And it means we can use it with azure and google cloud. It enables easier cloud onboarding, accelerates the development process, is customizable and reusable, leverages the full power of the programming language and performs type checking.

## Reading Material: -

- [What Is Cloud Computing? Definition, Benefits, Types, and Trends](https://www.toolbox.com/tech/cloud/articles/what-is-cloud-computing/)
- [AWS Named as a Cloud Leader for the 10th Consecutive Year in Gartner’s Infrastructure & Platform Services Magic Quadrant](https://aws.amazon.com/blogs/aws/aws-named-as-a-cloud-leader-for-the-10th-consecutive-year-in-gartners-infrastructure-platform-services-magic-quadrant/)
- [The Big 3 Cloud Providers: Who’ll emerge as #1?](https://www.themsphub.com/the-big-3-cloud-providers-wholl-emerge-as-1/)
- [CDK for Terraform](https://learn.hashicorp.com/tutorials/terraform/cdktf)
- [Introducing CDK for Kubernetes](https://aws.amazon.com/blogs/containers/introducing-cdk-for-kubernetes/)
- [What is the AWS CDK?](https://docs.aws.amazon.com/cdk/latest/guide/home.html)
- [AWS Free Tier](https://aws.amazon.com/free/)

## Class 7 Videos:

- [English on YouTube](https://www.youtube.com/watch?v=ic7U2r_-C78&ab_channel=PanacloudCloudAI%2CIoT%2CandBlockchainCourse)
- [English on Facebook](https://www.facebook.com/fb.anees.ahmed/videos/2918670415052373/)
- [Urdu on YouTube](https://www.youtube.com/watch?v=0mCvIqSYxK8&ab_channel=PanacloudUrduCloudAICourse)
- [Urdu on Facebook](https://www.facebook.com/Ai.SirQasim/videos/189709983183156/)
