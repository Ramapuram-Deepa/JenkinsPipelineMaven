node{
  stage{'SCM Checkout'}{
    git 'https://github.com/BairaboinaVyshnavi/JenkinsPipelineMaven.git'
  }
  stage{'Compile-Package'}{
    
    def mvnHome = tool name: 'mavan3', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }

}
