# Repolex Knowledge Graph of beeware/xbuild

RDF knowledge graph data for [beeware/xbuild](https://github.com/beeware/xbuild), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download beeware/xbuild
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e4b51709bdda1f8fdcfa73db56007d206b52891f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e4b51709bdda1f8fdcfa73db56007d206b52891f
│           └── chunk-001.nq.gz
├── blob
│   ├── 005c5ede45e0358bb15e75db167021a3838f7dd7.nq.gz
│   ├── 0085604c4e873ff519a648b72368fd965113f67c.nq.gz
│   ├── 01070500994616f421d84729adc09f9447dc4dfb.nq.gz
│   ├── 03db1a99396c43d8f97b87ddfd16093f529b93fc.nq.gz
│   ├── 04ed44339605aae081bde8d539d2c2b50e7a1f23.nq.gz
│   ├── 052e21f26af14e291727635c01d3e498a9b44a75.nq.gz
│   ├── 0584b24c07559404417bf9901d1500377ee0faa4.nq.gz
│   ├── 08ef4d86074dff83878c9277c90b8e5d82131761.nq.gz
│   ├── 0990a1b765f76b80c8bf1cfb16aabace99749fc8.nq.gz
│   ├── 0baf8b272762c25cebd57859f65e1254fe2f83fe.nq.gz
│   ├── 110e5d6c9caabd1259cc2eada33056522f791e81.nq.gz
│   ├── 19716c4cb1fe3da243c0f2e5181aec319f203376.nq.gz
│   ├── 1c0bc51916a52a9505c5c6dd1bc33fd5d387b44e.nq.gz
│   ├── 20cf39097c68baa17cc566b64e76d34ebf034044.nq.gz
│   ├── 210ca5661e412b1d7e80cb1db735192198328612.nq.gz
│   ├── 21398609ec9c7858e6ad9566172f8e751750a22e.nq.gz
│   ├── 22821df511001347154c6de7b571a67d75ef356f.nq.gz
│   ├── 23585f60923af651ce449dc941191d3336308def.nq.gz
│   ├── 25c4f7beeeb7de8db6ef251cb6714801af0e1835.nq.gz
│   ├── 260ae8939294cf7b1d67248711ee1460f7910ece.nq.gz
│   ├── 26472c2f3703afc9a5a9cd95533fffc1f0397422.nq.gz
│   ├── 27de5d01c1f19bde3d9ec7ee378788aff378e4b6.nq.gz
│   ├── 2923789aebbc0589f90901ee2f3ad6ccf3d15aa5.nq.gz
│   ├── 29b134a02811b04d82cae852dc4e47df60911367.nq.gz
│   ├── 2a451673f01393bca48b957b9d1dddf3b0c453f5.nq.gz
│   ├── 2b7e37491c565ba85f0b202fceae367941db3234.nq.gz
│   ├── 2be8a82d4260999f28496a6d8fdb76d2972f2e84.nq.gz
│   ├── 2dab7783f4c2fc4682957b08d8cc909a733974c2.nq.gz
│   ├── 2fd49220698eefb539be140989779cb92c64068f.nq.gz
│   ├── 320dab52acdc0bd71635ef4a1a1e9fa3a2e1c064.nq.gz
│   ├── 3514d5105c6063e97bcbb342a250ea2a52ca84e9.nq.gz
│   ├── 352d2f9e885a2a24a0afa276b5f5715ab78de322.nq.gz
│   ├── 365deb489a15504563d10bbc12bbf2c8dc5124a2.nq.gz
│   ├── 36a7861800381a2ef12605282d4eeafeef99d52d.nq.gz
│   ├── 3855912d9f68bb1881458be68f38678ad8e3e8e0.nq.gz
│   ├── 3c48be4bb5851390c28c1df50b0072a25038596b.nq.gz
│   ├── 3c73197c19c965dd8e3f06a2c22063c111a805d3.nq.gz
│   ├── 3f630e895dfad825d771864524f7aa8ae9ce52d9.nq.gz
│   ├── 42afabfd2abebf31384ca7797186a27a4b7dbee8.nq.gz
│   ├── 43bdffca5254b3faf3d4255c9859b9274caad694.nq.gz
│   ├── 47936a9168254458dae8a91598aeef68cc820049.nq.gz
│   ├── 47f832f87cd030d2d7391da270ed738aafd41527.nq.gz
│   ├── 4a09c81e23ca735b7d235c71f9ed7feca8081af3.nq.gz
│   ├── 4b093471c90949e20eccd126e0f1b11a3209177d.nq.gz
│   ├── 4d296799c5da68fe3e4e84788057f7b4dade9684.nq.gz
│   ├── 4e141e613f43e9f6c963eba6156e8eab2dbb10a1.nq.gz
│   ├── 4f6de72c65565c2801f3c6e657b3d538efcb7ea5.nq.gz
│   ├── 5135968888acb5f5754e50e48cd3ede3c73d6dd7.nq.gz
│   ├── 51874e07ae8c2364a6590a5646d1ec5a9f33ebed.nq.gz
│   ├── 54006e1ce0162ce4acb2d110b6d57381579e6f67.nq.gz
│   ├── 5492471e53fddb9bd21977d75366eb84e1d43e3a.nq.gz
│   ├── 563a54ac7dc10bffbc78e038e0272feb2154bdf3.nq.gz
│   ├── 56994d0c74e654cf21eea26ac4ce53f5ffeb41d6.nq.gz
│   ├── 59ce2eeb7d622448451588f8cbf05587dbd79efe.nq.gz
│   ├── 5aff7df452064782c507caa41012a97044598b25.nq.gz
│   ├── 5bc161f1745f9e8b40b7863290a40440c7d2cc99.nq.gz
│   ├── 5e08773e02450f9c4cfac02233de028a94fcafdc.nq.gz
│   ├── 5e5ac2a6ff0a27eeb52d20b7b14d5dd29e13ef80.nq.gz
│   ├── 5f835ee724fa4b95d2f5dfd10201d9be4177d676.nq.gz
│   ├── 64783cdfb8569065e96971f93b1845e74d8a88cc.nq.gz
│   ├── 6632d9e5c1c4045f28e6e2fea4d02ccceac6f603.nq.gz
│   ├── 6c225a9d1c2604dcf5418a92e5f1aa43ffaedac3.nq.gz
│   ├── 6d26605c18828a2d6a4deb2951bb0f26f82d3727.nq.gz
│   ├── 6d5ccd96f8ae2902e325bee84524938b41b592a9.nq.gz
│   ├── 6dae97649217287ec20aa417caec279c93101a7b.nq.gz
│   ├── 6e34adaf869f835622b4da5a2502fdcac3fa7641.nq.gz
│   ├── 6fa0f02352192e021b4fff2583f60091d48d180d.nq.gz
│   ├── 6fe48eb1b26e8a5fd0214e33691681ef06532460.nq.gz
│   ├── 70539649d588f858bd064176bdb8e1cfd4d7cf1f.nq.gz
│   ├── 741d6580d60e05080e71e845240863f6b273333c.nq.gz
│   ├── 7a2d0ef1f2135deec575745b2c24bde2ae6b1184.nq.gz
│   ├── 7c57aee58c160a254122841cb68c2cd2ea96ee1b.nq.gz
│   ├── 7f024f0a348b61c8b50b5e5f4b347efaca46ab5d.nq.gz
│   ├── 816198782f7584e4976a56981dd91215237229b5.nq.gz
│   ├── 819433657150aac87e7b599b1a0a2a564af1161d.nq.gz
│   ├── 82409fcf0432cdfdd4ec317df21d62cca240037d.nq.gz
│   ├── 85b9269631ae91558dedfb932f9cdf7702efa180.nq.gz
│   ├── 88339b4701f482a61ebe3d95cd2b265fa38cab77.nq.gz
│   ├── 8994c4ed0215c5903f4c10d8bed945eaf54551c6.nq.gz
│   ├── 89fddd784ec6bd3692f77918f087f47fde424a56.nq.gz
│   ├── 914de5332ea469040ded2380a661c805cb01954c.nq.gz
│   ├── 927ac8356e18085a9bc524f08ec04be9efc7915d.nq.gz
│   ├── 956e9e85e672eba3d2d3b0b08ad1d989bd3deb78.nq.gz
│   ├── 96d7c7de08b2d3b18df9b27cc036e6f248b429f0.nq.gz
│   ├── 9a18c04ab82fd85977b5a0309b85042315baeb22.nq.gz
│   ├── 9b251eb151c2b187e3429c4d9d52fff03981bb2d.nq.gz
│   ├── 9b8908267ee132897deb2b5d7c48a6f81da6a598.nq.gz
│   ├── 9ce2cdf62163420722e566e1eabc50c433424529.nq.gz
│   ├── 9f7ef72fbb9696d91530b59ebd10341c332455f9.nq.gz
│   ├── 9fcece77250837d3309b4089726d4067b63aea95.nq.gz
│   ├── 9fe800d72239ce8153805f48235cef4cc1a667c1.nq.gz
│   ├── a01a96baeccccdb1130a28eed84f17b5cf823dad.nq.gz
│   ├── a1e7ff8dc490f0ab166c66532ef0d808eadb647c.nq.gz
│   ├── a1fba5adc6f5a190d9f75ebdb9ece75c3eb7c583.nq.gz
│   ├── a3a59c07d8fc56ec6d360bc8321c2489968fa49d.nq.gz
│   ├── a66a582a0d45a426bd48154542cf20b564c182b3.nq.gz
│   ├── a9a2043081724213abcfffb470d6cb258d7747a9.nq.gz
│   ├── aba8e988946b6d653dbd6413117b2c8ab1e3d1c7.nq.gz
│   ├── abce397e932dcf4c0367853aed798be9d1bc798f.nq.gz
│   ├── ae96a20bd09722940b2e76720a0be7d085c46fb2.nq.gz
│   ├── b1ad12b4d72c5686f58b85950a29950d4c0d2c8c.nq.gz
│   ├── b1fac969ea23dbe8728818f8ef7c69be6e2d0b91.nq.gz
│   ├── b33c3f3933faab5a19d8897cbced7510652d5c01.nq.gz
│   ├── b3e7829df39980dee8f1212f75bad705374e9481.nq.gz
│   ├── b53e73074fe6bc2db852710e61ffd58970c0ca41.nq.gz
│   ├── b5af3acbee0dae96afea08c6202b14e63f472ed1.nq.gz
│   ├── b5d7d013f7d0bfec012fff8754a4534b3d2e28a4.nq.gz
│   ├── b834affdddcf5014398ca9c16aafe3ea7f2d0422.nq.gz
│   ├── b9fb4e8523668f48328e0203531666689f3d387a.nq.gz
│   ├── ba81662d7d50d30b4fdc162ea24698b13eb9503e.nq.gz
│   ├── bff552d35690bab4b83309a2dd665895073a2c38.nq.gz
│   ├── c0162c1c0d4255daae6c9ad3b13161bcbc498218.nq.gz
│   ├── c1c4c8b9a95d0c4fac7cbc14f763b01fe20f362d.nq.gz
│   ├── c20f302317150bf4a101220ae6a8f69c712b1f26.nq.gz
│   ├── c2292069b97954ccce08417bfa710a11b7132cf0.nq.gz
│   ├── c24bdac88ed04c8dfbf93d022bdac2e9da0a1fed.nq.gz
│   ├── c2b24f003a30ecd7e7cc99b052273dd8faad1fa8.nq.gz
│   ├── c301cdcc220bbd43ac70393b67a182340e7d472b.nq.gz
│   ├── c3c485abce70fccca24d909e2b4a2e25eabf31e3.nq.gz
│   ├── c4d88e8173e484996f9c1fe716bd0fb7e4c8a73b.nq.gz
│   ├── c75df40385b52de338d8f832d0202ce13591f6b5.nq.gz
│   ├── c8fe3acd849ac7a876fabc228931d61eb7d249a9.nq.gz
│   ├── cb7a1cf4e64260712ec323352a885eb3412f03be.nq.gz
│   ├── cbe65a81c62ef40eaff430cd202d1ac8727027b7.nq.gz
│   ├── cd0798a468c713e8f4687c572d81d180d61a5324.nq.gz
│   ├── cf4f23e3a1c445493f24cd7d4fb9a769466f4d6e.nq.gz
│   ├── d2009be924edd5fa62440dce993788d273610990.nq.gz
│   ├── d4eee58e3ebea70f9ee234dddbef716e349ccf83.nq.gz
│   ├── d770ad6a4227e958ff56f48fd35ad874abd18cb6.nq.gz
│   ├── db0bed7ee30635eb978a5983c65282ccd2a9e40c.nq.gz
│   ├── dcf508835604096e3e7252fd97210f663b87ceb3.nq.gz
│   ├── dd64de074b593e1ff78454252391c3a0b074aab1.nq.gz
│   ├── df21be27523499900a7d8789eb6fc69cce8c9c62.nq.gz
│   ├── df624ec3ba4fb1638dfd3f5cd041a0f133bbdbc1.nq.gz
│   ├── e4a84c7ae0aa2766e47c31cbdf61f98143fe458c.nq.gz
│   ├── e57243566f91dcaba2d4dfbcccbf596c6f0ad663.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e828b1f1a19365a2dfff348555c2c69fb5274476.nq.gz
│   ├── eb9876bdabe0aca80bc0fc3d441f4f050bde5903.nq.gz
│   ├── ed251d7d3305e608672518878a9e9449588def5c.nq.gz
│   ├── f0a2a08ecd78c29215a6ae6e1d6c95aa5cf2ac5f.nq.gz
│   ├── f1daa865868673e0d941c01d1fac631b05d116ba.nq.gz
│   ├── f37e86793df0e3c2d0b1fe7ec1a25ca7d81a2004.nq.gz
│   ├── f655e3ad5e81ea48b0847165772d5fd882be1a3b.nq.gz
│   ├── f765104d3594353cc99b1546d3303828f15b29bd.nq.gz
│   ├── fa84492f134ed08ce5d563e3282940e767fd1f3d.nq.gz
│   ├── fc9dff197ffb5526a0dd705159157887d5f7605a.nq.gz
│   ├── fff3256061847fee8241cdb4d5d5f22e84adbcc9.nq.gz
│   └── fff8bd55f53b13fd6f35d048ae345cfb335570d1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e4b51709bdda1f8fdcfa73db56007d206b52891f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 157 files
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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[beeware/xbuild](https://github.com/beeware/xbuild)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
