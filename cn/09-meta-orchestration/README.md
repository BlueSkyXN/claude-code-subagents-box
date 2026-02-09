# 元编排子代理

元编排子代理是您的指挥家和协调者,管理复杂的多代理工作流并优化AI系统性能。这些专家擅长元级工作——编排其他代理、管理上下文、分配任务,并确保多个AI系统之间的顺畅协作。它们将混乱转化为交响乐,让复杂的AI系统和谐地协同工作。

## 何时使用元编排子代理

在以下情况下使用这些子代理:
- **协调多个代理**执行复杂任务
- **优化上下文使用**跨对话
- **高效分配任务**给专家
- **优雅处理错误**在多代理系统中
- **综合知识**来自各种来源
- **监控性能**的AI工作流
- **设计复杂工作流**具有多个步骤
- **扩展AI操作**跨团队

## 可用子代理

### [**agent-organizer**](agent-organizer.md) - 多代理协调器
编排专家,管理复杂的多代理协作。掌握任务分解、代理选择和结果综合。将复杂问题转化为协调的解决方案。

**使用场景:** 协调多个代理、分解复杂任务、管理代理依赖关系、综合结果或设计代理工作流。

### [**context-manager**](context-manager.md) - 上下文优化专家
上下文专家,最大化AI对话效率。精通上下文窗口、信息优先级和内存管理。确保有限上下文空间的最佳使用。

**使用场景:** 优化长对话、管理上下文窗口、优先信息、实现内存系统或处理上下文溢出。

### [**error-coordinator**](error-coordinator.md) - 错误处理和恢复专家
错误处理专家,确保优雅的故障恢复。掌握错误模式、回退策略和系统弹性。保持多代理系统在故障时平稳运行。

**使用场景:** 实现错误处理、设计恢复策略、管理级联故障、监控系统健康或构建弹性工作流。

### [**it-ops-orchestrator**](it-ops-orchestrator.md) - PowerShell/.NET生态系统的IT运维元编排器
元编排器,将模糊的基础设施和运维任务路由到正确的专家代理,强烈偏好PowerShell和基于.NET的工作流。了解Windows基础设施、Azure、M365和PowerShell语言专家的角色,并协调他们提供端到端解决方案。

**使用场景:** 任务涉及IT运维或基础设施自动化,但跨越多个领域(AD、DNS/DHCP、Azure、M365、PowerShell模块)。该编排器选择并协调最佳子代理(例如windows-infra-admin、azure-infra-engineer、m365-admin、powershell-5.1-expert、powershell-7-expert、powershell-module-architect),默认使用PowerShell作为实现语言。

### [**knowledge-synthesizer**](knowledge-synthesizer.md) - 知识聚合专家
知识综合专家,组合来自多个来源的信息。精通信息融合、冲突解决和洞察生成。从多样化的输入中创建连贯的知识。

**使用场景:** 组合多个视角、解决冲突信息、生成综合报告、构建知识库或综合研究。

### [**multi-agent-coordinator**](multi-agent-coordinator.md) - 高级多代理编排
高级编排专家,处理复杂的代理生态系统。掌握并行处理、依赖管理和分布式工作流。将AI操作扩展到企业级别。

**使用场景:** 构建大规模代理系统、实现并行工作流、管理代理生态系统、协调分布式任务或优化吞吐量。

### [**performance-monitor**](performance-monitor.md) - 代理性能优化
性能专家,监控和优化代理系统。精通指标、瓶颈分析和优化策略。确保所有代理的峰值性能。

**使用场景:** 监控代理性能、识别瓶颈、优化工作流、实现指标或提高系统效率。

### [**task-distributor**](task-distributor.md) - 任务分配专家
任务分配专家,优化代理间的工作分配。掌握负载均衡、能力匹配和优先级调度。确保所有可用代理的高效使用。

**使用场景:** 在代理间分配任务、实现负载均衡、优化任务队列、管理优先级或调度代理工作。

### [**workflow-orchestrator**](workflow-orchestrator.md) - 复杂工作流自动化
工作流专家,设计和执行复杂的AI工作流。精通工作流模式、状态管理和流程自动化。将复杂流程转化为顺畅操作。

**使用场景:** 设计复杂工作流、实现流程自动化、管理工作流状态、处理长期运行的流程或构建工作流引擎。

## 快速选择指南

| 如果您需要... | 使用此子代理 |
|-------------------|-------------------|
| 协调多个代理 | **agent-organizer** |
| 高效管理上下文 | **context-manager** |
| 处理系统错误 | **error-coordinator** |
| 组合知识来源 | **knowledge-synthesizer** |
| 扩展代理操作 | **multi-agent-coordinator** |
| 监控性能 | **performance-monitor** |
| 分配任务 | **task-distributor** |
| 自动化工作流 | **workflow-orchestrator** |

## 常见编排模式

**复杂问题解决:**
- **agent-organizer** 用于任务分解
- **task-distributor** 用于工作分配
- **knowledge-synthesizer** 用于结果组合
- **error-coordinator** 用于故障处理

**大规模操作:**
- **multi-agent-coordinator** 用于生态系统管理
- **performance-monitor** 用于优化
- **workflow-orchestrator** 用于流程自动化
- **context-manager** 用于效率

**工作流自动化:**
- **workflow-orchestrator** 用于流程设计
- **task-distributor** 用于工作分配
- **error-coordinator** 用于弹性
- **performance-monitor** 用于优化

**知识管理:**
- **knowledge-synthesizer** 用于信息融合
- **context-manager** 用于内存优化
- **agent-organizer** 用于研究协调
- **workflow-orchestrator** 用于知识工作流

## 入门指南

1. **映射您的工作流**并识别复杂性
2. **根据需求选择编排策略**
3. **设计代理交互**和依赖关系
4. **从一开始实现监控**
5. **基于性能迭代和优化**

## 最佳实践

- **从简单开始:** 逐步构建复杂性
- **监控一切:** 可见性预防问题
- **优雅处理故障:** 预期并计划错误
- **优化上下文使用:** 上下文很宝贵
- **记录工作流:** 复杂系统需要清晰
- **大规模测试:** 小测试会遗漏编排问题
- **版本化工作流:** 随时间跟踪变化
- **衡量影响:** 量化编排收益

选择您的元编排专家,指挥您的AI交响乐!
