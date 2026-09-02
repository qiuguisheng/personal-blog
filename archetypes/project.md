+++
date = '{{ .Date }}'
draft = true
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
tags = []
client = ""          # 客户/所属项目方（可脱敏，如"某金融企业"）
role = ""            # 你的角色，如"架构设计与实施负责人"
stack = []            # 技术栈标签，如 ["PVE", "Ceph", "Prometheus"]
duration = ""         # 项目周期
outcome = ""          # 一句话量化成果，如"成本降低30%，故障响应时间缩短60%"
+++

## 项目背景
（一段话说明客户面临的问题）

## 解决方案
（你做了什么，技术选型和关键决策）

## 交付成果
（量化结果：性能提升、成本节省、稳定性提升等）