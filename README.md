## Source Code Line Count Maven Plugin

统计源代码中每个文件的行数

### Usage

```
<plugin>
    <groupId>com.github.bowen</groupId>
    <artifactId>source-code-line-count-maven-plugin</artifactId>
    <version>1.0-SNAPSHOT</version>
    <executions>
        <execution>
            <goals>
                <goal>countLines</goal>
            </goals>
            <phase>initialize</phase>
        </execution>
    </executions>
</plugin>
```
