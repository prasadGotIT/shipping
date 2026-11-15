@Library('jenkins-shared-library') _

def configMap = [
    project: "roboshop",
    component: "shipping"
]

echo "Going to execute jenkins shared library"
if ( ! env.BRANCH_NAME.equalsIgnoreCase('main') ){
    javaEKSPipeline(configMap)
}
else {
    echo "Please follow the CR process"
}