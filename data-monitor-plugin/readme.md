            <!-- 使用方式 -->
            <plugin>
                <groupId>com.linewell.data.monitor</groupId>
                <artifactId>data-monitor-plugin</artifactId>
                <version>1.0</version>
                <configuration>
                    <output>${project.build.directory}</output>
                </configuration>
                <executions>
                    <execution>
                        <phase>test-compile</phase>
                        <goals>
                            <goal>touch</goal>
                        </goals>
                    </execution>
                </executions>
            </plugin>
            <plugin>