# 中文说明
我们收集了上海大学认证系统接口在 2024年1月1日到2024年1月10日 期间共 7,439,701 条 HTTP 请求日志。
![image](https://github.com/user-attachments/assets/5687ee42-d15f-4ade-b394-8eb1ea0c7388)

该数据集详细记录了系统中各类用户操作事件的 HTTP 日志信息，涵盖用户身份、访问行为、认证结果等多个维度，广泛适用于 行为分析、入侵检测、认证审计 等研究与应用场景。

每条日志包含以下字段：

## 字段名	说明
timestamp	日志记录时间戳，精确到毫秒，便于识别高频操作及异常行为模式
uid	用户唯一标识符（User ID），用于追踪用户行为
type	访问类型，如 mail 表示邮件系统相关的访问
appName	应用名称，例如 ldap，用于标识系统组件或服务
sourceIp	用户请求的源 IP 地址
action	用户尝试执行的操作类型，例如 login
result	操作结果，常见值为 success 或 fail
message	日志附加信息，如“login from mail ldap”

# English Description
We collected 7,439,701 HTTP request logs from the Shanghai University authentication system API during the period of January 1st to January 10th, 2024.

This dataset records various user activity events in the system's HTTP logs. It includes multiple dimensions such as user identity, access behavior, and authentication results. It is suitable for use in behavioral analysis, intrusion detection, and authentication auditing.

Each log entry includes the following fields:

## Field	Description
timestamp	Timestamp of the log entry, accurate to the millisecond, useful for detecting high-frequency operations and abnormal patterns
uid	Unique user identifier (User ID) used to track individual behavior
type	Type of access, e.g., mail indicates access related to the mail system
appName	Name of the application or service component, e.g., ldap
sourceIp	Source IP address of the user request
action	Type of action attempted by the user, such as login
result	Result of the operation, typically success or fail
message	Additional context or message, e.g., “login from mail ldap”
