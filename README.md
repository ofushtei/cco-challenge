<img src="https://github.com/ofushtei/cco-challenge-test/assets/46541097/3fa766bb-9fcc-4a1e-9db6-1fdcc00d7646">


Quick rundown:
- basic.yaml - full deployment, but creates everything in the hardcoded namespace __DO NOT USE__
- deploy-full.yaml - full deployment of all components
- deploy-challenge-v1.yaml - deployment without Java instrumention

Remember, before applying the file, please add the namespace you want to use to the __*ClusterRoleBinding*__ object, specifically in __*subjects*__
It should look like this:

<img src="https://github.com/ofushtei/cco-challenge-test/assets/46541097/092f094c-7ea1-4740-8548-898dd58a8495" width="400">

Also, there is __NO__ version-control going on here, I cba 🤡 

For Konrad:
Use deploy-challenge-v1.yaml
