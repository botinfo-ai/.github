# BotInfo.ai

BotInfo.ai is a robot marketplace: listings, prices and guides for humanoid and quadruped robots at
[botinfo.ai](https://botinfo.ai), sold through partner dealers.

## Reins by BotInfo

[**Reins**](https://github.com/botinfo-ai/reins) is an open-source policy layer between an AI agent and a robot its
owner has connected. The agent gets only the actions the owner allows, each with checked bounds, plus rate and
motion-time limits, a stop that stays latched until the owner resumes, and an audit log.

The repo also holds a benchmark that grades robot connectors, ours included, against a hijacked agent, scored on
what the robot actually did. Third-party connectors graded so far: ros-mcp-server and unitree-go2-mcp-server
([leaderboard](https://github.com/botinfo-ai/reins/blob/main/results/LEADERBOARD.md)).

**Status: [v0.1.0](https://github.com/botinfo-ai/reins/releases/tag/v0.1.0), simulation and mocks only.** Nothing
has run on a real robot, and the scores are not a certification. A test case that Reins fails is the most useful
contribution: see "Adding a case" in
[docs/BENCHMARK.md](https://github.com/botinfo-ai/reins/blob/main/docs/BENCHMARK.md).

## Also here

[movement-lab](https://github.com/botinfo-ai/movement-lab): retargeting human motion onto a simulated Unitree G1
humanoid in MuJoCo.

## Contact

contact@botinfo.ai
