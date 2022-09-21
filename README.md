# wind-server-repository
a repository for wind-server include all necessary packages
1. 使用python-3.7.8
2. 需要下载mongodb、redis（？）
3. 在engine/store/MongoStore.py
import motor.motor_asyncio
self.conn = motor.motor_asyncio.AsyncIOMotorClient('localhost', 27017)
4. 下载etcd，将含有etcd、etcdctl的文件添加到系统环境变量, 启动etcd
5. 下载nats, 启动nats
