- java -version .\mvnw.cmd --version
java version "24.0.2" 2025-07-15
Java(TM) SE Runtime Environment (build 24.0.2+12-54)
Java HotSpot(TM) 64-Bit Server VM (build 24.0.2+12-54, mixed mode, sharing)


-  java -version .\mvnw.cmd --version
java version "24.0.2" 2025-07-15
Java(TM) SE Runtime Environment (build 24.0.2+12-54)
Java HotSpot(TM) 64-Bit Server VM (build 24.0.2+12-54, mixed mode, sharing)


- .\mvnw.cmd --version
Apache Maven 3.9.11 (3e54c93a704957b63ee3494413a2b544fd3d825b)
Maven home: C:\Users\aibar\.m2\wrapper\dists\apache-maven-3.9.11\03d7e36a140982eea48e22c1dcac01d8862b2550b2939e09a0809bbc5182a5bc
Java version: 24.0.2, vendor: Oracle Corporation, runtime: C:\Program Files\Java\jdk-24
Default locale: en_US, platform encoding: UTF-8
OS name: "windows 11", version: "10.0", arch: "amd64", family: "windows"


- .\mvnw.cmd test
WARNING: A terminally deprecated method in sun.misc.Unsafe has been called
WARNING: sun.misc.Unsafe::staticFieldBase has been called by com.google.inject.internal.aop.HiddenClassDefiner (file:/C:/Users/aibar/.m2/wrapper/dists/apache-maven-3.9.11/03d7e36a140982eea48e22c1dcac01d8862b2550b2939e09a0809bbc5182a5bc/lib/guice-5.1.0-classes.jar)
WARNING: Please consider reporting this to the maintainers of class com.google.inject.internal.aop.HiddenClassDefiner
WARNING: sun.misc.Unsafe::staticFieldBase will be removed in a future release
[INFO] Scanning for projects...
[INFO]
[INFO] ----------------------< mx.edu:backend-academico >----------------------
[INFO] Building backend-academico-u01 0.0.1-SNAPSHOT
[INFO]   from pom.xml
[INFO] --------------------------------[ jar ]---------------------------------
[INFO]
[INFO] --- resources:3.5.0:resources (default-resources) @ backend-academico ---
[INFO] Copying 1 resource from src\main\resources to target\classes
[INFO] Copying 0 resource from src\main\resources to target\classes
[INFO]
[INFO] --- compiler:3.15.0:compile (default-compile) @ backend-academico ---
[INFO] Nothing to compile - all classes are up to date.
[INFO]
[INFO] --- resources:3.5.0:testResources (default-testResources) @ backend-academico ---
[INFO] skip non existing resourceDirectory C:\Users\aibar\Desktop\U01\inicio\src\test\resources
[INFO]
[INFO] --- compiler:3.15.0:testCompile (default-testCompile) @ backend-academico ---
[INFO] Nothing to compile - all classes are up to date.
[INFO]
[INFO] --- surefire:3.5.6:test (default-test) @ backend-academico ---
[INFO] Using auto detected provider org.apache.maven.surefire.junitplatform.JUnitPlatformProvider
[INFO]
[INFO] -------------------------------------------------------
[INFO]  T E S T S
[INFO] -------------------------------------------------------
[INFO] Running mx.edu.backendacademico.BackendAcademicoApplicationTests
16:29:56.294 [main] INFO org.springframework.test.context.support.AnnotationConfigCo
ntextLoaderUtils -- Could not detect default configuration classes for test class [m
x.edu.backendacademico.BackendAcademicoApplicationTests]: BackendAcademicoApplicatio
nTests does not declare any static, non-private, non-final, nested classes annotated with @Configuration.
16:29:56.432 [main] INFO org.springframework.boot.test.context.SpringBootTestContext
Bootstrapper -- Found @SpringBootConfiguration mx.edu.backendacademico.BackendAcadem
icoApplication for test class mx.edu.backendacademico.BackendAcademicoApplicationTests
16:29:56.588 [main] INFO org.springframework.test.context.support.AnnotationConfigCo
ntextLoaderUtils -- Could not detect default configuration classes for test class [m
x.edu.backendacademico.BackendAcademicoApplicationTests]: BackendAcademicoApplicatio
nTests does not declare any static, non-private, non-final, nested classes annotated with @Configuration.
16:29:56.592 [main] INFO org.springframework.boot.test.context.SpringBootTestContext
Bootstrapper -- Found @SpringBootConfiguration mx.edu.backendacademico.BackendAcadem
icoApplication for test class mx.edu.backendacademico.BackendAcademicoApplicationTests

  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/

 :: Spring Boot ::                (v4.1.0)

2026-09-25T16:29:56.974-06:00  INFO 16336 --- [backend-academico] [           main]
m.e.b.BackendAcademicoApplicationTests   : Starting BackendAcademicoApplicationTests
 using Java 24.0.2 with PID 16336 (started by aibar in C:\Users\aibar\Desktop\U01\inicio)
2026-09-25T16:29:56.977-06:00  INFO 16336 --- [backend-academico] [           main]
m.e.b.BackendAcademicoApplicationTests   : No active profile set, falling back to 1 default profile: "default"
2026-09-25T16:29:57.991-06:00  INFO 16336 --- [backend-academico] [           main]
m.e.b.BackendAcademicoApplicationTests   : Started BackendAcademicoApplicationTests in 1.322 seconds (process running for 2.556)
Mockito is currently self-attaching to enable the inline-mock-maker. This will no lo
nger work in future releases of the JDK. Please add Mockito as an agent to your buil
d as described in Mockito's documentation: https://javadoc.io/doc/org.mockito/mockito-core/latest/org.mockito/org/mockito/Mockito.html#0.3
WARNING: A Java agent has been loaded dynamically (C:\Users\aibar\.m2\repository\net\bytebuddy\byte-buddy-agent\1.18.10\byte-buddy-agent-1.18.10.jar)
WARNING: If a serviceability tool is in use, please run with -XX:+EnableDynamicAgentLoading to hide this warning
WARNING: If a serviceability tool is not in use, please run with -Djdk.instrument.traceUsage for more information
WARNING: Dynamic loading of agents will be disallowed by default in a future release
Java HotSpot(TM) 64-Bit Server VM warning: Sharing is only supported for boot loader classes because bootstrap classpath has been appended
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 2.545 s -- in mx.edu.backendacademico.BackendAcademicoApplicationTests
[INFO]
[INFO] Results:
[INFO]
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0
[INFO]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.952 s
[INFO] Finished at: 2026-09-25T16:29:58-06:00
[INFO] ------------------------------------------------------------------------


EXPLICACION

¿Por qué cambiar el puerto no exige recompilar?

Porque el puerto no vive en el código, vive en la configuración. Spring Boot lee server.port al arrancar desde application.properties,
una variable de entorno, o un argumento como --server.port=8081 y arma el servidor con ese valor.
El .class compilado nunca tiene un número de puerto escrito adentro.
Por eso el mismo archivo compilado puede correr en 8080 o en 8081 sin tocar javac para nada.

Y por la misma razón, los tests no se inmutan: @SpringBootTest arma su propio contexto por separado
y no le importa en qué puerto correría la app en producción.