# AWS Solutions Architect certification


### Description
Here is my experience for taking [SAA-C02](https://aws.amazon.com/certification/certified-solutions-architect-associate) and [SAP](https://aws.amazon.com/certification/certified-solutions-architect-professional) certification.
You can also take a look at [Available AWS Certifications](https://aws.amazon.com/certification) for complete list of available certifications.
Compare to [java cert](https://github.com/dgaydukov/cert-ocpjp11) where you have to pass associate exam before passing professional, in aws you can 
[directly pass professional without passing associate](https://aws.amazon.com/about-aws/whats-new/2018/10/announcing-more-flexibility-for-aws-certification-exams) 
But since we get 50% discount after success [here](https://aws.amazon.com/certification/benefits) 
and [here](https://aws.amazon.com/about-aws/whats-new/2019/02/new-aws-certification-policies-offer-more-choices-flexibility) and since professional costs twice the associate, whatever pass you take you pay the same amount.
If you go with associate + professional => you pay 150 + 300 with 50% discount (so you will pay only 150 for second exam) = 300 totally. 
If you go straight to professional you just pay 300. But I would encourage you to take both, since during preparation for both of them you will learn a lot of new funny stuff.


### Why do you need it.
There are 2 main reasons to get it.
1. During preparation you will learn a lot of new stuff
2. It may help your career


### Contents
* [Solutions Architect Tips](htгигtps://github.com/dgaydukov/cert-aws-sa/blob/master/files/sa.md)


### Useful Links
* [Mock exam SAA](https://www.whizlabs.com/aws-solutions-architect-associate)
* [Mock exam SAP](https://www.whizlabs.com/aws-solutions-architect-professional)
* [Udemy Jon Bonso's exam](https://www.udemy.com/course/aws-certified-solutions-architect-associate-amazon-practice-exams-saa-c02)
* [AWS Well-Architected](https://aws.amazon.com/architecture/well-architected) - read all whitepapers here
* [SAP Exam Learning Path](https://jayendrapatil.com/aws-certified-solution-architect-professional-exam-learning-path)
* Read all FAQ & user guide for every AWS service


### TODO
* rds read replica (cross-region) vs multi-az failover
* cognito + api gateway + s3 serverless app (call cognito from java code from local machine vs from ec2) => put it all into cloudformation
* can you see building blocks (ec2/rds/elb) when using beanstalk + try codestar
* cross-region vpc peering
* vpc peering (non-transitive)
* vpc to on-premise (imitated by vpc + openswan) vpn connection (site-to-site vpn)
* transit vpc
* vpc endpoint service (add ec2+NLB and share ti to vpc from another region)
* transit gateway (connect multiple vpc to each other)
* client vpn (connect to vpc from you remote laptop)
* site-to-site vpn
* direct connect