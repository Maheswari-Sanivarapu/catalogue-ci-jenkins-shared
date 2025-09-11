@Library('my-shared-library') _

def configMap = [
    PROJECT : "roboshop",
    COMPONENT : "catalogue"
]
if ( ! env.BRANCH_NAME.equalsIgnoreCase('main') ){ // if not equals to main
    nodejsEKSPipeline(configMap) // by default it will call, call function inside this pipeline
}
else {
    echo 'Please Proceed with PROD Process'
}
