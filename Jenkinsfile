#!/bin/bash
pipeline {
    agent none
   stages {     
    stage('Maven Install') {
      agent {         
       docker {          
         image 'maven:3.5'     
     }       
  }       
  steps {
       sh 'mvn clean install'
       }
     }
   }
 }
