node{
stage ("1ST")
{
  checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/newtech43/sample1.git']]])
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
