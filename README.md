# MavenSource

<mirrors>

    <mirror>
        <id>maven_plugin</id>
        <name>Maven Plugins</name>
        <mirrorOf>central</mirrorOf>
        <url>https://repo.spring.io/plugins-release/</url>
    </mirror>

    <mirror>
      <id>alimaven</id>
      <name>aliyun maven</name>
      <url>http://maven.aliyun.com/nexus/content/groups/public/</url>
      <mirrorOf>*</mirrorOf> 
    </mirror>
    
    <mirror>
      <id>alimaven_nexus</id>
      <mirrorOf>central</mirrorOf>
      <name>aliyun maven nexus</name>
      <url>http://maven.aliyun.com/nexus/content/repositories/central/</url>
    </mirror>
    
    <!-- 中央仓库1 -->
    <mirror>
        <id>repo1</id>
        <mirrorOf>central</mirrorOf>
        <name>Maven Central Repo1</name>
        <url>http://repo1.maven.org/maven2/</url>
    </mirror>
    
    <!-- 中央仓库2 -->
    <mirror>
        <id>repo2</id>
        <mirrorOf>central</mirrorOf>
        <name>Maven Central Repo2</name>
        <url>http://repo2.maven.org/maven2/</url>
    </mirror>

<mirrors>
