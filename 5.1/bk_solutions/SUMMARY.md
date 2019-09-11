# Summary
## 蓝鲸最佳实践

* [快速入门]()
   * [新手之旅](Getting_started/Getting_started.md)
   * [FAQ](Getting_started/FAQ.md)
* [CI(持续集成)]()
   * [测试环境自动更新](CI/Pipeline_git_commit_to_stag.md)
* [CD(持续交付/部署)]()
   * [配置管理标准化]()
      * [概述( 1 : 待审核 )](CD/CMDB/Configuration_management_standardization.md)
      * [业务上线时管理主机](CD/CMDB/CMDB_management_hosts.md)
      * [管理进程](CD/CMDB/CMDB_management_process.md)
      * [管理数据库实例：以 MySQL 为例](CD/CMDB/CMDB_management_database_middleware.md)
      * [自动发现数据库实例：以 MySQL 为例](CD/CMDB/CMDB_CI_auto_discovery_MySQL.md)
      * [对接企业原有 CMDB，实现数据同步](CD/CMDB/CMDB_integration.md)
      * [Open-Falcon 集成蓝鲸 CMDB 业务拓扑树](CD/CMDB/Openfalcon_cmdb_topo_tree.md)
   * [应用交付自动化(理论篇)]()
      * [概述( 1 : 待审核 )](CD/Automation/Application_delivery_deployment_automation.md)
      * [管控混合云架构下的基础设施](CD/Automation/Hybrid_cloud_management.md)
      * [37 秒完成万台服务器的目录标准化](CD/Automation/Massive_host_control.md)
      * [一次标准的应用交付自动化案例](CD/Automation/application_deployment.md)
      * [操作员做应用交付，让运维更专注](CD/Automation/ops_half_automation.md)
      * [集成企业内部 ITIL 系统](CD/Automation/intergration_itil.md)
   * [需求自助化:测试自助调整验收环境](CD/Demand_self_service.md)
   * [容器编排]()
      * [快速构建 Nginx 集群](CD/BCS/Bcs_deploy_nginx_cluster.md)
      * [应用的滚动升级](CD/BCS/Bcs_app_Rolling_Update_Deployment.md)
      * [应用的蓝绿发布](CD/BCS/Bcs_blue_green_deployment.md)
* [CO(持续运营)]()
   * [IT 基础监控]()
      * [集成内部语音网关实现电话告警](CO/Monitor_Base/Send_voice_msg.md)
   * [业务指标监控]()
      * [概述](CO/Monitor_KPI/README.md)
   * [日志查询与监控]()
      * [概述](CO/Monitor_LogSearch/README.md)
   * [故障自愈](CO/FTA/Alarm_processing_automation.md)
      * [蓝鲸监控告警自动处理](CO/FTA/Bkmonitor_Alarm_processing_automation.md)
      * [Zabbix 告警自动处理](CO/FTA/Zabbix_Alarm_processing_automation.md)
      * [第 3 方监控系统告警自动处理](CO/FTA/REST_API_PUSH_Alarm_processing_automation.md)
   * [服务流程管理]()
      * [服务器资源申请流程线上化](CO/ITSM/Service_Request.md)
      * [应用发布流程线上化](CO/ITSM/Release_Management.md)
      * [环境变更流程线上化](CO/ITSM/Change_Management.md)
      * [故障提报流程线上化](CO/ITSM/Incident_Management.md)
