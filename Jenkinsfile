#!/bin/bash
pipeline {
    agent none
   stages {     
    stage('JDK Install') {
      agent {         
       docker {          
         image 'openjdk:8-alpine'         
     }       
  }       
  steps {
       sh 'mvn clean install'
       }
     }
   }
 }
