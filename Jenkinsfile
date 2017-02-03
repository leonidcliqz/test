@NonCPS
def printParams() {
      env.getEnvironment().each { name, value -> echo "Name: $name -> Value $value" }
}

node {
    printParams()
    echo scm.dump()
    echo scm.userRemoteConfigs
}
