### Helm

- Helm changes a lot form version to version
- Understanding the basic common priniciples and use cases

- What is Helm?
  - Package manager for K8s
  - To package YAML files and distrubte them in public and private repo
  - That bundle (from example explanation - https://youtu.be/X48VuDVv0do?t=8730) of YAML files is called Helm charts.
- What are Helm Charts?
  - Bundle of YAML Files
  - Create your own Hel Charts with Helm
  - Push them to Helm Repo or private repo(couple of tools available)
  - Download an use existing ones
  - Second Feature of it is Templating Engine
    - Define a common blueprint
    - Dynamic values are placed by placeholders in Template files ( and refered from values.yaml file, either from file pr --set flag can be used to set the values)
  - Another use case is
    - Same application across different environments
  - Third feature
    - Release management
- How to use them?
  - helm search <keyword> in cli or Helm Hub
  - Helm install <chartname>
- When to use them?
  - d
- What is Tiller? and what part it plays in the helm arch
