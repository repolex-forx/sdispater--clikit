# Repolex Knowledge Graph of sdispater/clikit

RDF knowledge graph data for [sdispater/clikit](https://github.com/sdispater/clikit), parsed by [repolex](https://repolex.ai).

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
rlex download sdispater/clikit
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1da34f16c50a2a7d4a22d21250cb6268c7b3eefd
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1da34f16c50a2a7d4a22d21250cb6268c7b3eefd
│           └── chunk-001.nq.gz
├── blob
│   ├── 040874b9eb4617b8d41f6d680622502792b57895.nq.gz
│   ├── 04f65faf4f2b8f567119a7f6eaf71569509b6c2d.nq.gz
│   ├── 07d54567c3db6b4cb22e1e0cb42d80ed893730e0.nq.gz
│   ├── 0a1d93c88f5e7650baadcaf0392ffa77d8273b53.nq.gz
│   ├── 0a47be79c0641f8f989f433d7a72e6dd598b766a.nq.gz
│   ├── 0bed22779e90bb228b6dc3341659f39ee67ad898.nq.gz
│   ├── 0cdd3200778aae6c9bc238135a8e4a28499ad09a.nq.gz
│   ├── 0f4a76c839b75b26fabdb3d6bca53f9f55030a07.nq.gz
│   ├── 107b784501ee24b9e345d1b55a33262f026327b1.nq.gz
│   ├── 1168a3a73f5d3bb45185744f3b69d2ef5f23ba7a.nq.gz
│   ├── 13ecbb318e55bceb9da02ae37714dbc810411494.nq.gz
│   ├── 164ed6b34beb8a14284854166074a4b2810ffef9.nq.gz
│   ├── 16af8539feea88b671491a3f34fb733e20d55265.nq.gz
│   ├── 16edcb27e4b574e37a5ed07ec712b3eea56f923e.nq.gz
│   ├── 18a9592f5d2661132b35693b2f0778a108511582.nq.gz
│   ├── 19c3ee1fb328e105dcc5ea64de00715c2b2c1c04.nq.gz
│   ├── 1edd65a7b8b1b59644b2b2378f7d4a14dc6b9e9f.nq.gz
│   ├── 206bb9c66abf8c27fb7178842016803176838446.nq.gz
│   ├── 208a9dbd2c1ffddb7c8d1cd44da3cda1ae010fae.nq.gz
│   ├── 20d598ca2ee477ee99ad65a177f34e2179432acf.nq.gz
│   ├── 20f23c3d80464906a522fb483c06bcfa7eae8f07.nq.gz
│   ├── 235d873822427ac736052d2fc9cebd409c61f809.nq.gz
│   ├── 239500f64cd55353455043b30ef525a515263d83.nq.gz
│   ├── 28a1465d3673f0dc90871de5c5214eeef06566d0.nq.gz
│   ├── 28afcb46aad7d81f0a277f55b3ec491a42df8b03.nq.gz
│   ├── 28c9d4ff38247b94aa11a573a49cc31ab2f6fe71.nq.gz
│   ├── 2a90e3f5c48ba45b17caef28a948026b890187f5.nq.gz
│   ├── 2afde37be5d5a04edd22cbcdfd536ad8adbdbeca.nq.gz
│   ├── 2b66a4caf087663b73020a856f5411cdaf00f26a.nq.gz
│   ├── 2d7bae0d3d5af3d88bfa1b59297fea28b9a7d759.nq.gz
│   ├── 2e751fb83d629345a39c09139db935f6a40eb26b.nq.gz
│   ├── 2ecdc1dde8ed95adbf4a0b1111219e87b79bfa8a.nq.gz
│   ├── 2f138bdb735fd270613328d0ab8b24774ec95a4d.nq.gz
│   ├── 2f32a57b11cae2cf0804524b8344860d95c428ef.nq.gz
│   ├── 2f75f108489ffce4c22a06b70cafddd821c63479.nq.gz
│   ├── 3137b9735e1bbc45f61945a6c792cc338f8c294c.nq.gz
│   ├── 3224a7bf2114c603000d22b73e0a0f01265b7aef.nq.gz
│   ├── 342ab1950371998974664af52ece46ad0c1f90c7.nq.gz
│   ├── 342ea244ca8f2c4ec8fa56b351c51dc57c43fa9c.nq.gz
│   ├── 355d7faa0eeaf35fbe0fba5e969af098994a66d1.nq.gz
│   ├── 35e85a567eb5168df3882bf178668a867e563b3c.nq.gz
│   ├── 36fdbe86901764c7781f8fd3b5478f29eaf17422.nq.gz
│   ├── 3738e940d59181ab934f206f85017478696598fb.nq.gz
│   ├── 389b51ec66e87f958ded8f8e5c0e8e3e9c632307.nq.gz
│   ├── 3934add974b9d5b5efe7028e35efdff7abccaa69.nq.gz
│   ├── 39da6249f63ac46218925c966a4cd708883296b8.nq.gz
│   ├── 3a0d2d420e449217fdafe37031fdf0fe2c83b029.nq.gz
│   ├── 3a69a101ee86e48aeeeb0109425866a7101e0c80.nq.gz
│   ├── 3a9c36c9a8355868d8c79da77ab48a70de6d0fa0.nq.gz
│   ├── 40383dcff02cf662ea393f79c5dc1fdba7c7f0f2.nq.gz
│   ├── 41328fcf0665f705417cbf382b2e93e5cc98671d.nq.gz
│   ├── 41c154550e5fa810f34faf79c9d32e536038fe0e.nq.gz
│   ├── 4282afe1d00e11f557523140213d5b98bea572ca.nq.gz
│   ├── 44c4b77ae8458aa11a7965f00e5f79ddb44d4b09.nq.gz
│   ├── 44cf2b30e6888272f6b278672d0077cd5948b1e7.nq.gz
│   ├── 457f79bfe9cbc1f0e2bd98250a123f7dfb4a9e6e.nq.gz
│   ├── 46c81015182ec95cc4c7f058382cb2ec4724bad6.nq.gz
│   ├── 46f7b931fd6b9ebe326e240447856ef8b9f74e3c.nq.gz
│   ├── 478060cf7777a1eb10f80eeabbe9fddc3ec465da.nq.gz
│   ├── 4c0d4f525df066caffb0ec070644b5be52b3cde9.nq.gz
│   ├── 4da4a0b74535c34e80ced3e1d0620b1cddc358b1.nq.gz
│   ├── 4e14ab427c217a85a2d3cee38d4fd7eecea37224.nq.gz
│   ├── 4eb922e9fd3878a244fd2dd3dafde62495c3a9d1.nq.gz
│   ├── 4fbe1fbfb0222d9ab4922abaee43213edf5ce85a.nq.gz
│   ├── 507c854e5333e193311d5da1a0b17b8e18771f84.nq.gz
│   ├── 5083991691be1476de90c64bfced9c2d4d67c62c.nq.gz
│   ├── 50b96c41a468620cb425383c1ef25d30bd826e6c.nq.gz
│   ├── 51fba47ce97dbab3a33c17d7b5916e6f760bd969.nq.gz
│   ├── 546bd97547a7351d789905aa8f84b72be195ff0e.nq.gz
│   ├── 56355248fd1866383f1e28d253f01a08e2411377.nq.gz
│   ├── 5855fff9cc420c29e0289ff890bfad452340682b.nq.gz
│   ├── 59483890fb1748f7c9eb24214a3d4f222fb73362.nq.gz
│   ├── 5996aef148e98bc2163f9f2a8cfb9857f8c8853c.nq.gz
│   ├── 5d7f6fbd9862808affe2799f6de2ba4af6df7a4b.nq.gz
│   ├── 63cbb647440e2c0eca56bb50679de0c44f5509a6.nq.gz
│   ├── 653d88448a476f299e0010bcd90fab62c3ce22d1.nq.gz
│   ├── 6637ba134637367bc068905541935daf8ee3366a.nq.gz
│   ├── 6b8e15903ae8f995da612864532a99240b56d638.nq.gz
│   ├── 6d06eab888e4930482578c00468fec3dd207d95a.nq.gz
│   ├── 73e391360a50728bed486ae44117f755ee470019.nq.gz
│   ├── 758ab95887bf6f8be962481a57f3e0daa0908985.nq.gz
│   ├── 75ec75cc377b0d1361d612bcff3c1d941d8fd786.nq.gz
│   ├── 775ba8db530d567ac678ad64e0dbcf71928c7774.nq.gz
│   ├── 78aac00b24e6b404820faac7f134b2d68e6fd729.nq.gz
│   ├── 80af4a491b04c7a2736cdb946f9a5b9b9604e1d4.nq.gz
│   ├── 82afdaea2f0726697eed374117998c7f48459912.nq.gz
│   ├── 8490a8718644e41eca12a729ea40458711caa8fb.nq.gz
│   ├── 8500936aeae92fe917321a0a4971f11886ac92e2.nq.gz
│   ├── 852086d18e4eaa3ea577c687821ec45bb6803bc2.nq.gz
│   ├── 88c8e5cc3a20331308d51a8bfba1b960808fa0af.nq.gz
│   ├── 89f8f85eadc18cfdf6ddcd038a808cd95d779df5.nq.gz
│   ├── 8f2279c625bc27c7e38bdb59410919320aac4b27.nq.gz
│   ├── 8f479677629c1253b119edc8fd5bcce8ab3bc05f.nq.gz
│   ├── 904088c46071de0a54d0aeba8c56f5ca29aaa792.nq.gz
│   ├── 92259f459e619375fd752c09d7b345c5af32fea9.nq.gz
│   ├── 93049681a853f45693cadca2c733f033fa65ab67.nq.gz
│   ├── 939e2b9ec34add79df2e041e82a97194fbd47343.nq.gz
│   ├── 93f1a155d98790401ca3b00a1d5c9d0e106f67a6.nq.gz
│   ├── 9557e269e661461dc78099e0769b1c03e9772532.nq.gz
│   ├── 982f8ff8c6b40bb493479466f4c5bffb56ab886a.nq.gz
│   ├── 9889672ecb43778952c85685fc85a43efa38ae20.nq.gz
│   ├── 991d4340f58f63514e243cfe6ea5a6f6920253f9.nq.gz
│   ├── 9a6a301aca77b286c484e7a0ff8cdc8e755d6f44.nq.gz
│   ├── 9aaf27dbecedc1f58d29bc731ea83a8c92ad4717.nq.gz
│   ├── 9b16c167cab9781659ea8093ed90f14806ed52c1.nq.gz
│   ├── a4470fd5885290a48b671284919fa722ed90ec19.nq.gz
│   ├── a5c4e38598336c30ae6b1d0ea533ac48fda968e3.nq.gz
│   ├── a810bcaa11c10b03a06c0435b38bbc87d7fdbae9.nq.gz
│   ├── aca7a010fe626987de0aa1343e4edbaa3b43cbaa.nq.gz
│   ├── adb27bc4fa756ea7a71c22efdaf93636d2bc66a4.nq.gz
│   ├── ae087b964c631d076cd45753059aaaf192a44d6a.nq.gz
│   ├── b2a869b0836bd776ec2591048127aa14fe68acb5.nq.gz
│   ├── b38f0c02ab2cc60e97666d23c7f5c61442787d74.nq.gz
│   ├── b3ac44709de9228f1b885008f10e2195a8b636d3.nq.gz
│   ├── b6b60858ff52ffb8be248863a21d560e89e9af32.nq.gz
│   ├── b82e2d191e8a73c9edcca766b564e1991ec35a5b.nq.gz
│   ├── baf3be4ec1d4ee9af1156f1a42cee27bc4832500.nq.gz
│   ├── bbaec79969512b8d58cc267b879a6735e287b02b.nq.gz
│   ├── bbdafc65fbdeb44425ad10dde761216e54a16a26.nq.gz
│   ├── bdf758b76f9baccf24a25cbbe2105796fdf2c874.nq.gz
│   ├── be078119d5573ad5f043a7ed334bec88a1db1a9a.nq.gz
│   ├── bec6f3cb681fb9db2ee9cfe67f17f2cf53189d9e.nq.gz
│   ├── c400e27642da969b40297fc99f73223e36ce0b70.nq.gz
│   ├── c46dcff8381a759cd1797ed9e0da7fc26f269a37.nq.gz
│   ├── c4ba5ce3af2920e79a6e934cd2fc6629e4acf2b5.nq.gz
│   ├── c56eff5b67e3499530875664c7e3d81d707216ce.nq.gz
│   ├── c6dce29d21ab8c4976cbac001a4f398433921cbb.nq.gz
│   ├── c9c9f1b28779fa5ea10ccbdde0b2728277f8fcf5.nq.gz
│   ├── cbb62d619c7cf1a195b7d8b15235cf4dedb338d4.nq.gz
│   ├── cea5778247411073896c47c8dadac32160f9bced.nq.gz
│   ├── cfbe6328d3a622d95fcc6b58faf40f450012c127.nq.gz
│   ├── d1268b4d59b7ee326ad91abd9c75925f24ee7685.nq.gz
│   ├── d30e812e154985f0faf78fcfed14cb71187cf74f.nq.gz
│   ├── d80d8d7cadb3ef057833c4e6f2d47bd9806925c3.nq.gz
│   ├── ddfdecdf9eeff5e059de9fe8297ba9906dd2317d.nq.gz
│   ├── df02e125e1a7ca1b824c428759b35ee78c1f0212.nq.gz
│   ├── e04add507291d932aa9fb9cb692173dfcaf4d037.nq.gz
│   ├── e15d0f1b804dbafa7f8803fd79d5bce76ca095e4.nq.gz
│   ├── e22eae3fa078352f5d6c82a8bce2185f8192f521.nq.gz
│   ├── e2c48e85aac2ee17d83d290f218bf4653008b96f.nq.gz
│   ├── e33b16b4d52e721b9e515ea2ccd12a03ea2b17d3.nq.gz
│   ├── e384553865adff250c522dd33615f6684f471e3e.nq.gz
│   ├── e3c6c66b012d79f4efe0357477857e4f7d843925.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea6349ee62d6975fba43cc3dde832782bb05812b.nq.gz
│   ├── ef4f47beeda8100bcf72a7565b9d7744bb1394b6.nq.gz
│   ├── efe869f1638da78f9ef281e0acff320cf79178d9.nq.gz
│   ├── f01c4ee0542b009fd99ede77ea58c8e702c1fa7a.nq.gz
│   ├── f0dc1e3242d70ab99b848fba9043c91f7d343479.nq.gz
│   ├── f1b1e2a154be10a4d69ae8eea2223e8449aacc07.nq.gz
│   ├── f348fd707f29df2e6383cce98b5fee74cabda767.nq.gz
│   ├── f583dead83ebd3fd0f6fc3cc31f013e67fcddc9d.nq.gz
│   ├── f6f0064f6f7ce512307fafde2e3beb6461048d5d.nq.gz
│   ├── f86af23ddf0d63683f03102d6872590423f7ebb1.nq.gz
│   ├── f9c5205be07283a334a3b0d949736c6124f2f8a9.nq.gz
│   ├── fbed5a599caaf7122a7f6bb0b593bc15d475be70.nq.gz
│   ├── fc654c0268f64a781b3cdf29dbdc179a3105fc8e.nq.gz
│   ├── fcd36c1e056e7528377c953399cf1de4a5fa15d4.nq.gz
│   ├── fdb561a36a133b55e59d5048ae4d2ecadc47f278.nq.gz
│   └── ffebe0c34fd22408aa47880245c60b0fd4c30629.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1da34f16c50a2a7d4a22d21250cb6268c7b3eefd.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 168 files
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

[sdispater/clikit](https://github.com/sdispater/clikit)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
