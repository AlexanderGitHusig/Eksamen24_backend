CA2 backend

To use the project follow the steps

- Change name, artifactId, dbname and remote server in pom.xml
- Add REMOTE_USER and REMOTE_PW on github
- Check name of branch in mavenworkflow.yml and change if it doesnt match (either master or main)
- Add datasource and run SetupTestUsers
- Check persistence.xml for DB, password and username (line 24, 25, 26)