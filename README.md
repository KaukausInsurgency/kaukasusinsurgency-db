<a href='http://158.69.193.117:8080/job/KI-Test-DB/'><img src='http://158.69.193.117:8080/job/KI-Test-DB/badge/icon'></a>

# ki-db

## comitting guidelines
Please ensure that you have removed all instances of DEFINER when exporting sql scripts. 
Ie. find and replace 'DEFINER=`root`@`localhost`' with '' and then commit to repo.
If you do not do this it will fail the build on Jenkins.
