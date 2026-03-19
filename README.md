# Repolex Knowledge Graph of square/okhttp

RDF knowledge graph data for [square/okhttp](https://github.com/square/okhttp), parsed by [repolex](https://repolex.ai).

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
lexq download square/okhttp
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3e14ab4438cff64e16d7ae14ceb79ed59643a280.nq.gz
│   ├── dataflow
│   │   └── 3e14ab4438cff64e16d7ae14ceb79ed59643a280.nq.gz
│   ├── lsp
│   │   └── 3e14ab4438cff64e16d7ae14ceb79ed59643a280.nq.gz
│   └── repolex
│       └── 3e14ab4438cff64e16d7ae14ceb79ed59643a280.nq.gz
├── blob
│   ├── 018d0fb52f42d44f8ec90c2e0e0c1332b1810dea.nq.gz
│   ├── 0405c043884cbd39cc91588a4b7dc629e3dfa532.nq.gz
│   ├── 05380e27e164485a175e4aebcb8f3321c875e73d.nq.gz
│   ├── 067726354f94d56f118ca393e42202c8e3faea77.nq.gz
│   ├── 0a29d4b1ab665c67328bcf7e4bcf27620fb60c48.nq.gz
│   ├── 0b26b8467bc228aff3891c6049cc88a7ee82da1f.nq.gz
│   ├── 0bcadce36e296a55dfbc800c9f4a3c0281f84f90.nq.gz
│   ├── 0f0cb280e685eb07ee152ea6bef6012fe9231cc6.nq.gz
│   ├── 1055e4f09fb2e89d74840bcf238c265db682f6cf.nq.gz
│   ├── 11d7239050659ede75c2d1c73dd995559afe8e0b.nq.gz
│   ├── 1334dfa69764d8106ce2d0d8d6370d21247b6106.nq.gz
│   ├── 1371262e6c5a3410e6a3e8f08f92f8963ec0b204.nq.gz
│   ├── 16f97c41755eaceec72c8849d19c3f2512a79468.nq.gz
│   ├── 1982a8ac4bab92b40dc5c4e551cb472cfc346ec8.nq.gz
│   ├── 1ad36898e86bf1a07845f0d5b6ca86bca390ce0c.nq.gz
│   ├── 1bfeb1de4e496584ff1d6a66ba64cd77df77c4e9.nq.gz
│   ├── 1e67968cd5f24cf5eca908c25fd2526088a26713.nq.gz
│   ├── 215e968dfe386a5ec2718fde29c423b6297c5523.nq.gz
│   ├── 226a3f3d65cd0b3400670c3fc044f85d1bf25045.nq.gz
│   ├── 22e6a95916a6704cc59a08d6589664cdb626166b.nq.gz
│   ├── 252f6ac85c087a2cd02d2a3552206aa852d2b541.nq.gz
│   ├── 274bf9dd4885bbe8ef2abd1044a286ea3015b19a.nq.gz
│   ├── 2af596ee8355255b94d231112af2c1d789856af2.nq.gz
│   ├── 2bc1d68e427ee33b49890fab73f23c980f3c744f.nq.gz
│   ├── 2c09596ff7bdbefcaffd0164de5c6ced52b0dd40.nq.gz
│   ├── 2c40f9aa8c6dd64da28fe1255ae1f4dc80f573a6.nq.gz
│   ├── 309ab7021106606e23978bc5f1fd12f95c97df0c.nq.gz
│   ├── 354f43d1d1ee7172a2717de17aa2035c8bc34df6.nq.gz
│   ├── 3d53f484886b19fe29cb0fa939affa0f6cf43c7e.nq.gz
│   ├── 41724f0787dabbbb5957489859f9036a39f59ff4.nq.gz
│   ├── 42b70b98063adcfaf4cbc8d0404889a1886f3d77.nq.gz
│   ├── 447d0334322372c911652439abd13847067ef850.nq.gz
│   ├── 44d4ea2bfaf03091c8ddb351a870923d36c1d657.nq.gz
│   ├── 471539a4672c00d959460794b0e82a3ecc5a7fae.nq.gz
│   ├── 4a2dad403a754b4acdcba3b48dfb48d3eb99d2d4.nq.gz
│   ├── 4b78fe23ac89d3bf89624fda827e3516890c407f.nq.gz
│   ├── 4b8786d2298fb738ed6251e54d69d8b174cefe18.nq.gz
│   ├── 4ce80a5ebb6dcda9304530dc088fee0f7ad8237a.nq.gz
│   ├── 4eca172d3558a79d7530878cdb8e4e6547ff3a9b.nq.gz
│   ├── 5260b87c4935aadffa59fad69b4f68c8351cff55.nq.gz
│   ├── 5335c2bce895d039d0395cc24e58466ace8f0a5d.nq.gz
│   ├── 5d04a1a67ae3fd4b30a3731cb0ef72f5eb482db7.nq.gz
│   ├── 5d9a49b3a2b4f4b109257638f7a98191399da64e.nq.gz
│   ├── 5eb6b7645576cae6bbb2745216c649baf914dced.nq.gz
│   ├── 5ff1a14d5f331068a59dc145193df864cab1db7a.nq.gz
│   ├── 609b0f32c0ebebf5c35a37e1ac056fa1e30498f8.nq.gz
│   ├── 636acbde11adc0462cf402bea43afbc3c861e602.nq.gz
│   ├── 69b2d37e94697d2d6c4c310ba9efc403e70d5642.nq.gz
│   ├── 69e86568f9036b1fc72f3a6d6763424fb5bb7e7b.nq.gz
│   ├── 6bb9cb3a9c17921fe8f687be037d5ecf929d86a4.nq.gz
│   ├── 6ca375691b6e49b5a67e5f3bf151e5a4c24e07fe.nq.gz
│   ├── 71c3cd0f21c544db203a5aa2133d82d30ead699a.nq.gz
│   ├── 7371f2e3dc159cbf21a62867b4598d5c7672bdb8.nq.gz
│   ├── 74af6fd533202145dfb22873721472239c097d45.nq.gz
│   ├── 74e6db01a6f4b9fc72afe79318d316072e27e30c.nq.gz
│   ├── 766e69c60e345e066394490fb27d8dddc80b29f7.nq.gz
│   ├── 76701c4c92096a373d169ba665770b7c89b6ec2a.nq.gz
│   ├── 7725f3d155a1c8f46110537ac36560c31e7a556e.nq.gz
│   ├── 7769867d9d31cb87b442cdc6d76bbf637c5f2d27.nq.gz
│   ├── 784f221caf83c7b22d5af716ffb2af11d7b14d57.nq.gz
│   ├── 788b301adb1d76a6f38b4b3e26d771e75be133cb.nq.gz
│   ├── 78c9691e6fd22906bc90014607b7465bf581515f.nq.gz
│   ├── 794af42b68a71e52bca5f35d720f2e6ffe392a2d.nq.gz
│   ├── 79cd0206f5fdef8107e2ac444c52160e9cf65003.nq.gz
│   ├── 7b625961897bc80771a2628dee25b588c5c2249c.nq.gz
│   ├── 7b990496dd2b7254334bcbc60a3e49a4454000a6.nq.gz
│   ├── 8210318276397db05f2b24e505a200cfced27ec9.nq.gz
│   ├── 8969f472364b0cbd344ee2c39d8ab595b5e1cc64.nq.gz
│   ├── 89f31da204e9a77d3e92287350a75a69630f527f.nq.gz
│   ├── 8b4532070475b369e4010515a9504be4370371e4.nq.gz
│   ├── 8f48bcd24425147f8ee38b8710ef53b34df65f9e.nq.gz
│   ├── 90c7f9057ba2a309906ef25dfa1c0d653bf5f063.nq.gz
│   ├── 91ed8229bfde1a728cf8c757a1c95447b218f138.nq.gz
│   ├── 95653b92913b76d9893c502f5b79e75d46cec1a5.nq.gz
│   ├── 95c5ac5ee61d40a7d6ede857d834fdbee88e9c5f.nq.gz
│   ├── 95e64416798c74accad9baaeb5d12a91f70a701a.nq.gz
│   ├── 98efc449710d13d89927f99c125057ddebc2d215.nq.gz
│   ├── 992b2ae4197384fd3bc1f9711ac8b970a0c61e02.nq.gz
│   ├── 99ddc6dc5640fbc7eced13d047a43bdd206cb844.nq.gz
│   ├── 9c5b008a20f71403bcada24ffe6cbd8be40fa864.nq.gz
│   ├── 9c8336289031c5228bff77758a079466ce76d1e0.nq.gz
│   ├── 9cbeaa73f12b19ed030d1ca9ad98b04c41b3a4c5.nq.gz
│   ├── 9eff91919a6ecd2ef0ff30d86c7f55f3c355e125.nq.gz
│   ├── a08773f6f67f8dd128f64cb78c4ff9c1f41e6dea.nq.gz
│   ├── a3547003a5588e62983361974527580a474de2e2.nq.gz
│   ├── a3ab3a4460d217589dfc330c44a89003c21d5a31.nq.gz
│   ├── a505419248c2669a494f80188b9cb68a91956810.nq.gz
│   ├── a5d39b30a4cfb1cde73b8f901e5672ec32ebe828.nq.gz
│   ├── a906fc7cb91d76a0235ec8666572f720ba73bccc.nq.gz
│   ├── a92db9ee14571862360feecceb0b123bfc308df7.nq.gz
│   ├── a9c6940069f1dec14d417cdcfd2649ca6b29c922.nq.gz
│   ├── ac6bac4a0b1d4539b31f14f61313c79670282a90.nq.gz
│   ├── ac71ec215ab97721d17376c9a7f43f1c3f961a9b.nq.gz
│   ├── acbfdd5c164bf863aab9f9c9687e7c9e472fb523.nq.gz
│   ├── aceacd18459f31121ec4530d63a403cf3b63b91f.nq.gz
│   ├── b0f23f44cd67b62a58f39a148837edb5809682b2.nq.gz
│   ├── b34bd9128cb91ec0566ced9ca2c5ec9bcfb2dcec.nq.gz
│   ├── b3e2369b79544374a3b842329d2f5d1c827a02dd.nq.gz
│   ├── b4d2c7c07dcb7d30cc9e8a5f5c2bc2159c077033.nq.gz
│   ├── b5427c58067331d8181d39b566719acdff51d020.nq.gz
│   ├── b95d01381811772cf95c36f85b0dbcd65fd939e2.nq.gz
│   ├── b97e6d39f51a1d077a76b59c0201978afe5cf25f.nq.gz
│   ├── bac274419883859728b3f2e74c2b150e4b115356.nq.gz
│   ├── bdc98d1c2f85fd55b21294d3b926a47d6c110c54.nq.gz
│   ├── be7c17376de9f34051a8f6871093a644c19f3cc1.nq.gz
│   ├── c0e0fe65ad6cfbb72710b6aa36ddcdf45dad0ddb.nq.gz
│   ├── c32b27aebba50a15508d54c7eb96fdb49ffa1b0c.nq.gz
│   ├── c3ca8f1163b2a0497fc9cbd1fce4158b83263eb9.nq.gz
│   ├── c46921fb78a7f1fdedf973fc17df92c731456509.nq.gz
│   ├── c585255780fc83ecfa74350ecb5245a4a9f9a21f.nq.gz
│   ├── c9678308b19ae3abcbf3df2907297617da003286.nq.gz
│   ├── ca6bb59f2efa510ac343272e707fb6c88b93b841.nq.gz
│   ├── d3a32e1172c94885472d4f22fb5e24a62b490813.nq.gz
│   ├── d408bfec0336ee774507701190f466c9521815b1.nq.gz
│   ├── d5884b18480a1648263d516f96efe3da38043bd3.nq.gz
│   ├── d5f0f4f9b8d5867267b91be531322b945ed0ec38.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d7d00c4a936dc82a711447ad05af6026080a1a04.nq.gz
│   ├── e0aef149160ada1fca809b8d0b0c8be1eaff4e80.nq.gz
│   ├── e16e176a169369de254ebb53fb58b12f6e624373.nq.gz
│   ├── e2438573332b141efe3c028fcb6ff77b75126fec.nq.gz
│   ├── e3574b739d441e1ba02d30c225d92d320088ca82.nq.gz
│   ├── e824fe233cc7ad66fec5e36f8b750b6b1a14b37c.nq.gz
│   ├── e933c177c3fefac4e1ded0c26c650c14c54862cc.nq.gz
│   ├── ed43e194a70cbb563af4680e3eef04ccbca0ab10.nq.gz
│   ├── f1decc8df04fd9eefe3050940d238246effa39ee.nq.gz
│   ├── f30ae985734198f7251a51d883f18d616a53a5c5.nq.gz
│   ├── f78592fcbfdead65517e92bc3cbb3d4ee0a6b15d.nq.gz
│   ├── f7fcb1ed2a613b3c779e97772f716221a68a30f3.nq.gz
│   ├── f95303ebab22467426fafaf1b0a6ef1686ca2e3e.nq.gz
│   ├── fb4a7048d33eee0b251b2f3310175bc44aaf970a.nq.gz
│   └── ffe6f54b1045b32aa62cacdd2700def8ee1ed290.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3e14ab4438cff64e16d7ae14ceb79ed59643a280.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 142 files
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

[square/okhttp](https://github.com/square/okhttp)

---
*Parsed on 2026-03-19 by [repolex](https://repolex.ai)*
