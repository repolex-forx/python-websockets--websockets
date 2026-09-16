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
│   │   └── d4303a5d3e373fc8c34177c3dec1a9c75c8865fa
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── d4303a5d3e373fc8c34177c3dec1a9c75c8865fa.nq.gz
│   └── repolex
│       └── d4303a5d3e373fc8c34177c3dec1a9c75c8865fa
│           └── chunk-001.nq.gz
└── blob
    ├── 00bce2cc6bb19fa280a6ef2b3481403e6f6ba74f.nq.gz
    ├── 00dcb301042311297daed77fcf35213b32c3f359.nq.gz
    ├── 01dd5b168e4876292e7fe7547b8314b8b7032d9d.nq.gz
    ├── 0211615d14ea0c9aaad052b6dee3d6857c1e78fe.nq.gz
    ├── 0252894b76b3c182a34d6ec02a8990cb6d0238ec.nq.gz
    ├── 02838b98a5335322daad566de9c0d9d0843fc49a.nq.gz
    ├── 030049f81520b2abd727979a0f2f6af436940664.nq.gz
    ├── 035834a893302fa6b5cf0f656820a7270c6bbf9d.nq.gz
    ├── 044ed60431f65839650dd043c037df712812e884.nq.gz
    ├── 0458706458855d9fa48dae9b3d0eca001ebe3c7c.nq.gz
    ├── 04a7466fa24b057e04e2f867ab3cbbf15539dc7f.nq.gz
    ├── 057a17291a811ab1c4caaca4f232e86bef6c8838.nq.gz
    ├── 05947f3a07e99e3b02fe3e5fe24be3a01bc58092.nq.gz
    ├── 0a3b8703d568a951119da2630fb387fb9fb83854.nq.gz
    ├── 0a9818d2930c50f638ade86a2f16fafd254a13dd.nq.gz
    ├── 0ac84156d567cf2d67a8dcdd6b9446312440f473.nq.gz
    ├── 0bdd7fd2fa1c629ae2e8776abfabfe7ef24041a3.nq.gz
    ├── 0d860e5379404c12f8fb4177ca4fcb6764b86f3b.nq.gz
    ├── 0fbcda60ccfc6646ed4b81d0f9681d0c6b391510.nq.gz
    ├── 1044769627011bfa2831f4f9c34946da697e0b8d.nq.gz
    ├── 10b0410954a8f625965eaaf1368d0bda2fcbd56e.nq.gz
    ├── 10cea8ac3566f63a830a6f49e55c5d8fe72a7f10.nq.gz
    ├── 11a452d55ca76f6678846ed8cb9c2cf34b676fd7.nq.gz
    ├── 12209dcdd7c9b49c31c73ba21b4b1147991c9571.nq.gz
    ├── 12b38ed06d5e925772d4d2b48397f6f07b07b264.nq.gz
    ├── 12f88b8ed0747ba5400fac646dd2fc4a3f2c7925.nq.gz
    ├── 13ae36c08e9d7fffc5e58a4c82f3989a1617077f.nq.gz
    ├── 14774b465e97f655dbcaa60d97c8a9aa72e7d51b.nq.gz
    ├── 1509a3549d7b810d0da558f6b29ee9bfa1c77921.nq.gz
    ├── 15b70a3727b2eb3202fc87173ad2fc8b742cf72c.nq.gz
    ├── 16c00c1b9501b253e3e58fc18436cf9045917d12.nq.gz
    ├── 175b20c589ded2c7c824a4484de9b7cf4e9367ef.nq.gz
    ├── 18c0e2a1151f184cfbcab07101534882175ff5e9.nq.gz
    ├── 1acf048bafb3fdbca5a588bb7b6c3d5a82cc184e.nq.gz
    ├── 1c35e8aaea909b3dd1a16f9346cd94f5063aa17c.nq.gz
    ├── 1c372b5de49bd56e7f3710e851bbae9d2322a497.nq.gz
    ├── 1ca70bdc001c3d4ad0ea352537a1f380d20f4024.nq.gz
    ├── 1ece1f10e243ab6c37e138e2f3e0891415e7d5a9.nq.gz
    ├── 1ee0062af8369f2ca8f84bf711e4bca4b143e8a7.nq.gz
    ├── 205a2be50871cbc2cb85144421587a57a58bc725.nq.gz
    ├── 2119f51099bf37e4fdb6071dce9f451ea44c62dd.nq.gz
    ├── 21aad6e0261b9849926faf19193332c86e0e6176.nq.gz
    ├── 236c493377514ff72fe974602d36de3af7a30dc2.nq.gz
    ├── 24fb74b4e6ede2843df9dccd858e03f2e3c0d9c1.nq.gz
    ├── 25a1b1ef5212dc96e6ec357891747e9f67ae5656.nq.gz
    ├── 26bed7ec9e79abb6ce8c899ce12be92df69094b8.nq.gz
    ├── 27abcdabd890af8cb23a1abafbac3b59f34cdb39.nq.gz
    ├── 27f0baf6e457f41eea2da6094a368817d5c001d2.nq.gz
    ├── 28d877be7d889306feffd9da68a1027c94011ac8.nq.gz
    ├── 291bf1fb6d0e27973327041a69a6a7c039eb3389.nq.gz
    ├── 2980a97b428f5f1d7fce99f37f13851358cc117a.nq.gz
    ├── 29a2525b4e73b788f773682ce0b88e13eafc6e26.nq.gz
    ├── 2bc63d79929321007578d3e1d96338f099fad085.nq.gz
    ├── 2bdab94645f60badc81a0cdbc7d42efc65725809.nq.gz
    ├── 2cca34fcbb49cceccde7b7e3b33962e7f4455ff2.nq.gz
    ├── 2d1ed4a2c098577bbf34c012a2a8f309326a5a84.nq.gz
    ├── 2d2e692e8d252a1d296b1f3f862f69bdf340b863.nq.gz
    ├── 2e35818f675d5a1a7b6a84e4561bec032180c1d6.nq.gz
    ├── 2f05ddc225577125ac018702cfe4de55a1aacd71.nq.gz
    ├── 2f3342aa51482b27a68c40db5566450a3e6421c1.nq.gz
    ├── 2f73e2f8753bdf1f9bb3a9503cf3c27b44c70e76.nq.gz
    ├── 2fdc59f0fdae4d28fdcf18b6f9edf8d62ad22f01.nq.gz
    ├── 309ce152ddb5d6407a29bc06e1edbe0a273e45e3.nq.gz
    ├── 3152f174ed2a8c771233047375f762ab55dd2997.nq.gz
    ├── 317dc4d9852df72ba34e10a6f61d1838cbbd969e.nq.gz
    ├── 32b79817ae754f024a509f2f6d68c8e355b5b6c9.nq.gz
    ├── 32f1465321e535b3aef7fdd0d961f2e7095265ca.nq.gz
    ├── 3328b3b5e55d65f7ac315ef0f8d680e5a9abe6d5.nq.gz
    ├── 3417124758a9a889de4845fbd821cb5381b396d4.nq.gz
    ├── 34a470661c903cecb4a5333d4c521173a05957d8.nq.gz
    ├── 36e855029d705e72d44428bda6e8cb6d3dd317ed.nq.gz
    ├── 37d892a28b447e243262757c225204a48d60286e.nq.gz
    ├── 384caf0a2c16228ed01c911ebfc751109377a297.nq.gz
    ├── 391f7580fbfb9e4a85406f5fce13bce66a91c774.nq.gz
    ├── 393e0215cd85151a06226e42c74aef117873ee81.nq.gz
    ├── 3a7a0db49ee94a31fb5e270c6817ea676cb5b200.nq.gz
    ├── 3ba13e0cec6cbbfd462e9ebf529dd2093148cd69.nq.gz
    ├── 3cad8b1f2c04ad496b2c01afa47ac4ee17b6e9f6.nq.gz
    ├── 3f6f7dd90e065bd1271348a50732d2750b1573cc.nq.gz
    ├── 3fdffb5017497a9782c62500d9f84a5122297dcf.nq.gz
    ├── 4069e39670c982bba4d221dd88ebd5910041c084.nq.gz
    ├── 41534391168f67efbe5f56b96aebfeb6aa2154a7.nq.gz
    ├── 42100fade9b2ab8abcfd6bb3876befca893affdf.nq.gz
    ├── 43970a7cd678fbace6afba348ea99717b99723c6.nq.gz
    ├── 44d89e00b48e59a6f317c547d179a1c96ec16077.nq.gz
    ├── 452d2fb34dc45577401321ce76d6a030d2e49597.nq.gz
    ├── 494f56a4465919c0d65815350e2eb9db148c5b63.nq.gz
    ├── 49d2a40feee03ebcda5e05dc43eebeb27ccecab7.nq.gz
    ├── 4a7dcd5ab162f01c56b10afceafa6dd8af199cc8.nq.gz
    ├── 4b3ad9b13722f48827fa1751b91920db84a69d45.nq.gz
    ├── 4b47db1ba56797f86b9403fed1035ee99874c1f5.nq.gz
    ├── 4db014337ca6c1b7b36444e86e83d4a839493a1c.nq.gz
    ├── 4e6ff952bda5ce229e2005d45d032803c420e030.nq.gz
    ├── 4e843daab34f865b012ec41408c2804b6ddce9a5.nq.gz
    ├── 4f34c06284890ca871a26e0796f041092405fa7a.nq.gz
    ├── 504c830efedb3ebad1d81a68b45f8044c3df4a1c.nq.gz
    ├── 51bfd982be7bac755c318376e79b6f7d3dfd91ee.nq.gz
    ├── 520ba92a973eee19016b5dbf5359b78c878d807d.nq.gz
    ├── 524fb35f832eba51a76b876bfba8b1a9a86db6fa.nq.gz
    ├── 52629a9891a7af7decbc7b3fe6ee796ad1aaf060.nq.gz
    ├── 5290072ed28c6b804295c6028e300e958d515fc2.nq.gz
    ├── 546f70a6f9f2ea12d3112bd13fc164e6481c79c2.nq.gz
    ├── 55a9977ca4005a94b5b833df6efb39ded822f61e.nq.gz
    ├── 56c98196acf6a7d8399caec8cced954cb2b9f68d.nq.gz
    ├── 56e2621141a06c14e3fe6db0a57cc5ddd4c01c6e.nq.gz
    ├── 574e053bf39630c38711f595daa9be5dc1337b7a.nq.gz
    ├── 575c84519c35b3aa25481a5a3abf45b9719df630.nq.gz
    ├── 58f61af0dd478f402b24ce87e0440b59cc646678.nq.gz
    ├── 59a51b6e33810bc0bc34b7d2ea6e47b0fd8be78b.nq.gz
    ├── 59e0cea0f4393082668833c7a488eb87576a732d.nq.gz
    ├── 5af73eb0cf58fa4246e9a274a2b1ef36f301eb9c.nq.gz
    ├── 5c5ca1bd297e53afd03c1c471d9cc6b2543f7dfd.nq.gz
    ├── 5cd673d979526361b5bf01b315b14edb19e56150.nq.gz
    ├── 5d61ece22a75a759aed8e52af280eca28d35d6bf.nq.gz
    ├── 5e78e34479224d0332b165badd67a8933e0c73db.nq.gz
    ├── 6202fb14a0ea9fd296918647d818c3e5dd76d30e.nq.gz
    ├── 62250b07f65bd5333469e280736100bb972c4aba.nq.gz
    ├── 62ba9d843ffc665cfdf1b3678fb0d02603de1e5b.nq.gz
    ├── 6348271867d4625cec188b34001b41d922b9ead4.nq.gz
    ├── 64334f20fb31c05a7f8fbc724931313bbe23bcb5.nq.gz
    ├── 6596c9f32f860cc6a78fda8c8f8afbfed57b9f68.nq.gz
    ├── 661ae64fc47962d7a6d0428a23c193e7c73517df.nq.gz
    ├── 665f478ac9377174ca5c912f5939f81bdd8db3d7.nq.gz
    ├── 66b0819b216406c1d70adfce760b03c332c770c1.nq.gz
    ├── 66ebbe3ffb302225e625f027dc79d0590e85793d.nq.gz
    ├── 6761620dd1cba3145a7e4bbb20b4da30fe08dc5c.nq.gz
    ├── 678fcfe798ec7c25c94680caa0995864b9c2f389.nq.gz
    ├── 67aa0086d54f3dd0fd230b6ff6fb68bf502e9b09.nq.gz
    ├── 6906720a49d3a83b92b3386ebe57aed2f2e488bb.nq.gz
    ├── 697163c9994b67d65dbdef5d00b841ca20eb7eab.nq.gz
    ├── 69b1a8d372837b0a297177f8353a335375cfbd49.nq.gz
    ├── 69bfd5e7c74a8bff0621a345f273f69b39bb263a.nq.gz
    ├── 6a54d0b6caeb5288cf4248c1b4c7d299deee8a00.nq.gz
    ├── 6a7157c010720733ca42d363cd810c354bf9d221.nq.gz
    ├── 6b783f90c50201bd8bb3ad89bb9670a2f2474e74.nq.gz
    ├── 6c09a13fac9bc35baef9b899d7c33860c7f993d9.nq.gz
    ├── 6c45bc749e7540d6476ff4f6289f824b72660c50.nq.gz
    ├── 6cbdc9c79f784a538f6470cdd0bca3af53c2c258.nq.gz
    ├── 6d5d66d9aef166965dc66a592ef5298ad2a21da3.nq.gz
    ├── 6dc827f72d70f1e63a542ecfc7764d43a8a7cd47.nq.gz
    ├── 6e3918ccae60e096d8ac491c653911f85abbce22.nq.gz
    ├── 6e4518497c80e89e5ddd8a8b4208638041c4aa59.nq.gz
    ├── 6e81199fc6265cb5f14f991cb220888465c68a21.nq.gz
    ├── 6ecd175f87be054d8b4ae04e910d688f2a0d340c.nq.gz
    ├── 6ffa899695637829dd5d3c7b58c68683000fc35d.nq.gz
    ├── 71ad86909e44af12d80a9edce979499164f7e445.nq.gz
    ├── 72c7dce37c7acd3adff80219e16c1e90c9173d3f.nq.gz
    ├── 73825868839e6a65ed84cc41e29562b8b442c4c8.nq.gz
    ├── 7488a5397f39420d386d3dd3f7b6e22c7f4ea406.nq.gz
    ├── 749d9d482d2f01563c0226f96042b03b3b3521c7.nq.gz
    ├── 756ad03b6522647ca131487ff837850c31befbab.nq.gz
    ├── 76a664d91b12dead5d4fc196a62095172986fc17.nq.gz
    ├── 76af61122cff8a295f8d42047440949e5637cb46.nq.gz
    ├── 76cd48623c46eb530d107925ac1f97c986402666.nq.gz
    ├── 76ce9c2d7a554b113ad06adfd82ec9eecf4b327b.nq.gz
    ├── 76da1c2fb1aaa723d31c769eee5a78768aa26aba.nq.gz
    ├── 7716e7a2b2896d598b4f3137c55a6e5e565201cb.nq.gz
    ├── 77a4fd1d85ebc29efb3f0b0e0a0e636b06fda6fc.nq.gz
    ├── 798d595db3ae8613ded5193df09e6aa236c2c190.nq.gz
    ├── 7b6ca58dfb6d2b74a4dbec8c606c0889d7e56e77.nq.gz
    ├── 7c022066fd01b9eb7287428817dab928e36cda39.nq.gz
    ├── 7c4ed2f3e0a84255c16ac03a98a08aec51850048.nq.gz
    ├── 7d5447ac9d9960cbf2f03358ed2b7a2719bf71b9.nq.gz
    ├── 7ea3a5e5fbda3c57267692270ac30fe9d01200b5.nq.gz
    ├── 7fc4ad4b3b4a7d58323ea4b19dea4d7836bfe707.nq.gz
    ├── 80f80d51b115134c79329b69f02c47e3906e0f59.nq.gz
    ├── 816afc54159fadcd11927b0e9650a38aff734623.nq.gz
    ├── 821576020ee8ad2984226b1a7115c1ad9b5f669b.nq.gz
    ├── 841dccaa47eec230f1e3f6bdc09d1d49b9a93fc4.nq.gz
    ├── 84c3167583727707591d187ff475d68e900b9c19.nq.gz
    ├── 84deb97273216485ff091cc30a011d5d5b525701.nq.gz
    ├── 87201c9e4acec0b9217b4c7a102eea29d3cb04c2.nq.gz
    ├── 880ef4a2acb42bcf13a3f9aa532970160db14ec4.nq.gz
    ├── 88640e66040d4fa60f88611662e82b9bfce0958e.nq.gz
    ├── 8a285e92e5680235e7196d234b92fb383eb564eb.nq.gz
    ├── 8a4981f5f36fadbeb2d5999e3eddfc166f288d6b.nq.gz
    ├── 8ccef7d390d24183c9a1c1c16531e7aaca9035c5.nq.gz
    ├── 8cfd7b4b5694e1efa05ac363f58839eca3ec1413.nq.gz
    ├── 8df63ec8f4b3aa3e0f0f274c317fec6bd16cd15b.nq.gz
    ├── 92c6629b5110e7d14b8dd68e0dccf9b6ab2f031d.nq.gz
    ├── 939737b4523ade2d83da695509ff7fd5757975aa.nq.gz
    ├── 95125773d4c4c0ea15da260c58eed4e4111be60e.nq.gz
    ├── 9ad2ebea4b71d57cc4366d8583a2f64c3bb15e58.nq.gz
    ├── 9bd5119fb8bc5a4d620a5b81e1c18119133303fe.nq.gz
    ├── 9c8bacea0791d3eac621c320f8d6ba56f5bfb4f7.nq.gz
    ├── 9ea71c58e4773e3f0ff0b0e8cfabf01f4de08063.nq.gz
    ├── 9f734504a73b9a886c84be1a3ed92105216b76e9.nq.gz
    ├── a01f91703c6e6e27d91312a73f0c739499caf2a9.nq.gz
    ├── a073139e3311d3bc4e2997e15542cf1f3ddfccdf.nq.gz
    ├── a1bb663b50d39fd473e8743ad6150fc9ab22b778.nq.gz
    ├── a245929ef4f326ccde789c4ce3083a93da9a690e.nq.gz
    ├── a2536d4c0e2e38df2f13daa9360fded0607bacad.nq.gz
    ├── a262fcd791bc66a1ad0ee9389faed1c62c69e2be.nq.gz
    ├── a343b37bcda58da54d81002e4a2d3b9fe6f08f76.nq.gz
    ├── a4e7ad3479fe08a60935be0560fb50b057bb113c.nq.gz
    ├── a55057a0d5c13eb0118ee91d0226ebd40d6b4627.nq.gz
    └── a7c8a927e177d36f6a54bcc293dc853e2e15e736.nq.gz

8 directories, 200 files
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
*Parsed on 2026-09-16 by [repolex](https://repolex.ai)*
