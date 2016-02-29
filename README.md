# maven


- Run java program
  - `mvn exec:java  -Dexec.mainClass=YOUR_PACKAGE_NAME.YOUR_JAVA_FILE -Dexec.args="arg1 arg2 arg3"`
    - e.g., `mvn exec:java  -Dexec.mainClass=cloudmtd.MTDSimulationBase -Dexec.args="nomad" > log.txt`
