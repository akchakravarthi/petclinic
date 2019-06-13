#!/bin/bash
pipeline {
    agent none
   stages {     
    stage('Maven Install') {
      agent {         
       docker {          
         image 'maven:3.5' --privileged      
     }       
  }       
  steps {
       sh 'mvn clean install'
       }
     }
   }
 }
