Developer HDP Cluster
=================

Likely 4 nodes that represent a standard HDP cluste to enable trying std. Big Data App developer usecase.

HDP components includeing
- Core: HDFS, YARN, Zookeeper
- Data store: HBase
- Processing: MRv2, Tez, Hive, Pig
- Workflow: Oozie, Falcon
- Others: Slider, Sqoop, Client

# Masters
Master node x 3.
- Master1: Namenode, History Server, ZooKeeper1, Oozie Server, Falcon Server
- Master2: ResourceManager, Hive Metastore, Hive Server2, ZooKeeper2, WebHCat Server
- Master3: SecoundaryNamenode, HMaster, ZooKeeper3, App Timeline Server

# Slaves
Slave node x 1
- DataNode, NodeManager, RegionServer

