# gitblit
gitbit_v1.9.3 源代码 不包含前端内容，仅供参考学习。
需要添加到classpath下的内容(jar包在lib目录下)：
```xml
<classpath>
	<classpathentry kind="src" path="src/main/java" />
	<classpathentry kind="src" path="src/main/bugtraq" />
	<classpathentry kind="src" path="src/test/java" output="bin/test-classes" />
	<classpathentry kind="src" path="src/test/bugtraq" output="bin/test-classes" />
	<classpathentry kind="src" path="src/main/resources" />
	<classpathentry kind="src" path="src/test/resources" output="bin/test-classes" />
	<classpathentry kind="lib" path="ext/guice-4.0.jar" sourcepath="ext/src/guice-4.0.jar" />
	<classpathentry kind="lib" path="ext/javax.inject-1.jar" sourcepath="ext/src/javax.inject-1.jar" />
	<classpathentry kind="lib" path="ext/aopalliance-1.0.jar" sourcepath="ext/src/aopalliance-1.0.jar" />
	<classpathentry kind="lib" path="ext/guava-18.0.jar" sourcepath="ext/src/guava-18.0.jar" />
	<classpathentry kind="lib" path="ext/guice-servlet-4.0-gb2.jar" sourcepath="ext/src/guice-servlet-4.0-gb2.jar" />
	<classpathentry kind="lib" path="ext/annotations-12.0.jar" sourcepath="ext/src/annotations-12.0.jar" />
	<classpathentry kind="lib" path="ext/log4j-1.2.17.jar" sourcepath="ext/src/log4j-1.2.17.jar" />
	<classpathentry kind="lib" path="ext/slf4j-api-1.7.29.jar" sourcepath="ext/src/slf4j-api-1.7.29.jar" />
	<classpathentry kind="lib" path="ext/slf4j-log4j12-1.7.29.jar" sourcepath="ext/src/slf4j-log4j12-1.7.29.jar" />
	<classpathentry kind="lib" path="ext/javax.mail-1.5.6.jar" sourcepath="ext/src/javax.mail-1.5.6.jar" />
	<classpathentry kind="lib" path="ext/activation-1.1.jar" sourcepath="ext/src/activation-1.1.jar" />
	<classpathentry kind="lib" path="ext/javax.servlet-api-3.1.0.jar" sourcepath="ext/src/javax.servlet-api-3.1.0.jar" />
	<classpathentry kind="lib" path="ext/jetty-all-9.2.30.v20200428.jar" sourcepath="ext/src/jetty-all-9.2.30.v20200428.jar" />
	<classpathentry kind="lib" path="ext/wicket-1.4.22.jar" sourcepath="ext/src/wicket-1.4.22.jar" />
	<classpathentry kind="lib" path="ext/wicket-auth-roles-1.4.22.jar" sourcepath="ext/src/wicket-auth-roles-1.4.22.jar" />
	<classpathentry kind="lib" path="ext/wicket-extensions-1.4.22.jar" sourcepath="ext/src/wicket-extensions-1.4.22.jar" />
	<classpathentry kind="lib" path="ext/lucene-core-5.5.2.jar" sourcepath="ext/src/lucene-core-5.5.2.jar" />
	<classpathentry kind="lib" path="ext/lucene-analyzers-common-5.5.2.jar" sourcepath="ext/src/lucene-analyzers-common-5.5.2.jar" />
	<classpathentry kind="lib" path="ext/lucene-highlighter-5.5.2.jar" sourcepath="ext/src/lucene-highlighter-5.5.2.jar" />
	<classpathentry kind="lib" path="ext/lucene-memory-5.5.2.jar" sourcepath="ext/src/lucene-memory-5.5.2.jar" />
	<classpathentry kind="lib" path="ext/lucene-queries-5.5.2.jar" sourcepath="ext/src/lucene-queries-5.5.2.jar" />
	<classpathentry kind="lib" path="ext/lucene-queryparser-5.5.2.jar" sourcepath="ext/src/lucene-queryparser-5.5.2.jar" />
	<classpathentry kind="lib" path="ext/lucene-sandbox-5.5.2.jar" sourcepath="ext/src/lucene-sandbox-5.5.2.jar" />
	<classpathentry kind="lib" path="ext/jakarta-regexp-1.4.jar" />
	<classpathentry kind="lib" path="ext/pegdown-1.5.0.jar" sourcepath="ext/src/pegdown-1.5.0.jar" />
	<classpathentry kind="lib" path="ext/parboiled-java-1.1.7.jar" sourcepath="ext/src/parboiled-java-1.1.7.jar" />
	<classpathentry kind="lib" path="ext/parboiled-core-1.1.7.jar" sourcepath="ext/src/parboiled-core-1.1.7.jar" />
	<classpathentry kind="lib" path="ext/asm-5.0.3.jar" sourcepath="ext/src/asm-5.0.3.jar" />
	<classpathentry kind="lib" path="ext/asm-tree-5.0.3.jar" sourcepath="ext/src/asm-tree-5.0.3.jar" />
	<classpathentry kind="lib" path="ext/asm-analysis-5.0.3.jar" sourcepath="ext/src/asm-analysis-5.0.3.jar" />
	<classpathentry kind="lib" path="ext/asm-util-5.0.3.jar" sourcepath="ext/src/asm-util-5.0.3.jar" />
	<classpathentry kind="lib" path="ext/wikitext-core-1.4.jar" sourcepath="ext/src/wikitext-core-1.4.jar" />
	<classpathentry kind="lib" path="ext/twiki-core-1.4.jar" sourcepath="ext/src/twiki-core-1.4.jar" />
	<classpathentry kind="lib" path="ext/textile-core-1.4.jar" sourcepath="ext/src/textile-core-1.4.jar" />
	<classpathentry kind="lib" path="ext/tracwiki-core-1.4.jar" sourcepath="ext/src/tracwiki-core-1.4.jar" />
	<classpathentry kind="lib" path="ext/mediawiki-core-1.4.jar" sourcepath="ext/src/mediawiki-core-1.4.jar" />
	<classpathentry kind="lib" path="ext/confluence-core-1.4.jar" sourcepath="ext/src/confluence-core-1.4.jar" />
	<classpathentry kind="lib" path="ext/org.eclipse.jgit-4.5.7.201904151645-r.jar" sourcepath="ext/src/org.eclipse.jgit-4.5.7.201904151645-r.jar" />
	<classpathentry kind="lib" path="ext/jsch-0.1.53.jar" sourcepath="ext/src/jsch-0.1.53.jar" />
	<classpathentry kind="lib" path="ext/JavaEWAH-0.7.9.jar" sourcepath="ext/src/JavaEWAH-0.7.9.jar" />
	<classpathentry kind="lib" path="ext/httpclient-4.3.6.jar" sourcepath="ext/src/httpclient-4.3.6.jar" />
	<classpathentry kind="lib" path="ext/httpcore-4.3.3.jar" sourcepath="ext/src/httpcore-4.3.3.jar" />
	<classpathentry kind="lib" path="ext/commons-logging-1.1.3.jar" sourcepath="ext/src/commons-logging-1.1.3.jar" />
	<classpathentry kind="lib" path="ext/commons-codec-1.7.jar" sourcepath="ext/src/commons-codec-1.7.jar" />
	<classpathentry kind="lib" path="ext/org.eclipse.jgit.http.server-4.5.7.201904151645-r.jar" sourcepath="ext/src/org.eclipse.jgit.http.server-4.5.7.201904151645-r.jar" />
	<classpathentry kind="lib" path="ext/bcprov-jdk15on-1.57.jar" sourcepath="ext/src/bcprov-jdk15on-1.57.jar" />
	<classpathentry kind="lib" path="ext/bcmail-jdk15on-1.57.jar" sourcepath="ext/src/bcmail-jdk15on-1.57.jar" />
	<classpathentry kind="lib" path="ext/bcpkix-jdk15on-1.57.jar" sourcepath="ext/src/bcpkix-jdk15on-1.57.jar" />
	<classpathentry kind="lib" path="ext/sshd-core-1.2.0.jar" sourcepath="ext/src/sshd-core-1.2.0.jar" />
	<classpathentry kind="lib" path="ext/mina-core-2.0.21.jar" sourcepath="ext/src/mina-core-2.0.21.jar" />
	<classpathentry kind="lib" path="ext/rome-0.9.jar" sourcepath="ext/src/rome-0.9.jar" />
	<classpathentry kind="lib" path="ext/jdom-1.0.jar" sourcepath="ext/src/jdom-1.0.jar" />
	<classpathentry kind="lib" path="ext/gson-2.3.1.jar" sourcepath="ext/src/gson-2.3.1.jar" />
	<classpathentry kind="lib" path="ext/groovy-all-2.4.4.jar" sourcepath="ext/src/groovy-all-2.4.4.jar" />
	<classpathentry kind="lib" path="ext/unboundid-ldapsdk-2.3.8.jar" sourcepath="ext/src/unboundid-ldapsdk-2.3.8.jar" />
	<classpathentry kind="lib" path="ext/ivy-2.2.0.jar" sourcepath="ext/src/ivy-2.2.0.jar" />
	<classpathentry kind="lib" path="ext/jcalendar-1.3.2.jar" />
	<classpathentry kind="lib" path="ext/commons-compress-1.4.1.jar" sourcepath="ext/src/commons-compress-1.4.1.jar" />
	<classpathentry kind="lib" path="ext/xz-1.0.jar" sourcepath="ext/src/xz-1.0.jar" />
	<classpathentry kind="lib" path="ext/commons-io-2.2.jar" sourcepath="ext/src/commons-io-2.2.jar" />
	<classpathentry kind="lib" path="ext/force-partner-api-24.0.0.jar" sourcepath="ext/src/force-partner-api-24.0.0.jar" />
	<classpathentry kind="lib" path="ext/force-wsc-24.0.0.jar" sourcepath="ext/src/force-wsc-24.0.0.jar" />
	<classpathentry kind="lib" path="ext/js-1.7R2.jar" sourcepath="ext/src/js-1.7R2.jar" />
	<classpathentry kind="lib" path="ext/freemarker-2.3.22.jar" sourcepath="ext/src/freemarker-2.3.22.jar" />
	<classpathentry kind="lib" path="ext/waffle-jna-1.7.3.jar" sourcepath="ext/src/waffle-jna-1.7.3.jar" />
	<classpathentry kind="lib" path="ext/jna-4.1.0.jar" sourcepath="ext/src/jna-4.1.0.jar" />
	<classpathentry kind="lib" path="ext/jna-platform-4.1.0.jar" sourcepath="ext/src/jna-platform-4.1.0.jar" />
	<classpathentry kind="lib" path="ext/libpam4j-1.8.jar" sourcepath="ext/src/libpam4j-1.8.jar" />
	<classpathentry kind="lib" path="ext/args4j-2.0.29.jar" sourcepath="ext/src/args4j-2.0.29.jar" />
	<classpathentry kind="lib" path="ext/jedis-2.6.2.jar" sourcepath="ext/src/jedis-2.6.2.jar" />
	<classpathentry kind="lib" path="ext/commons-pool2-2.0.jar" sourcepath="ext/src/commons-pool2-2.0.jar" />
	<classpathentry kind="lib" path="ext/pf4j-0.9.0.jar" sourcepath="ext/src/pf4j-0.9.0.jar" />
	<classpathentry kind="lib" path="ext/tika-core-1.5.jar" sourcepath="ext/src/tika-core-1.5.jar" />
	<classpathentry kind="lib" path="ext/jsoup-1.7.3.jar" sourcepath="ext/src/jsoup-1.7.3.jar" />
	<classpathentry kind="lib" path="ext/javax.activation-1.2.0.jar" sourcepath="ext/src/javax.activation-1.2.0.jar" />
	<classpathentry kind="lib" path="ext/junit-4.12.jar" sourcepath="ext/src/junit-4.12.jar" />
	<classpathentry kind="lib" path="ext/hamcrest-core-1.3.jar" sourcepath="ext/src/hamcrest-core-1.3.jar" />
	<classpathentry kind="lib" path="ext/selenium-java-2.28.0.jar" sourcepath="ext/src/selenium-java-2.28.0.jar" />
	<classpathentry kind="lib" path="ext/selenium-support-2.28.0.jar" sourcepath="ext/src/selenium-support-2.28.0.jar" />
	<classpathentry kind="lib" path="ext/selenium-firefox-driver-2.28.0.jar" sourcepath="ext/src/selenium-firefox-driver-2.28.0.jar" />
	<classpathentry kind="lib" path="ext/selenium-remote-driver-2.28.0.jar" sourcepath="ext/src/selenium-remote-driver-2.28.0.jar" />
	<classpathentry kind="lib" path="ext/cglib-nodep-2.1_3.jar" sourcepath="ext/src/cglib-nodep-2.1_3.jar" />
	<classpathentry kind="lib" path="ext/json-20080701.jar" sourcepath="ext/src/json-20080701.jar" />
	<classpathentry kind="lib" path="ext/selenium-api-2.28.0.jar" sourcepath="ext/src/selenium-api-2.28.0.jar" />
	<classpathentry kind="lib" path="ext/commons-exec-1.1.jar" sourcepath="ext/src/commons-exec-1.1.jar" />
	<classpathentry kind="lib" path="ext/platform-3.4.0.jar" sourcepath="ext/src/platform-3.4.0.jar" />
	<classpathentry kind="lib" path="ext/mockito-core-2.28.2.jar" sourcepath="ext/src/mockito-core-2.28.2.jar" />
	<classpathentry kind="lib" path="ext/byte-buddy-1.9.10.jar" sourcepath="ext/src/byte-buddy-1.9.10.jar" />
	<classpathentry kind="lib" path="ext/byte-buddy-agent-1.9.10.jar" sourcepath="ext/src/byte-buddy-agent-1.9.10.jar" />
	<classpathentry kind="lib" path="ext/objenesis-2.6.jar" sourcepath="ext/src/objenesis-2.6.jar" />
	<classpathentry kind="con" path="org.eclipse.jdt.launching.JRE_CONTAINER" />
	<classpathentry kind="output" path="bin/classes" />
</classpath>
```