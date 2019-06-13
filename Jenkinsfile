#!/bin/bash
pipeline {
    agent any
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
