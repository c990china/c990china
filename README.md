# c990china

文档 / 工具控。喜欢把重复劳动自动化，顺手给开源项目提 PR。

## 开源贡献 · Open-source contributions

- **[caveman](https://github.com/JuliusBrussee/caveman)**（作者 [@JuliusBrussee](https://github.com/JuliusBrussee)）：PR [#699](https://github.com/JuliusBrussee/caveman/pull/699) — 让 `evals/llm_run.py` 具备容错能力：单次 `claude -p` 调用失败时保留已完成结果、写出 `results.partial.json`，而不再丢弃整轮评测运行。该修复被 **3.2.0** 版本采纳并署名为 **co-author**（合并于 PR [#1199](https://github.com/JuliusBrussee/caveman/pull/1199)）。
- **[rimes](https://github.com/scholay/rimes)**（作者 [@scholay](https://github.com/scholay)）：Issue [#83](https://github.com/scholay/rimes/issues/83) — 报告 Windows 下 `state.json` 丢失后卸载崩溃（TSF 注册残留）的高优先级 bug，并附实体机复现与修复补丁（PR [#84](https://github.com/scholay/rimes/pull/84)）。维护者据此在 **Windows 1.1.1** 合入恢复逻辑并点名致谢（补丁由官方 PR [#88](https://github.com/scholay/rimes/pull/88) 接续重写）。

## 提交 / 反馈记录 · Submitted & reported (未合入)

- **[WorkDaddy](https://github.com/babygoton/WorkDaddy)**（作者 [@babygoton](https://github.com/babygoton)）：PR [#387](https://github.com/babygoton/WorkDaddy/pull/387) — POSIX 守护进程锁身份校验，修复 PID 复用导致的启动死循环。**已关闭、未合并**（上游已在后续版本自行修复）。
- **[WorkDaddy](https://github.com/babygoton/WorkDaddy)**：Issue [#388](https://github.com/babygoton/WorkDaddy/issues/388) — 反馈面板点升级后安装程序卡在中间无法继续。**已关闭**（维护者称已在最新版本处理）。
