# fork-sync

This branch only holds the GitHub Actions workflow that keeps this fork in sync.

- The code lives on [`main`](../../tree/main), which is force-updated every day
  to match [sgl-project/sglang-torchtpu](https://github.com/sgl-project/sglang-torchtpu) `main`.
- Do not commit to `main` on this fork; anything pushed there is overwritten by the next sync.
- Trigger a sync by hand: **Actions → Sync fork with upstream → Run workflow**.
