# 江西服装学院 — 新生八字趣味解读 Skill

> SkillHub「宝藏母校 Skill 大赛」参赛作品 · 江西服装学院—新生八字趣味解读Skill
>
> 不是算命计算器，是「人生财务诊断模型」：盘面由算法产出，引导由 AI 按
> 「财管/K线隐喻」框架现跑——把八字翻译成一份"出厂财报 + 年度行情"。

详细说明见 [SKILL.md](./SKILL.md)（含指导哲学、知识库案例熔接、解读框架、实战示例）。

## 快速开始

```bash
cd calculator
npm install
node dist/run-chart.js --year=2005 --month=3 --day=12 --hour=8 --minute=30 --gender=male --ref-date=2026-08-29
node dist/dump-text.js --input=chart.json
```

把 `dump-text.js` 的输出交给 AI，AI 按 SKILL.md「解读框架」产出第二段引导。

## 作者

LK666-A11Y · 江西服装学院 · 财务管理 2024级

## License

MIT
