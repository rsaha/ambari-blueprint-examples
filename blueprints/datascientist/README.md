HDP Cluster with Spark
======================

Deploys 4 nodes cluster including Spark to enable trying HDP for data scientist usecase.

HDP components includeing
- Core: HDFS, YARN, Zookeeper
- Data store: HBase
- Processing: MRv2, Tez, Hive, Pig, Spark
- Workflow: Oozie, Falcon
- Others: Slider, Client

# Masters
Master node x 3.
- Master1: Namenode, History Server, ZooKeeper1, Oozie Server, Falcon Server
- Master2: ResourceManager, Hive Metastore, Hive Server2, ZooKeeper2, WebHCat Server, Spark History Server
- Master3: SecoundaryNamenode, HMaster, ZooKeeper3, App Timeline Server

# Core Slaves
Slave node x 1
- DataNode, NodeManager, RegionServer

