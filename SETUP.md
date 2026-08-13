# Final setup

1. Put `README.md`, `assets/`, and `.github/workflows/minecraft-snake.yml` in `PiyushRouniyar/PiyushRouniyar`.
2. Repository Settings -> Actions -> General -> Workflow permissions -> **Read and write permissions**.
3. You do NOT need the `GH_PAT` secret for this workflow.
4. Open Actions -> Generate Minecraft Contribution Snake -> Run workflow.
5. Wait for the green check.
6. A new `output` branch should appear.
7. The README reads the generated snake from that `output` branch.

The snake itself is functional: Platane/snk reads the real GitHub contribution graph and generates the animation. It can be regenerated automatically every 24 hours. The official snk documentation describes this GitHub Action and its `output` branch pattern.
