@Library('jenkins-shared-library') _

def configMap = [
    project: "robomart", 
    component: "payment"
]

if ( !env.BRANCH_NAME.equalsIgnoreCase("main") ) {
    echo "Deploying on non-prod branch"
    pythonEKSPipeline(configMap)

} else {
    echo "Kindly follow the CR process"
}