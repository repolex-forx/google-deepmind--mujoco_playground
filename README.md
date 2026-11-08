# Repolex Knowledge Graph of google-deepmind/mujoco_playground

RDF knowledge graph data for [google-deepmind/mujoco_playground](https://github.com/google-deepmind/mujoco_playground), parsed by [repolex](https://repolex.ai).

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
rlex download google-deepmind/mujoco_playground
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 24a071343e380eb739a053650a9d12bf530cc92c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 24a071343e380eb739a053650a9d12bf530cc92c
│           └── chunk-001.nq.gz
└── blob
    ├── 014234c66a08db10d789df4a0499a3cfa9f00006.nq.gz
    ├── 01b60bb21a5a9eda0c33bd3f6dcfa7dd3ca68a28.nq.gz
    ├── 01c0761262ca13a0ba0abc8b863f3e494189e05e.nq.gz
    ├── 020ce346585bfd6dba1215cdc3ea206672d8186b.nq.gz
    ├── 03d9ddca7a5df4213c5c4191ddc7442050dfb6ff.nq.gz
    ├── 041c94fec760772a8884a5962161e2121b721562.nq.gz
    ├── 0426823de2996d5adaa0e7dd709220918fda231d.nq.gz
    ├── 04fa1fe20569f2f0aff9365f2c6b23013b13a647.nq.gz
    ├── 052830c24b90e4c86c4acabade3f05f80a52052a.nq.gz
    ├── 05f9169b15e37806fb59eafb498a6b9aef164e89.nq.gz
    ├── 0700859cd49320137237a3d2890e0e6a0452ad4f.nq.gz
    ├── 0701bc0ed83a878c376588f731eacc667b65260c.nq.gz
    ├── 07cd177faad0c491d2b6f51a8cf86898f6ee1671.nq.gz
    ├── 08020417e4115734ba4b34bb9def2fd1e8808b5c.nq.gz
    ├── 08afb0037639416bf8d0e97f97ae6692c912a499.nq.gz
    ├── 0916aa59a10804a35cb6ac0c49bf9161786a695f.nq.gz
    ├── 09199731a3e9b56cee773cefd26d1c46ba8fc062.nq.gz
    ├── 09280ef5c4d9b75f147ebdbe101a1ef4b7fb8d13.nq.gz
    ├── 0958bdc166e6cdc80ee5de698b8ee1d4a766807a.nq.gz
    ├── 0a312948c1c5635f3e97b7a0a1e43675d308ea2b.nq.gz
    ├── 0b2bc17d97a1e614e3639eb795e91c7601e96f13.nq.gz
    ├── 0b8cf0f103a5937847b40ba482035813cdfad2e0.nq.gz
    ├── 0c9126770633df1410ba3d74b312cb29a1513132.nq.gz
    ├── 0d1e5fc4f5072256f35e9e1cef9f1751fcfb9c61.nq.gz
    ├── 0d6ecc798c4e164290176ba1aa947a5343d3ac34.nq.gz
    ├── 0e2a69a287757f5afc1d19c3e8f0dd53e1e52fe6.nq.gz
    ├── 0ea5429a7993ff655beafbc31f0f1f60ba555179.nq.gz
    ├── 0f374447543c105997af6de3219fdee64e5c041a.nq.gz
    ├── 101d8905f52a85afea8b0807cd89fb38bd2d5154.nq.gz
    ├── 10d7d88459e16bc533b7a3bb779b628cb14fb13a.nq.gz
    ├── 11b61fab6c3a56f943be8f0db329d29e5dd5b81e.nq.gz
    ├── 11dd56571d927678374999e26b3983e8493034c1.nq.gz
    ├── 120ad9aa3d1f29c11ca80b60c84c9ce877223eb3.nq.gz
    ├── 123096276f823f09b12ec329b57e458224cc9798.nq.gz
    ├── 12bf918314d092dac3806043a7a5444a463a5826.nq.gz
    ├── 1397009f330bc4e8e14940b3407aaf6283971d3b.nq.gz
    ├── 13a5c055c1a3ec70bbb1cdea46ae227df9e8199c.nq.gz
    ├── 13e3192570acb4fc9c30a4ab82e42d50e3452d3e.nq.gz
    ├── 1456b3ff47440b380e9806f6dbb40a74218fca34.nq.gz
    ├── 1458c74988f500c5c0ec90f4bdb659f19d773f7e.nq.gz
    ├── 1543959ad192761b5baf5a5c81103fc922a3f27d.nq.gz
    ├── 156e369165f24287b17a75d8f67346ed5fc40419.nq.gz
    ├── 15eb8ffcb521141edc36bb7e7012be8d9b74da2b.nq.gz
    ├── 16a958cced953d72ab79f382e12fb562512114a7.nq.gz
    ├── 17137abe148581925b3ccc708c22d2c94c5b5e29.nq.gz
    ├── 184e39094efedc9698ba8db8e13726248d862ef6.nq.gz
    ├── 1921443ae5a771bd2ef7d3304c95677a9b2bae5f.nq.gz
    ├── 19bf347470e126d6a663554b88cb941356d24c73.nq.gz
    ├── 19f406a137b08d82ec2b870148f61f0e53a6e022.nq.gz
    ├── 1a05178c8c78e721b393e459a7aeabefa1505c9e.nq.gz
    ├── 1a658de0a5993b1a059cd8d2039b1d26cccc1eb8.nq.gz
    ├── 1abdb90bb534651ab237dbadae9759305cc20c13.nq.gz
    ├── 1b8a6e38a71b1e2749bba939b3875425536eee43.nq.gz
    ├── 1c03468a92579849878ac3e622eca119cdaabd04.nq.gz
    ├── 1c834230c2b812177a93fffaf820c34d27a9b616.nq.gz
    ├── 1d03d4f73c53adb3e2129d2f6b256105a302ce18.nq.gz
    ├── 1d2396e28d3102d703e4a6b3e416e2c11d955992.nq.gz
    ├── 1d30d1cdcaa2e38bd06bf7f1e37719f74b02bf9b.nq.gz
    ├── 1d670fe36774a72fcb2f3c847ab39d0a55b26010.nq.gz
    ├── 1e0cc16e738deb317fbae93cabd22e3641aa3633.nq.gz
    ├── 1e27295c40a760394886e6c5ef2a09820900376a.nq.gz
    ├── 1e5d8139d676c65b80d971f22b5cb9a0f33fe670.nq.gz
    ├── 1f08e40b617a76ef7d24b9e9d541f1b61eb30096.nq.gz
    ├── 20ebfa90c39510d2ff520bb43f18a0c56820cf84.nq.gz
    ├── 21744c80f97e8bf46f5a30d679564b9cd538f60b.nq.gz
    ├── 2183ea2bf369eca077f49cc0e7c32aa905adaca4.nq.gz
    ├── 229eace2036f8eb338266e889b2ec23e55b9a07e.nq.gz
    ├── 244394736508145dcc4b02153b1567ad168e64af.nq.gz
    ├── 26aebb74011728fbc016326194da66415ca20ae8.nq.gz
    ├── 278ca8d84e97fed6f0431ec294e52f57f376871d.nq.gz
    ├── 27aaf8f595ead29ce9b0141fa8880eb966ffc003.nq.gz
    ├── 2a1ca9ce3302b86d61ff167454fdead0426b4e16.nq.gz
    ├── 2a2171558c79746b30f43f94b6abf10915333690.nq.gz
    ├── 2a74730fa989dfac12c9f21d92da48416da740b6.nq.gz
    ├── 2c13354eaec1757df343070126ff2a891a426d10.nq.gz
    ├── 2d9be371c5fc3d1fa873d6e06930aa3221fe441c.nq.gz
    ├── 2dc654449e0ffd489703900e2030e73fbc1f85fd.nq.gz
    ├── 2df953c3336c6bbaea7ce1562eddad38ca30bcff.nq.gz
    ├── 2ea8908e319172de37ad8af338e4cd0f9dbe490b.nq.gz
    ├── 2eda67e1b12bc15088974eb168b89fa5a66ca356.nq.gz
    ├── 2f262c4e27df44d2db72c52aee0de73736bb886b.nq.gz
    ├── 2f506f7ac53fe9affa39700a0a0ee50294d9c429.nq.gz
    ├── 2ffd257e86e915e9f39ac3d85e2f8182e5984e3f.nq.gz
    ├── 30750869203b0cda1bd3b0b0f1b4d5b8a8a58c49.nq.gz
    ├── 30e88b120a58e73413acc46980309b2a3f1fb1dc.nq.gz
    ├── 31407d42d764072b9dc22150e747967f4e3055d5.nq.gz
    ├── 317f3e8da38c85a2724db30001e2c463d5fef3eb.nq.gz
    ├── 318ddb28343725e1a4ac2769ebf5dc6f1051b175.nq.gz
    ├── 31e2501a8b43c17259ba3b069ec791a8bcad1fe4.nq.gz
    ├── 31f80675816fab071d6bcca958306656905e9af7.nq.gz
    ├── 328ed8d0cc9efc333bdaac5e7a758a0219fb0eb8.nq.gz
    ├── 347b181caeff7e1ab2c36db4177a8820f2138207.nq.gz
    ├── 3496382cf3b72be3d4736f8caa0257d5e2afbc6d.nq.gz
    ├── 34b9b84db6f879595c4d906592b44e536176b15d.nq.gz
    ├── 34ffe7e6f833385546155357c65493331df721da.nq.gz
    ├── 362a5251ca4e885dad010f30d083c639011f5c98.nq.gz
    ├── 371670baaf07a6af0e16303f24da5277528d8d9f.nq.gz
    ├── 38a3926710370a92ff35b6d389e1630c9e7111ed.nq.gz
    ├── 393a54bf1303b5298c3f856e1c42fa6455c1de38.nq.gz
    ├── 396b58d5969dbf909495849572557699eaff8e5c.nq.gz
    ├── 39f4350b88e9ef386f7ba3655a079ce077e0b82d.nq.gz
    ├── 3a87edf7a52d14e4947df51b8885eaba1aabcd5e.nq.gz
    ├── 3b1db466bb2dbec4eb786d0a76f7ca64bf1939da.nq.gz
    ├── 3b265900d17c894182651c248891d98c10d7b700.nq.gz
    ├── 3b35f05f06a1e7dba7e27e6222dd335fbd2085cf.nq.gz
    ├── 3b6ae8442efe47e9dd0db94aa52fa99812a96dac.nq.gz
    ├── 3c05791711fdf76a87bba0f6964790cf6cfc191a.nq.gz
    ├── 3c1b83813a008cc4e3d0873b6ff4b2aae422abf1.nq.gz
    ├── 3c74a4ca2da458687ffdca5abf72c54c3828e228.nq.gz
    ├── 3cbc3f9062c16cecf3d3dd05120a371dc1d70d9b.nq.gz
    ├── 3d155a617a78f8480eaa010f973ed51676a7b90b.nq.gz
    ├── 3d9d31703a95cdcdbe5a4a17d44ce4bf773352fd.nq.gz
    ├── 3e27153c651282800940bab24a047b24c3f3915f.nq.gz
    ├── 3e4c3379fcd54bc6ce921f0d1994564b9a000ab5.nq.gz
    ├── 3e5076ce4494150c0cc946e606b439e6ab813c13.nq.gz
    ├── 3fa3f834fd8c0f4f23c5927bf42e594ad6151cfe.nq.gz
    ├── 3fac8b066d6cbdf2dbe4b6c8ced9082ae9b4aa8a.nq.gz
    ├── 41ba16d3a626d7ae0129079016fbdfd0f6ba9729.nq.gz
    ├── 425f214f0f81bdc6bc3528a4e0f25519b6a23e4f.nq.gz
    ├── 42f6e69fef0b98aa21dc01dc10ba941c1565e3c1.nq.gz
    ├── 431d8ffa509a6822996773c35e315b8922cbbef2.nq.gz
    ├── 43fee467679819ecdbbbf75973490ca5089aa723.nq.gz
    ├── 4496a25fe8c54c576d24c0a92da17f1291cc695b.nq.gz
    ├── 44ca4126c6c19c312dd74f37f6670e2fe523326d.nq.gz
    ├── 451bb1c8e4778c51011ecff9077e462b78e5e1f4.nq.gz
    ├── 45614d8d30410ed32b04527bc6020d0b02f9a446.nq.gz
    ├── 4646e862d2bba7a99f67f3e2434223f618e0a0e1.nq.gz
    ├── 464ce860239b1187d58e53697dac7b2aa5f44ea6.nq.gz
    ├── 4684e4e024653ff55c37dd637af75981cc8af762.nq.gz
    ├── 47ce0d5a5be03e67c67f323a9bc6a72cfcc370e5.nq.gz
    ├── 49759942cfc569da9b96a87062bd2e027f6b8ef0.nq.gz
    ├── 4a022e5de1b7e7689bad6988e0654deb93e6e1d3.nq.gz
    ├── 4a71bd7d271456f1d442860fe53f477385c42296.nq.gz
    ├── 4a7c00cdc92e245914d39b86b69b9329a26c35f5.nq.gz
    ├── 4b972c1f16d5d14dd231f7548957b834a3a72a56.nq.gz
    ├── 4c24d65f6a014fe88dfdb1ae07660173d179cd9c.nq.gz
    ├── 4c3feff34083c48b0b5c549abc6582018c76951f.nq.gz
    ├── 4d71c7c7bdb78d81eeccbb32e3975db9e53e9ff0.nq.gz
    ├── 4da025e004fe430b84e15baf3856a41ce5941f35.nq.gz
    ├── 4dbd23ab590e9aa3c50d16902d45cc6dbe300db6.nq.gz
    ├── 4e23c9b09653f8aed5fcc0a02a72aa14e6cfd84b.nq.gz
    ├── 4e5600d94e4923d9521bfe9e645cd21cd3aa5dbd.nq.gz
    ├── 4ee0ad5f57cbe0f5ca6742e8dc0e4aa39869928a.nq.gz
    ├── 4f2060413ef82c8617e791264706a5ad3dc5feba.nq.gz
    ├── 4fe88bc62ef22261abfbd7ef59deb2823808b698.nq.gz
    ├── 504a58153a0515e2c492369b97e73293d17e2b90.nq.gz
    ├── 50b0ebad46c5f727489d06cbedee7c170b883e47.nq.gz
    ├── 50e468eefe2c79dab0b4c06cb2ef912d67fb1c34.nq.gz
    ├── 50eab329fbca87610f8ba019056cd367957fb9d3.nq.gz
    ├── 51c5e00be62fe66a3d3c98602a61530f7d6f2821.nq.gz
    ├── 521bc0bcb0f250c62f168b270d96ba299b954b91.nq.gz
    ├── 52f11bdaf531c4ad9aff3fb5d856c401b48708fc.nq.gz
    ├── 533ac82cdd70b17231e05f74cda76bc054acbae7.nq.gz
    ├── 53802a0976c51836b50cd8c2fd8c8b9cce3e13d9.nq.gz
    ├── 54e078fce5cb05d668b73a9c67bd15b5f4180373.nq.gz
    ├── 550b860c6fe5575df9a9da14656cac2b1a8c7800.nq.gz
    ├── 55a120fcffe147d9f314610b5a89b0bd0d963985.nq.gz
    ├── 569103945d4b9243ccb6c408685e54f501eff3c5.nq.gz
    ├── 56d978eb37e6358aaae570a65a6c3fca41cc53c1.nq.gz
    ├── 57353b684d7d1b1805f8bf09d5ccbda82bf2ff1d.nq.gz
    ├── 5771c6c492c6b37d0f7c3a1244f1d2914e23f2a6.nq.gz
    ├── 597083af0e53ad0b5fb626adb0ef4384bf6518c4.nq.gz
    ├── 597726ff044377349b1dc9a78f19907774f2c766.nq.gz
    ├── 5986ab3f7c64ad636f3ac0c1792955db3f4215e7.nq.gz
    ├── 5993b8e083d1782bd4ba68b7ecc2794bc309d18b.nq.gz
    ├── 59ca63950eec3ab2e718e96437025949bb3982d3.nq.gz
    ├── 5a2fb65b0031b01aaf7d7b3864b2933858800f3c.nq.gz
    ├── 5ab44cf742942e5e5996938a3e07f50d634af532.nq.gz
    ├── 5b14719d212c80fc38b30a923290dbf22a3cae35.nq.gz
    ├── 5c4466396e3527a673218bed582f0eb8fd92a971.nq.gz
    ├── 5c59a5085172009c4ca05ecf11761e2b2c01f1c6.nq.gz
    ├── 5c71c776c4043adf2a466e8c9f882b6afd796c1f.nq.gz
    ├── 5d361ca9dcb589d8408954240ed64f990c94ba5e.nq.gz
    ├── 5f17f93a6031347baa3f2a4c2b2fae686fe83d11.nq.gz
    ├── 600a7ff1d6cf5099865dc832311d4a6ddc147901.nq.gz
    ├── 60433355fde5d8c265e6d4e436f7c82b1383b05b.nq.gz
    ├── 604e6e78b9159e608c1be4e300c9febf40941960.nq.gz
    ├── 609286aff8a968840d55e900175b43a3eb825c78.nq.gz
    ├── 611b653ba91c9e61d4825b64d8f9b203e74412e2.nq.gz
    ├── 61497946767cb72ce2891395583869bd0ea829ed.nq.gz
    ├── 6277f6f827025b868c45d33f6304e68188c436a0.nq.gz
    ├── 62af27a2bcbd1d9ceb3ac6a8fcda9e28b437ffee.nq.gz
    ├── 62b34e3d2a2d34c6141f58075e3a841f114e417f.nq.gz
    ├── 63cc4dc835626c860e1247f4235791198ac3e569.nq.gz
    ├── 65bc230664bd158c6a7dd32168c76079bdf8df4d.nq.gz
    ├── 660e5b98d0780775f445293b1e70bed1d8cda4d4.nq.gz
    ├── 6730228566723ff295fce0a214a7c8a5eaf18efb.nq.gz
    ├── 6788c122379a20390e41504dae5425977eb71388.nq.gz
    ├── 67c487db4c7c1fcf491ba915d8fd041c751fffd1.nq.gz
    ├── 680707b2d63a4a3e6e3f04eaf8216053c1966214.nq.gz
    ├── 686fdd860616903cde08468df380f5ebd890c766.nq.gz
    ├── 68f2c6180f9237e789eb0312053d577fe65b21e2.nq.gz
    ├── 6950c6081fe061306cf1dd97d52476072bdd18e6.nq.gz
    ├── 6a20ef3e73f8d1165e300b653f9a0c654897c651.nq.gz
    ├── 6a55bc57aa145f6d8d7771abab116d1c3c61210a.nq.gz
    ├── 6aa472368ab3776444748140ed9d1d78fada9f08.nq.gz
    ├── 6c885b854a1f15558046f4d531033d0c7689dc1f.nq.gz
    └── 6ccfa4b77b87c75df8881de057080871261e86b8.nq.gz

7 directories, 200 files
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

[google-deepmind/mujoco_playground](https://github.com/google-deepmind/mujoco_playground)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
