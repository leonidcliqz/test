@NonCPS
def printParams() {
      env.getEnvironment().each { name, value -> echo "Name: $name -> Value $value" }
}

node {
    printParams()
    echo $CHANGE_TITLE
    echo $CHANGE_ID
    echo scm.dump()
    echo scm.userRemoteConfigs
}
