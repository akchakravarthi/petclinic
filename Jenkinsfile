#!/bin/bash
pipeline {
    pipeline {
    agent { dockerfile true }
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
