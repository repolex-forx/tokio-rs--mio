# Repolex Knowledge Graph of tokio-rs/mio

RDF knowledge graph data for [tokio-rs/mio](https://github.com/tokio-rs/mio), parsed by [repolex](https://repolex.ai).

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
lexq download tokio-rs/mio
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ce39a6be2cc739165daaeb10cce609b9b77242ac
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── ce39a6be2cc739165daaeb10cce609b9b77242ac.nq.gz
│   └── repolex
│       └── ce39a6be2cc739165daaeb10cce609b9b77242ac
│           └── chunk-001.nq.gz
├── blob
│   ├── 0036445a6d81138818dad978371a4a20da34e057.nq.gz
│   ├── 01f6a8975df79a9c2181b52d3330e766c0e454cd.nq.gz
│   ├── 0893b0fd347bed4b97927509e3949e111a4e6c29.nq.gz
│   ├── 0b9497a90763554af8311d5cbfce440e429a832b.nq.gz
│   ├── 0c61db94a61c20dba68c5d3560f9f6bf67fd3a6f.nq.gz
│   ├── 0c67eb56f5b32db4d4fb63e656705d626361c368.nq.gz
│   ├── 0e1d17cf7642e426f7936fa9e834ae1ea162b66e.nq.gz
│   ├── 103aa01a7b8dbca142da86a3aec17f22b371501c.nq.gz
│   ├── 10d3e27c1517a51c35d39fa8d256f0dce1b09578.nq.gz
│   ├── 13799c3b75f4ce9fbc739f862f08f6833514ad1f.nq.gz
│   ├── 17a97d4caa5987d2b9933b0a707c6e3ffc6c61de.nq.gz
│   ├── 1fc1ceb9298e384c855bb23d36165ce61f8bde33.nq.gz
│   ├── 2010e8ebb61bba3a54abbf57140d64db63ed9d66.nq.gz
│   ├── 244f40455e7b746fbda90bb92111cdb011ca3e4b.nq.gz
│   ├── 2b53d785ab1371d22d0337b5b69afb5e68f2a760.nq.gz
│   ├── 3516413824bd717ba0c5e8b01b9903da6a1c673e.nq.gz
│   ├── 3a9e59ac648971f4e97479e9ec22effe4ce2000c.nq.gz
│   ├── 3d5e7cfad15f57b3f36102cdf58d58c5e37e20f5.nq.gz
│   ├── 3f8367987d40b1585a3196a9246f1bd3100c87d1.nq.gz
│   ├── 446781aeddb4d893dda7ab7e9f14d0a54aed07b8.nq.gz
│   ├── 46a0a1eee478655d3b4d7df765d614fb14fa0438.nq.gz
│   ├── 4f7326ab8e27b07ef88314842e15a45b1c5aafe2.nq.gz
│   ├── 5b9ac0b6245d49dd0a6dc1d71fc44874e3c7504e.nq.gz
│   ├── 5cc235335eea40dd7a9ffb7d65245861724a57ce.nq.gz
│   ├── 619f72d42a0024f49e587940925c6675dcabf069.nq.gz
│   ├── 66656d0e59b91b409928455e3246e95fc36c24cb.nq.gz
│   ├── 66cb23c4db49b549a35c01d0c88bdefb89e5f3f7.nq.gz
│   ├── 68626746a26926e80aa3b24a11ce56c75586e7ae.nq.gz
│   ├── 6a48b6941d72d35d74352644a7d5dd6cebe69e9e.nq.gz
│   ├── 7006576cba13f1dce34675548a994d1d4387e8ea.nq.gz
│   ├── 7282ce4dab01355e033af5a8a81ae4c5816be50e.nq.gz
│   ├── 73d5b7fc83f121b6e729502c59e6b8da5d121a72.nq.gz
│   ├── 73fea07313735845d1203fdeee717f0205d3fd7a.nq.gz
│   ├── 74e281751e26a9d5572de044a5ae5760dd04e175.nq.gz
│   ├── 7666f9ff2d8ddd0f653e1575fc1defc9c5a995a0.nq.gz
│   ├── 7a54daa01c8af6a5eb9d72ac5252368a43d6bcf6.nq.gz
│   ├── 7b3d86cd82a0ea829f8296e0ddf5bdcffac74e44.nq.gz
│   ├── 7dcdc833c40410d5fcd6b2a97933681e83107052.nq.gz
│   ├── 7ea7e322f850e59ced3ff75be71c41f1e5ce9d95.nq.gz
│   ├── 80a09f63d7065fa8d3e7369dc9faef71c0e2ae1b.nq.gz
│   ├── 87e269fa3b0b99e2e54946bde631e3178ad4017a.nq.gz
│   ├── 89d74b1a2b9a4bc8b4583e67b7a530c310189207.nq.gz
│   ├── 8a12a90aaff0657d0424068c2b6103ff2c722e7b.nq.gz
│   ├── 8e17f82ee55254fd46e5be720dc0cc03f3e0379e.nq.gz
│   ├── 9298acf768868fc42e11b652820770920f345fca.nq.gz
│   ├── 92fdb4c163e71337e8a256897e726c7396534bed.nq.gz
│   ├── 94af5c10e8e2b5b49aeef6bf867c91b90131477b.nq.gz
│   ├── 9502cbce07d2774dd76d3170199725418d682036.nq.gz
│   ├── 987d04c8ae1d8db564135fbb2e8b1412ec0a5f81.nq.gz
│   ├── a104bcda14b4b3dfcd49569514aef22168a5d23a.nq.gz
│   ├── a255972a54430bd54f59658cb65ed77b435cff35.nq.gz
│   ├── a3b97a12450211650dccf7b3eeb5c06fbfe23019.nq.gz
│   ├── a59389676843767bc0df0f5a76694e19d5d64696.nq.gz
│   ├── aa1c6220fee4dc77df704400a0d62bb916c44b20.nq.gz
│   ├── aaf77c2950fa8aa1d2e3cc6ecb2c00b850a596ea.nq.gz
│   ├── ac1542720276e858fb86f18845a97c65baaa333a.nq.gz
│   ├── ae8b7838321249b7121f11e8e1cdf30e66254bfe.nq.gz
│   ├── b0a7cb78dfb7c5354e85290645c35c330fa07e91.nq.gz
│   ├── b45c556c6ce88f8282de609f1f5db72cc5ece3c6.nq.gz
│   ├── ba533e1c6a590cdf8131d520e51a839e05304112.nq.gz
│   ├── bac01fce70331deb8dccb00d815cda5671d976e6.nq.gz
│   ├── bae9cee8dd335b1ddf95faafbc4c6d78fa9c570f.nq.gz
│   ├── bbdd7c33af1f2f968dd249b230763b402837049f.nq.gz
│   ├── bd2a6dcfe23b9642cde35998d9d1dfd315ba1fd1.nq.gz
│   ├── bd92935465970897dba831b47fcbe54550d039e0.nq.gz
│   ├── be9214844626d0ef70f98060c09a4064f31f61c2.nq.gz
│   ├── bea1b1e2e61a5d5d6ffd40c9374f8e56b728aa4e.nq.gz
│   ├── c41a23b029f1c2fe63a40d139e4b984a4c49e084.nq.gz
│   ├── c7b5e3d00c965481e933c0fbd9d60f4e93c89fc3.nq.gz
│   ├── cc59eec4cbf277d427d507163370f5e3119736a6.nq.gz
│   ├── d1456ded40d8108fd375e43c188f02b776dedfa6.nq.gz
│   ├── d73324c6a5effb58dbfd521054bad7fe73890eb3.nq.gz
│   ├── d8eb6bf7a041cf95508be99b4fb52dd67373f8d6.nq.gz
│   ├── d941d8010c3f92d5dfba30eb44ff11b16ad717da.nq.gz
│   ├── db817bd51845fa668a32c06e1a614f3be77b7888.nq.gz
│   ├── dbec27a98a71f36fc107c66898aa02a8cebda74e.nq.gz
│   ├── dd2b2cab39ad3088e10427443e210c671fe2c5b6.nq.gz
│   ├── de8e079ee039feeb8ee1bbcf40a15d056a3e209d.nq.gz
│   ├── e02fd80dc86a7f76b5c1b0075c0c0792bfb9c287.nq.gz
│   ├── e380c6b14e32ce0706695d116c54106b1648a91c.nq.gz
│   ├── e41114aa06f355341e817ddacf9d00376aa66c65.nq.gz
│   ├── e9050c9f94135f491bcaf7a4bda2c1a98165518d.nq.gz
│   ├── eda9f7f53fbd516a093b71a7c92de74cce41324f.nq.gz
│   ├── ee9c3ab4b1a9393e32de9f07b396ef29b8bc1142.nq.gz
│   ├── eeddcbdea24ce428ee4f5e186c31dd994c9f36cd.nq.gz
│   ├── f3c5a2f02f07d4aa2c2bb98a98b383c7b24a3b90.nq.gz
│   ├── f4564a351efa61b9ed2b833c1087f673cbac5ee2.nq.gz
│   └── f94ea76245e395f1d22324eb6032470d4e819c65.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── ce39a6be2cc739165daaeb10cce609b9b77242ac.nq.gz
├── filetree
│   └── ce39a6be2cc739165daaeb10cce609b9b77242ac.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 98 files
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

[tokio-rs/mio](https://github.com/tokio-rs/mio)

---
*Parsed on 2026-04-23 by [repolex](https://repolex.ai)*
