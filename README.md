# test-update

Test repository for the reusable workflows in
[javiertuya/digestabot-workflows](https://github.com/javiertuya/digestabot-workflows).

- [`digestabot.yml`](.github/workflows/digestabot.yml) calls `docker-digests.yml` on the
  Dockerfiles in [`dockerfiles`](dockerfiles), one per image, some of them deliberately stale.
