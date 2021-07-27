# reg-ex

### commons-validator-1.4.0-org
#### changes: 
1. maven's source / target setting from 1.4 to 1.7
<maven.compile.source>1.7</maven.compile.source>
<maven.compile.target>1.7</maven.compile.target>

#### result
Tests run: 415, Failures: 7, Errors: 1, Skipped: 0

### commons-validator-1.4.0-beanutils-1.6.1

#### changes: 
1. maven's source / target setting from 1.4 to 1.7
<maven.compile.source>1.7</maven.compile.source>
<maven.compile.target>1.7</maven.compile.target>

2.dependency beanutils from 1.8.3 to 1.6.1

    <dependency>
      <groupId>commons-beanutils</groupId>
      <artifactId>commons-beanutils</artifactId>
      <version>1.6.1</version>
    </dependency>

#### result
Tests run: 415, Failures: 7, Errors: 108, Skipped: 0

#### commons-validator-1.4.0-beanutils-1.9.3

#### changes: 
1. maven's source / target setting from 1.4 to 1.7
<maven.compile.source>1.7</maven.compile.source>
<maven.compile.target>1.7</maven.compile.target>

2.dependency beanutils from 1.8.3 to 1.9.3
    <dependency>
      <groupId>commons-beanutils</groupId>
      <artifactId>commons-beanutils</artifactId>
      <version>1.9.3</version>
    </dependency>
#### result
Tests run: 415, Failures: 7, Errors: 1, Skipped: 0

#### commons-validator-1.4.0-digester-2.1
#### changes: 
1. maven's source / target setting from 1.4 to 1.7
<maven.compile.source>1.7</maven.compile.source>
<maven.compile.target>1.7</maven.compile.target>

2.dependency digester to 2.1
      <groupId>commons-digester</groupId>
      <artifactId>commons-digester</artifactId>
      <version>2.1</version>

#### result
Tests run: 415, Failures: 7, Errors: 1, Skipped: 0

#### commons-validator-1.4.0-digester-1.3
#### changes: 
1. maven's source / target setting from 1.4 to 1.7
<maven.compile.source>1.7</maven.compile.source>
<maven.compile.target>1.7</maven.compile.target>

2.dependency digester to 1.3
      <groupId>commons-digester</groupId>
      <artifactId>commons-digester</artifactId>
      <version>1.3</version>
      
3.fix error by comment out a line of code at ValidatorResources.java[243,20]. 

     [ERROR] /Users/cheny39/Documents/tmp/reg-ex/commons-validator-1.4.0-digester-1.3/src/main/java/org/apache/commons/validator/ValidatorResources.java:[243,20] error: no suitable method found for parse(URL)
#### result
Tests run: 415, Failures: 7, Errors: 108, Skipped: 0

