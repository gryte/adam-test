node {
  checkout scm
  sh 'npm install'
  sh 'npm run build-linux'
  dir('dist') {
    archiveArtifacts artifacts: '*.zip', fingerprint: true;
  }

}
