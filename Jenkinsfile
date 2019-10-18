#!/usr/bin/env groovy

// Configure using microservice-pipelines and using "part2" branch
@Library("microservice-pipelines@part2") _

// Entry point into microservice-pipelines
jenkinsJob.call()

def mvn_version = 'M3'
withEnv( ["PATH+MAVEN=${tool mvn_version}/bin"] ) {
  //sh "mvn clean package"
}
