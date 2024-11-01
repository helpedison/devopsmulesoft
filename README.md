# CI/CD in mulesoft

# GitHub Actions Workflows

Three environments are defined (`DEV`, `QA`, and `PROD`), each with instructions specified in YAML files.

### Libreries SAP

![Texto alternativo](imgs/mulesoft_libs_sap.PNG)
More info -> https://docs.mulesoft.com/sap-connector/latest/sap-connector-studio

You can donwload in this repo, you must follow it this path (only linux)

- lib\Linux86-64
  - libsapjco3.so
  - sapidoc3.jar
  - sapjco3.jar 

Note: Must review compatibility with the runtime that it runs 

### Configuration in github



### Work it of the connected apps 




### Example project customer surexport







## Details
- Each environment has its own configuration
- Instructions are written in YAML format
- Pipeline configurations include:
 - Development (`DEV`)
 - Quality Assurance (`QA`)
 - Production (`PROD`)

# File Structure

- .github/
  - workflows/
    - dev-pipeline.yml
    - qa-pipeline.yml
    - prod-pipeline.yml
 
##  buil-dev.yaml 

ubuntu-latest

ubuntu-latest
Install SAP JCo Native Library
Install SAP JCo Native sapjco3
Install SAP JCo Native sapidoc3


Build with Maven    


##  buil-qa.yaml 

 