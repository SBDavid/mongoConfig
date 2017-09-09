## 启动手册

### home

- 启动server home: "C:\Program Files\MongoDB\Server\3.4\bin\mongod.exe" -f "D:\005-mongo\mongoConfig\mongod_home.conf"

- 安装win service: mongod -f "D:\005-mongo\mongoConfig\mongod_home.conf" --install --serviceName mongodInstance1 --serviceDisplayName  mongodInstance1

- 启动win service: net start mongodInstance1

- 停止win service: net stop mongodInstance1

### work

- 启动server work: "C:\Program Files\MongoDB\Server\3.4\bin\mongod.exe" -f "D:\005-project\mongo\mongoConfig\mongod_work.conf"

- 安装win service: mongod -f "D:\005-project\mongo\mongoConfig\mongod_work.conf" --install --serviceName mongodInstance1 --serviceDisplayName  mongodInstance1

- 启动win service: net start mongodInstance1

- 停止win service: net stop mongodInstance1

### 宝山

- 启动server work: "C:\Program Files\MongoDB\Server\3.4\bin\mongod.exe" -f "D:\005-project\mongo\mongoConfig\mongod_work.conf"

- 安装win service: mongod -f "D:\project\mongo\mongoConfig\mongod_baoshan.conf" --install --serviceName mongodInstance1 --serviceDisplayName  mongodInstance1

- 启动win service: net start mongodInstance1

- 停止win service: net stop mongodInstance1