- 用户故事 User Story：
- 版本 Version：
- 问题重现 Reproduction：
- 关联现有系统的模块：
- 输出结果 Expected Results：(以check box方式列举)



例如：

- 用户故事 User Story：有一些客户的Hadoop集群是隔离不同环境的，一个环境无法直接连接到另一个集群的HDFS文件系统。跨Hadoop集群迁移工具在对于这样的环境处理单个Cube跨集群迁移有改进的空间。导入cube的时候可以开放选项从本地文件系统中导入，而不强制需要从HDFS导入。
- 版本 Version：Any KAP version
- 问题重现 Reproduction：N/A
- 关联现有系统的模块：Cube导入
- 输出结果 Expected Results：
  - [x] 研究这样的从本地文件系统中导入迁移的cube方案是否可行
  - [ ] 如果可行进行Manual修订