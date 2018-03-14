node{
stage ("1ST")
{
  checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'bd6831be-eb19-44b1-a119-786a39ac4be0', url: 'https://github.com/newtech43/sample1']]])
}
stage ("2nd")
{
echo "shanmukha"
}
stage ("3rd")
{
sh "sample.sh"
}
}
