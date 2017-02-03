@NonCPS
def printParams() {
      env.getEnvironment().each { name, value -> echo "Name: $name -> Value $value" }
}

@NonCPS
def printGit() {
    scm.userRemoteConfigs.each { echo it }
}

node {
    printParams()
    echo scm.dump()
    printGit()
}
