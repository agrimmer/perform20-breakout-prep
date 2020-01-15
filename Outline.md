**Outline for the Presentation**

1. Sebastian: Introduction and Motivation (<10min)
    - What is Aboi?
    - Limitation of existing architecture (i.e. it is/was a monolith)
    - Why K8s?
    - Business driver why to transform Aboi
    - New deployment process covering the business requirements (different customers, different versions) 

1. Sebastian: Demo 1 (2min)
    - Show application in v1 (e.g. with 5 features) in staging and prod representing the current implementation
    - New application in v2 with 6 features 
    - Inform Keptn about new image in v2 (tests will approx. take 5min)

1. Andreas: Keptn (10min)
    - What is keptn?
    - What is going on in the backround?
    - Introduce Quality Gates (e.g. for metrics, architecture, business)

1. Sebastian: Demo 2 (10min)
    - New build is available in staging
    - Show notifications in WebEx and Slack
    - Show SLI, SLO and why this build was failing
    - Show events in DT (deployments, testing, etc.), dashboards, and how the response time increased
    - Deploy v3

1. Outlook (6min)
    - Sebastian: Relationship Avodaq <-> DT
    - Andreas: Keptn is not only CD but also CO
    - Sebastian: Feature flags
    - Andreas: Key Takeaways
    - Sebastian: Verify v3 in production 
