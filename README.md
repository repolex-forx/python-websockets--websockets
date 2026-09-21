# Repolex Knowledge Graph of python-websockets/websockets

RDF knowledge graph data for [python-websockets/websockets](https://github.com/python-websockets/websockets), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download python-websockets/websockets
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 01195322d2620a44039b716cb93c108c2ca9b6b9
│   │   │   └── chunk-001.nq.gz
│   │   ├── 0403823185b272ae389da1c9182773932b4df950
│   │   │   └── chunk-001.nq.gz
│   │   ├── 157f7908c33cb540f7cf76568dde8aa6cf400504
│   │   │   └── chunk-001.nq.gz
│   │   ├── 323adef1f3000cf07617d7ee649c27c0801126e6
│   │   │   └── chunk-001.nq.gz
│   │   ├── 37c9bc0781f0cc5af7c729947ef1833c1e12b70d
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4d229bf9f583d593aa103287aee0a77c9fbc3a79
│   │   │   └── chunk-001.nq.gz
│   │   ├── 624a36cc9c1ea1369971387d7bb23533b2797350
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7ac73c645329055a3c352077b8055e6ed65fa46c
│   │   │   └── chunk-001.nq.gz
│   │   ├── bf858ac9a6e047c50614d6990a12345e1f38802c
│   │   │   └── chunk-001.nq.gz
│   │   ├── d4303a5d3e373fc8c34177c3dec1a9c75c8865fa
│   │   │   └── chunk-001.nq.gz
│   │   └── f0d20aafab027e9b99460b193dcb709872b219a5
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 01195322d2620a44039b716cb93c108c2ca9b6b9.nq.gz
│   │   ├── 0403823185b272ae389da1c9182773932b4df950.nq.gz
│   │   ├── 157f7908c33cb540f7cf76568dde8aa6cf400504.nq.gz
│   │   ├── 323adef1f3000cf07617d7ee649c27c0801126e6.nq.gz
│   │   ├── 37c9bc0781f0cc5af7c729947ef1833c1e12b70d.nq.gz
│   │   ├── 4d229bf9f583d593aa103287aee0a77c9fbc3a79.nq.gz
│   │   ├── 624a36cc9c1ea1369971387d7bb23533b2797350.nq.gz
│   │   ├── 7ac73c645329055a3c352077b8055e6ed65fa46c.nq.gz
│   │   ├── bf858ac9a6e047c50614d6990a12345e1f38802c.nq.gz
│   │   ├── d4303a5d3e373fc8c34177c3dec1a9c75c8865fa.nq.gz
│   │   └── f0d20aafab027e9b99460b193dcb709872b219a5.nq.gz
│   └── repolex
│       ├── 01195322d2620a44039b716cb93c108c2ca9b6b9
│       │   └── chunk-001.nq.gz
│       ├── 0403823185b272ae389da1c9182773932b4df950
│       │   └── chunk-001.nq.gz
│       ├── 157f7908c33cb540f7cf76568dde8aa6cf400504
│       │   └── chunk-001.nq.gz
│       ├── 323adef1f3000cf07617d7ee649c27c0801126e6
│       │   └── chunk-001.nq.gz
│       ├── 37c9bc0781f0cc5af7c729947ef1833c1e12b70d
│       │   └── chunk-001.nq.gz
│       ├── 4d229bf9f583d593aa103287aee0a77c9fbc3a79
│       │   └── chunk-001.nq.gz
│       ├── 624a36cc9c1ea1369971387d7bb23533b2797350
│       │   └── chunk-001.nq.gz
│       ├── 7ac73c645329055a3c352077b8055e6ed65fa46c
│       │   └── chunk-001.nq.gz
│       ├── bf858ac9a6e047c50614d6990a12345e1f38802c
│       │   └── chunk-001.nq.gz
│       ├── d4303a5d3e373fc8c34177c3dec1a9c75c8865fa
│       │   └── chunk-001.nq.gz
│       └── f0d20aafab027e9b99460b193dcb709872b219a5
│           └── chunk-001.nq.gz
└── blob
    ├── 005e9b4bbc4128c6506763538e00369648121b83.nq.gz
    ├── 006d5bdd51df31d97f99cdd95fb3963948bfc2c5.nq.gz
    ├── 00b0a985e1f4e445cc00b4c63b26507f313d0ddf.nq.gz
    ├── 00bce2cc6bb19fa280a6ef2b3481403e6f6ba74f.nq.gz
    ├── 00bd0ccc549da6812dc14b1b3fedeef567ac6676.nq.gz
    ├── 00dcb301042311297daed77fcf35213b32c3f359.nq.gz
    ├── 01dd5b168e4876292e7fe7547b8314b8b7032d9d.nq.gz
    ├── 020ed7ad85cd1ee515d114d503c57ffa1e74fbd5.nq.gz
    ├── 0211615d14ea0c9aaad052b6dee3d6857c1e78fe.nq.gz
    ├── 02513894ad0d038b2e6400d2517b68626f954668.nq.gz
    ├── 0252894b76b3c182a34d6ec02a8990cb6d0238ec.nq.gz
    ├── 02838b98a5335322daad566de9c0d9d0843fc49a.nq.gz
    ├── 02d4c6f01bc58c1af2bd812660aaf823a677984d.nq.gz
    ├── 030049f81520b2abd727979a0f2f6af436940664.nq.gz
    ├── 035834a893302fa6b5cf0f656820a7270c6bbf9d.nq.gz
    ├── 035f0f03c97b3788ce2854998c5aa0fc3d929c1a.nq.gz
    ├── 0369e0656548151a22b18ec614eeda592f00c5af.nq.gz
    ├── 036bc14102b64d2eccb33810f79b4a419b3fb0aa.nq.gz
    ├── 039e21174b169e04a7b970f958aca2b6f4545651.nq.gz
    ├── 03f4e972fb73d2d233425a59b78afbeb08cfb8bc.nq.gz
    ├── 044ed60431f65839650dd043c037df712812e884.nq.gz
    ├── 0458706458855d9fa48dae9b3d0eca001ebe3c7c.nq.gz
    ├── 047e7ef1c6913b90c97b78d2e43ada8f890d16ac.nq.gz
    ├── 04a7466fa24b057e04e2f867ab3cbbf15539dc7f.nq.gz
    ├── 057a17291a811ab1c4caaca4f232e86bef6c8838.nq.gz
    ├── 05947f3a07e99e3b02fe3e5fe24be3a01bc58092.nq.gz
    ├── 064a6ac4d58014436fcc3ae94d619c27695e0432.nq.gz
    ├── 06bba0922597332ffb76a2d2e7dc6ed9e8ef449e.nq.gz
    ├── 06bfe9edc36839fc0a5288c60132f2817c7b43f7.nq.gz
    ├── 06ea00efc4dff3e03e19ad8627ce5325909ca60b.nq.gz
    ├── 07274e62556b694ced9ce770955f3e43eef02303.nq.gz
    ├── 07d1d34edea22f2549cc85398cc2efdaa36bdd64.nq.gz
    ├── 087ff5f569a3705109b5bd92071f1422c920f8d5.nq.gz
    ├── 08b09f7ce3f4072572b15b90f2d4435f4cf8a392.nq.gz
    ├── 08b412d306b954c75b8d7cfd4478611ed63438d2.nq.gz
    ├── 08e87f5931a44fc0d771a682be503a6df783b094.nq.gz
    ├── 095262a2073fff410d1885545e193a4f8ac4d7bc.nq.gz
    ├── 09bafc74558dda5fef566c735a72f4856dc3700a.nq.gz
    ├── 0a37141c6cb0c6b0c940bd3b6ea20e0855c08c68.nq.gz
    ├── 0a3b8703d568a951119da2630fb387fb9fb83854.nq.gz
    ├── 0a61e7c7ee1d66f6edc2ae4ea4cf87bd8e3cef8a.nq.gz
    ├── 0a7aab6e201c0283a394691132ab0ce88c5eebef.nq.gz
    ├── 0a9818d2930c50f638ade86a2f16fafd254a13dd.nq.gz
    ├── 0ac84156d567cf2d67a8dcdd6b9446312440f473.nq.gz
    ├── 0b7c96cb91876679361b66e9aa8a355c9f23c672.nq.gz
    ├── 0b80f087a1f4f82c434a4b76738f3dfcefe26940.nq.gz
    ├── 0bcec5ded1f2b11643c9dcea91d56b8640ad930e.nq.gz
    ├── 0bd2af4f1b883d755f7a7627a55c36ced83ea3ee.nq.gz
    ├── 0bdd7fd2fa1c629ae2e8776abfabfe7ef24041a3.nq.gz
    ├── 0c5d66c92ea7eb36effa572a25fc1462f9346fd3.nq.gz
    ├── 0c7e9b4c6dce526aa5e0d37e8fd8a796f8d78bd4.nq.gz
    ├── 0d860e5379404c12f8fb4177ca4fcb6764b86f3b.nq.gz
    ├── 0dc4a3aebe0b581d2229a76ae25a110f09d7faab.nq.gz
    ├── 0dfc84253246fdabc7ec99d7c7c076e94f73f166.nq.gz
    ├── 0e698566fb99a06bfa63de388d1115b0c9f8c8fe.nq.gz
    ├── 0e7cff94894624d4c2eb4339f8d69fa354b823cd.nq.gz
    ├── 0f6fea2503fc883fb48969c9cf2edc16e907f282.nq.gz
    ├── 0fbcda60ccfc6646ed4b81d0f9681d0c6b391510.nq.gz
    ├── 0fe20dc655dd85b34a93d0ddc586b53294bfc522.nq.gz
    ├── 0ff07c9dff0e5647bc2e9ce43e3a1ec4077c9c5d.nq.gz
    ├── 0ff5598c73566731908e39df9af3cad2ac680643.nq.gz
    ├── 0ffd65233419e7988d583e2318bdbddaa3a4af48.nq.gz
    ├── 1044769627011bfa2831f4f9c34946da697e0b8d.nq.gz
    ├── 10631791626c9a39a5526d55dd392a0007b46a9a.nq.gz
    ├── 106d6f3930e05d3561ecf4871e47c0e171c66648.nq.gz
    ├── 10b0410954a8f625965eaaf1368d0bda2fcbd56e.nq.gz
    ├── 10cea8ac3566f63a830a6f49e55c5d8fe72a7f10.nq.gz
    ├── 11a452d55ca76f6678846ed8cb9c2cf34b676fd7.nq.gz
    ├── 11b13250abc627df9df414b82dce4b65bb9e6e6c.nq.gz
    ├── 120a3dd3277c9b048e98fdc22d9f9fd460b975c7.nq.gz
    ├── 12209dcdd7c9b49c31c73ba21b4b1147991c9571.nq.gz
    ├── 12b38ed06d5e925772d4d2b48397f6f07b07b264.nq.gz
    ├── 12f88b8ed0747ba5400fac646dd2fc4a3f2c7925.nq.gz
    ├── 133af05368d64ad9485cb5e104a43bf5ef179ec1.nq.gz
    ├── 134070f614b68901ce2d8a3b93278e9ecb7064ba.nq.gz
    ├── 13ae36c08e9d7fffc5e58a4c82f3989a1617077f.nq.gz
    ├── 1426cc9f3f9aaed3572e051fcea6ed5271f0a7b0.nq.gz
    ├── 14767968c97c7e203d1a7c6442cd390e9cd1f303.nq.gz
    ├── 14774b465e97f655dbcaa60d97c8a9aa72e7d51b.nq.gz
    ├── 1509a3549d7b810d0da558f6b29ee9bfa1c77921.nq.gz
    ├── 15afd4163f9eb42ccce8bb8ee60a336c85175d04.nq.gz
    ├── 15b70a3727b2eb3202fc87173ad2fc8b742cf72c.nq.gz
    ├── 15c9ba13eca93c3063d672cd69fd4b60bb5d2c0f.nq.gz
    ├── 15d53e08d229cce6ef01076d14775e4158c89a2b.nq.gz
    ├── 163d1bbaeb38f69c85242b1a11a3860741761e0a.nq.gz
    ├── 164732152f6d44a3d0994cf85f9aa7ba099223a9.nq.gz
    ├── 16bb3f1c1b206a04e51f087bfaf434b26b5e8efa.nq.gz
    ├── 16c00c1b9501b253e3e58fc18436cf9045917d12.nq.gz
    ├── 16d9c9f16041615785d510fae6f27cf349fc93ce.nq.gz
    ├── 16f92e1648321ca523bb77104b627739b670f2ba.nq.gz
    ├── 1744412031b39c2dbcd5df20b7f886552aa6c1fe.nq.gz
    ├── 175b20c589ded2c7c824a4484de9b7cf4e9367ef.nq.gz
    ├── 17ad09d26a856b48100e4b49e8fb6f740b9f4726.nq.gz
    ├── 17f8dce7e3fa9cc67a93eb9894dc6a5be48d8304.nq.gz
    ├── 1849d635a41fa879f04047fc959824a6b5135742.nq.gz
    ├── 186846ef38ae5cc1040384c30e2070ea0ca18eb4.nq.gz
    ├── 18c0e2a1151f184cfbcab07101534882175ff5e9.nq.gz
    ├── 191660553ffd2a546adceda4df23a9cfa65aa2a6.nq.gz
    ├── 19cee0e652b0cf9f8528718bb778acde35b8818a.nq.gz
    ├── 19dae44b7b9c6f8b466dbf751d6c4494a4a27549.nq.gz
    ├── 1aaca5cc6dcdb6bd17d49b452b640fe67fbb7763.nq.gz
    ├── 1acb372d4f3ae03ccaeb2acb5210f80b7ec43197.nq.gz
    ├── 1acf048bafb3fdbca5a588bb7b6c3d5a82cc184e.nq.gz
    ├── 1b51e479186ef76e6a48096d1ede22b8c1d7cdcb.nq.gz
    ├── 1b7cbb4b423854821be79900ec351af31af92af8.nq.gz
    ├── 1bcc9c90baa04078388102e07e323a6d10ae1847.nq.gz
    ├── 1bdb42723ef92c37a08871c5a9dc0ae943d15a0f.nq.gz
    ├── 1c092459d2fbea1a1864b88f4d4526ef7d59fb94.nq.gz
    ├── 1c28f73558df2582bb4e992143b7dac37224ed1c.nq.gz
    ├── 1c35e8aaea909b3dd1a16f9346cd94f5063aa17c.nq.gz
    ├── 1c372b5de49bd56e7f3710e851bbae9d2322a497.nq.gz
    ├── 1c660b95b1464a9401ecd506323158ea2cb6bbfd.nq.gz
    ├── 1ca70bdc001c3d4ad0ea352537a1f380d20f4024.nq.gz
    ├── 1d80450f9f24b15323f2b70d643520c13006e910.nq.gz
    ├── 1dab2ce4c1709a743d527ab1142c26a293053072.nq.gz
    ├── 1e6f58fad583a5dcdd91ddee2bd1bd82737cefe3.nq.gz
    ├── 1ece1f10e243ab6c37e138e2f3e0891415e7d5a9.nq.gz
    ├── 1ed4d711e925dea3cb515399f3ab5f76b270126f.nq.gz
    ├── 1ee0062af8369f2ca8f84bf711e4bca4b143e8a7.nq.gz
    ├── 1f79bb600766382596f67ff7309a76b8eb96c9d8.nq.gz
    ├── 1fbcb3ba49763008f37597a9141b5d90f09ad62f.nq.gz
    ├── 1fd41811c42f03caf3104d8f6e3352058acf4b2d.nq.gz
    ├── 202de840f359a890631d166912d3fcef1d7cc317.nq.gz
    ├── 202ff49a03a59ab707090ce56bba1ffcea1281cf.nq.gz
    ├── 205a2be50871cbc2cb85144421587a57a58bc725.nq.gz
    ├── 2119f51099bf37e4fdb6071dce9f451ea44c62dd.nq.gz
    ├── 218a489a3f53885a36a8942d4b1751fe8b0cb2cc.nq.gz
    ├── 21aad6e0261b9849926faf19193332c86e0e6176.nq.gz
    ├── 21d51371b32640aa0b0c94811eaa09b3d4b76ed3.nq.gz
    ├── 2292c5aa17ba010424523911dbb22112ee1dc884.nq.gz
    ├── 22a3b583f30150d5de0b3979a107e824fa1f07ac.nq.gz
    ├── 22ee4c5bd7b9d10f846cca2d41035fc3d8e112ca.nq.gz
    ├── 231d6b8cade343fd4a6bdbaf0210eb55d1edcc11.nq.gz
    ├── 2354db022a4a9407e3384b56c5c9327fb4ae6ce3.nq.gz
    ├── 236c493377514ff72fe974602d36de3af7a30dc2.nq.gz
    ├── 23cb040979a8c58a4f8e7993cc02de1c00bb9abb.nq.gz
    ├── 2468be85e9a66ac1bb4b26122f6e60e1c45fc577.nq.gz
    ├── 24e60897562fa0eba0092f339d41a3d00fb63e47.nq.gz
    ├── 24fb74b4e6ede2843df9dccd858e03f2e3c0d9c1.nq.gz
    ├── 2568dcf18bcace2f841ff144f1abee019e9abda1.nq.gz
    ├── 256bee14cc3f55b4a1a0321604e39f172ee495fd.nq.gz
    ├── 25a1b1ef5212dc96e6ec357891747e9f67ae5656.nq.gz
    ├── 25d2c1c45b4ae3c6ce1550cece0162d6274b8449.nq.gz
    ├── 25d5a71444f1f009a72ee7d79f4f3bd398a4e64e.nq.gz
    ├── 261057f9a085dfd84c9a29c95b09b9c5c4ea876b.nq.gz
    ├── 264e6e42d1c1c2c8b80ee09d1604e012a268b02d.nq.gz
    ├── 268b05a34a1cc0f6e9ed38dd6934e5efdac9b7c0.nq.gz
    ├── 2693d4304df50fb2dda5a8f62b1f55dc72ad67aa.nq.gz
    ├── 26bed7ec9e79abb6ce8c899ce12be92df69094b8.nq.gz
    ├── 27abcdabd890af8cb23a1abafbac3b59f34cdb39.nq.gz
    ├── 27f0baf6e457f41eea2da6094a368817d5c001d2.nq.gz
    ├── 287d2fe317e91a18abd177f17c8d0185fd484363.nq.gz
    ├── 28c990c5c9a8c8b47d7cecd6ed0999e253bf357e.nq.gz
    ├── 28d877be7d889306feffd9da68a1027c94011ac8.nq.gz
    ├── 28db931552190f99e3679ee94b7231a3c1020088.nq.gz
    ├── 29141f39a59c9ab01c6c7ae914cbed12e68ad66b.nq.gz
    ├── 291bf1fb6d0e27973327041a69a6a7c039eb3389.nq.gz
    ├── 2937a2f15e40a3b46c71d81949f8a81f11ac6d36.nq.gz
    ├── 2980a97b428f5f1d7fce99f37f13851358cc117a.nq.gz
    ├── 29a2525b4e73b788f773682ce0b88e13eafc6e26.nq.gz
    ├── 2a1fe9a78503627997051c1ad78441e1e5b4e530.nq.gz
    ├── 2a39c1b0346325de8b3c613fc7aadb8d7a06138d.nq.gz
    ├── 2a9556dd9e856622b904010f7df8bf5c92beb357.nq.gz
    ├── 2aa491f6a46478094d07d63862069474c2850658.nq.gz
    ├── 2ab9102f7a5721548053e6721e12e9091e8240c2.nq.gz
    ├── 2ac7f7092d58c8caf2b7289dc3ce334f167327b1.nq.gz
    └── 2b3a44819d27f6d909aaaacd5fbdfe06ba776469.nq.gz

28 directories, 200 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |

## Source repository

[python-websockets/websockets](https://github.com/python-websockets/websockets)

---
*Parsed on 2026-09-21 by [repolex](https://repolex.ai)*
