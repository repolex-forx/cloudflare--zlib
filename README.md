# Repolex Knowledge Graph of cloudflare/zlib

RDF knowledge graph data for [cloudflare/zlib](https://github.com/cloudflare/zlib), parsed by [repolex](https://repolex.ai).

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
rlex download cloudflare/zlib
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 50893291621658f355bc5b4d450a8d06a563053d
│   │   │   └── chunk-001.nq.gz
│   │   └── b7bc38845416febaba0d3736fec890750ad9fb28
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 50893291621658f355bc5b4d450a8d06a563053d.nq.gz
│   │   └── b7bc38845416febaba0d3736fec890750ad9fb28.nq.gz
│   └── repolex
│       └── b7bc38845416febaba0d3736fec890750ad9fb28
│           └── chunk-001.nq.gz
└── blob
    ├── 0160e62b69f419e1eb903cf1d323c07e1ec19936.nq.gz
    ├── 03d20f838bfbb0b73a6d2fb35f4363add2af74ad.nq.gz
    ├── 043019cda1db5ec2ca6a7c82acce4d559e9787d0.nq.gz
    ├── 0491bfc2b036f179f9d3a2f37fd61d9b3b8dd779.nq.gz
    ├── 05fb3e338070d67054858cd2fe469e3bbb2044a3.nq.gz
    ├── 0a0da54bbb45ae762ca37866eb7d0ed8776f683f.nq.gz
    ├── 0a90e76b300205a44a0ecbf613e64aaaef2e51e7.nq.gz
    ├── 0b2a3de2dfe25f8afef4b331e92197929a698181.nq.gz
    ├── 0c0247cc516b4493bb9a9b66f743a6110139a2b5.nq.gz
    ├── 0ca0969a7d09a487b1b2b5d74b805837a3bf2e96.nq.gz
    ├── 0ca4a712046af856cd2b490c1bfe90029db33d95.nq.gz
    ├── 0e2594c80885c0dbea13c6d22b2e60e9fb82b51f.nq.gz
    ├── 1073c0a38e6c2c7f51d7638135a08f1471d7320c.nq.gz
    ├── 10e445f216f20dba6dba085560888ca0e3768b6b.nq.gz
    ├── 111ac69190f0b2153a6f263f0ce8c888984b527c.nq.gz
    ├── 1154484c1cc15874a95b5d58af1f41e18bfc0407.nq.gz
    ├── 12c009018c3775df11e98b403a447d97a46da4ab.nq.gz
    ├── 138a699bd53e60250b3eed61e631175ef0452630.nq.gz
    ├── 13a1bd91a9b00f5527e7878e74740918d2833907.nq.gz
    ├── 13c6221914714eeda5217958344d19b96dd4ef65.nq.gz
    ├── 15e3e165f37decb7c403a892438650de80f3b928.nq.gz
    ├── 180b71cd61df64afb4f8c13f84e73426c4cd7d2e.nq.gz
    ├── 18d6665ce7428af56577451728738362b2eed153.nq.gz
    ├── 193eed7b318a605bb0fca99c972d1998931c1016.nq.gz
    ├── 1e9e8200b201ff600aecd9eb7df1ac6989931266.nq.gz
    ├── 1f2efbfeb80287a7d024ca56381760a535a2deaa.nq.gz
    ├── 1fd7759ef004c66fd920873efb030eda5d1eafe0.nq.gz
    ├── 2104e39150749b496ecfac6cabb266488c4777d4.nq.gz
    ├── 21337d01ab2fe20743682125994666e20af6b7e7.nq.gz
    ├── 2245a2905bdf53083544015620345a175c4fdf64.nq.gz
    ├── 23d2ebef008fdcc00833eba0d9abcd7b9c665531.nq.gz
    ├── 242e9493dff5c26d7f06104b6dd1ca22d8201215.nq.gz
    ├── 249daa89caf99e98b077b58873859a8d25ab6d6b.nq.gz
    ├── 24ab06b1cf60aeba4ade9ab36ff7ad5f73541960.nq.gz
    ├── 265335cd430f986d56040b76bd4f4600aff9e481.nq.gz
    ├── 278f9ad07d23d76052282233f2868254b5ef6045.nq.gz
    ├── 296b22aa966706adb8780e12089d7a9072997a78.nq.gz
    ├── 29b03954d7bb5c21ef8866798153d9a771b68525.nq.gz
    ├── 2ba0641204861d7ebb63524c961e6e004113356c.nq.gz
    ├── 2c391e5986753de7b6d9eeccfe919d543698925f.nq.gz
    ├── 2da6733412aab24841af676f3a127c290253919c.nq.gz
    ├── 2dc9a8bba2f96e592a8dff7367fd6ca7cf8dcf2b.nq.gz
    ├── 30aac2cf4793f3aad92ef0a3c88731198c39566e.nq.gz
    ├── 3271f720a1a7645a301b8d1fc16389cad955d5f8.nq.gz
    ├── 351389a603bf880ea1552861b7995e5a10163775.nq.gz
    ├── 37f4d74c19c0a369f8bf54f177d42d977ee53f52.nq.gz
    ├── 38d29d75efc79b94ac7155f6e07acb3e4d8f04c0.nq.gz
    ├── 3b09212f8a29916959be48a7cc920d423794c60c.nq.gz
    ├── 3d0f0634f72e6483c54857b0dbd72c219e46671e.nq.gz
    ├── 3d12a2c25270a42e66ffad27357d9b8a974bfefd.nq.gz
    ├── 3d65401be5cdd7b58c57d681e28347278942917b.nq.gz
    ├── 3d77d521e83f6264cde310ed48ec462ef1177571.nq.gz
    ├── 3e0c7672ac51d93782f020bba32eb1207617e70a.nq.gz
    ├── 403c8c722ff24ca034973876fa819d37715b9b6a.nq.gz
    ├── 4288962ecef05681db4c62bfa13b2f090b9ce6a8.nq.gz
    ├── 42e6da3a5652fe2e96cdecf3c8c45a63a4cd0798.nq.gz
    ├── 43d2332b79b70bb8ead6d84838e6841e349ec818.nq.gz
    ├── 44d89cf24e1c2aa20c3b4f0e68bff0d15ae3a5d7.nq.gz
    ├── 46b8638107fbd5317d7dc6576cd337e78f48346c.nq.gz
    ├── 49c1aa3c76050cbb8c3732dfa4ba90094d7aca8b.nq.gz
    ├── 4a73ad215f5ac0be2b8f66d55b2aa86d99ed0676.nq.gz
    ├── 4ae00cb730d753aa55da6b08d3e95191562e37d8.nq.gz
    ├── 4c753f1a3b993842030429bbdeccdb48f8a86ebe.nq.gz
    ├── 4d6ab0efa6629b13024d9c153de24a43732949b8.nq.gz
    ├── 53a8693bb0a4fdbef4cc457675e4f867cf64e5c6.nq.gz
    ├── 54565b7bc5a85446ba63081eb4a16af4f50db47c.nq.gz
    ├── 5518b36a7308551bfbf3ec7fc8591273990a59cd.nq.gz
    ├── 55b706e19b98c3f980e54c74c03a365290b79556.nq.gz
    ├── 55c6647eb46f95a82af2881d4943d0457058480a.nq.gz
    ├── 56a31714e566aa29fd85dec5ea3a9716f558fefa.nq.gz
    ├── 57224382adfde9efb310c31534bda30c654c5257.nq.gz
    ├── 579a5fc9e0fd7a04e11e156a6341bf68e209e154.nq.gz
    ├── 57d715242087b328c37dbd6a47217b63b1ed88c6.nq.gz
    ├── 57e29d3fba917799382a539b80566d7494c9e8fb.nq.gz
    ├── 57efe58124eed661c2ff5827258772ab97a44bdc.nq.gz
    ├── 5ab21f0c6d112033069b26647e6537de05df640d.nq.gz
    ├── 5aec82a9d58c4597f84dae6475fb5f23221fb6b9.nq.gz
    ├── 5c0feed1b44534c971832ec000224d513f9d517b.nq.gz
    ├── 5ca9d127edaf7a67158f284d8baa3f5f21db11e0.nq.gz
    ├── 5e6e4071ab015367f8d64710e5f1cca00b50f88c.nq.gz
    ├── 5f659dea00f65275ae43fa8f37b00c94d2b69b77.nq.gz
    ├── 608ef9e8906f4a08d13566f4eaca9d5da0c9fa1f.nq.gz
    ├── 60a8d89b71846c015795966dfaa3547711061cd1.nq.gz
    ├── 60d50f9b3338c74d434d313ff7e480641cf2cf60.nq.gz
    ├── 60e87c8a331b5de9a998a9927c8eb31700d19a28.nq.gz
    ├── 61c76c7c5bc504e0c21d0cea1b7ed462d719702e.nq.gz
    ├── 62258f1495611695ab35009e67183b42a35c4728.nq.gz
    ├── 6273f62d62a8fa280edcfb798a013e0a0ae84534.nq.gz
    ├── 63670467220c7268cb3eb153a109b1caa3bc7672.nq.gz
    ├── 658cfd32004031af173a450bd7c4c7bc09e1b5a7.nq.gz
    ├── 65e9d0cbc8e1ddfc828ddc26ecb74c7b507faf20.nq.gz
    ├── 662dec3794b7c0f799fcb8e9feb1a1f43a3a46da.nq.gz
    ├── 67a5fd08a89eea8e0edc9052716b64ee011ff545.nq.gz
    ├── 67b773171da2dc4a5623f44e40dba573c2f9f8e5.nq.gz
    ├── 67d522cf988ccb1930844f75fc949d7b7017b0cc.nq.gz
    ├── 695b5c78b91edfc29f77823eb642fc9ead8e15f1.nq.gz
    ├── 696957705b756b1457a18c7a23a91affafa17d91.nq.gz
    ├── 69b5b7fdcb3b4ae67ac7f9ee23733a59dac7e665.nq.gz
    ├── 69ef0fe00e8d883539e88596dadd4ba51e2a5704.nq.gz
    ├── 6a2a883be7225417ac14d9496e5604a51bf650f1.nq.gz
    ├── 6bba86c73fca2abda416baa1a7cf883b3494fb29.nq.gz
    ├── 6d1ded622bf0080a120868df69e49971b7174006.nq.gz
    ├── 6d5595401306370d787930cda038499a5c9146d2.nq.gz
    ├── 6e9762676a0d052ac224b72dac12f2b5ffffaba5.nq.gz
    ├── 6f6ffd5eea13b661512f1fe3e8f6cb2d30023e36.nq.gz
    ├── 6ff9ddb0772af1e9c78c13840927eed7e55253b5.nq.gz
    ├── 7032f97be0469e50397f8e88d256802568701378.nq.gz
    ├── 7066da5b557e896d8a6c1285fb191af7bd7914bb.nq.gz
    ├── 71eeb8590af1715896813f9696bebf7d4d806d19.nq.gz
    ├── 7292f67b753795a33aff274e4adcbf561f78c75c.nq.gz
    ├── 7341a6d818760f0ce1d0911147f66fda6d867ff2.nq.gz
    ├── 73f6476d6051d049e7b807217817ff6f51b2a302.nq.gz
    ├── 749e2915271d258a022c32848f0f432d043e1097.nq.gz
    ├── 74e15c90d3c4bd46309713f42a762db785b04680.nq.gz
    ├── 776481488c90d077cd01c7ec8b770fd6ca86de7b.nq.gz
    ├── 77b86022137da79eb2e08a9a554863a8e2d53add.nq.gz
    ├── 788b2fcecedb07801588b0e7f6be89b66e4e1e72.nq.gz
    ├── 794f014c920a6aee2f21ee348e30f38a458e9c7d.nq.gz
    ├── 79ec9b4eeb98501b9b9da8bf430a63cd57818acb.nq.gz
    ├── 79ffc4095cf46f90a30334466637b4df61dfaa5b.nq.gz
    ├── 7a9d8f21b54e6f405c15dea9c43fc56611fb0b28.nq.gz
    ├── 7b5d93bf51f6c6378610782fd84f88eafe4199db.nq.gz
    ├── 7d265b3b5c0e017bfa7270b766d5354feddf1c4d.nq.gz
    ├── 7da32b91eafb368077ef07d67fcdb84180567cac.nq.gz
    ├── 7e5acf9c77e7749e710a8960de27d8eff7d94786.nq.gz
    ├── 7f5c191b2afd1624a653afafad3fef722e864bc3.nq.gz
    ├── 7f90d6bc7c49c73c40ccc1fcd4c144bc5f5c72b8.nq.gz
    ├── 800bf079827b7b1215b9ded3f7d373a5e8e124a9.nq.gz
    ├── 806b76a88b6337c9e0a2ca41ec92f290eb7775e6.nq.gz
    ├── 81d4a1c9494b1c7a26849d2b594874918f04c700.nq.gz
    ├── 827a4e05770f87127cf1333b4b85d24503d6e532.nq.gz
    ├── 83535d1693580f04824a2ddd22bd241fd00533d8.nq.gz
    ├── 84eaad20d4fb19b00965268dd75d7e9b66c8cc21.nq.gz
    ├── 8574479ae1e7cd01cc0b0aaed2f457f7b1669603.nq.gz
    ├── 86f0cecba5b402eba32038fd4865e0f8ce8da94f.nq.gz
    ├── 870f89bb4d3646684bf37e2144c4b83c808ab84d.nq.gz
    ├── 8940c120fbb9705472fe7d623a37759ebc6ffeec.nq.gz
    ├── 89e484fee600190331dff67f6aa3d8bd906aaf9f.nq.gz
    ├── 89e8098441b6b51530e207d902100fb65e194ea7.nq.gz
    ├── 8aaebb623430fcba7801c3502f8f94e46198ddb4.nq.gz
    ├── 8b6fd686ac77ec02919b60d0039254559b8af7a0.nq.gz
    ├── 8dcbdb06e35ad55a11e342ccc052b85a1c807ddd.nq.gz
    ├── 8ed5451d664204ecb9c73fc9d7beae5a976087f3.nq.gz
    ├── 8f9343d0afde424e852148fe93c57d39e4e1133e.nq.gz
    ├── 8f9f20bd3290a4c2858af1274973a9ce7adf8851.nq.gz
    ├── 90773acfa186694f1af39aad32b497d0368c895a.nq.gz
    ├── 9088d176f8ce9f3c4e584dec6c513b3fc0a78306.nq.gz
    ├── 909350435a51f96ecac2a2f789b616bc3704cea0.nq.gz
    ├── 917e15652b18f93d1fc1c41e3696fc1ca4c2104c.nq.gz
    ├── 922f878dde3d8aecead27afbaed7768f5079cdce.nq.gz
    ├── 94235334f25cd5c5e2464d66f4c8ecf8ce161400.nq.gz
    ├── 94eb933444a967755a3aa81ee1d5dcb6435153b8.nq.gz
    ├── 95f4986d400223bad542e5b34a7e6284a039425e.nq.gz
    ├── 96891c2e0b71ef95a50a0c3271c83e5a2123d025.nq.gz
    ├── 978dc076753687eb0c1c91e47d0494eaf1477648.nq.gz
    ├── 979a7190a3ca44c66797f6f994804f825bf82d4a.nq.gz
    ├── 9879c28b908c94d5b0ee598b283da13d26bc8dcf.nq.gz
    ├── 98814fd4c145714602656d17c47eb0dbe0f53d8b.nq.gz
    ├── 9987a775530c0393e7c27b73b1e854b946d5ee47.nq.gz
    ├── 99b7cf92e45497fc8f608777f962dce2148d108b.nq.gz
    ├── 9ac13a98fa5fb4769bdd1e818dd1d07d83f79a8b.nq.gz
    ├── 9ac8a41635e3df3a78f8d02370ad1970ab98cbc6.nq.gz
    ├── 9bb00b7cc4211c89db28d55443910aeab505fe44.nq.gz
    ├── 9be80bafe050eed57029ef2e690f36677a3003c0.nq.gz
    ├── 9c1b57a58579851fd0184f0510631568e7b5fd8d.nq.gz
    ├── 9cb0bf877f3d2145e335b03491cc30dd7a12dc0f.nq.gz
    ├── 9e0c7781025148380d130d6f7b6e590117ad3a8c.nq.gz
    ├── 9f20c78f60b9840da0ad4d0a428d2b0ecebebfac.nq.gz
    ├── 9fcbafdd02cbddc94602902183fc98e305a1ec47.nq.gz
    ├── a0bf3bea4aff5b9c231fadb605b9cc455fe31bb8.nq.gz
    ├── a105aaa5bbdb2663c5dd103534e750671754dc75.nq.gz
    ├── a24ac8659ffd87b1928d85760df28cca912efda7.nq.gz
    ├── a346b5d7e24834806b0871b209637c728fb36d60.nq.gz
    ├── a46d96c7fddc6347454efab6c999a8a4ce4cb9cf.nq.gz
    ├── a49a426ec2fcb279995806adbfd2ed48e781f616.nq.gz
    ├── a579974f0440d3938bd1fb9ea6f95d3e53edf6af.nq.gz
    ├── a589c9ddb247fb07716ad2f0fb3240e2b6848887.nq.gz
    ├── a5e642938c69851ea57d0a4e1dcd94ea1381edfa.nq.gz
    ├── a75ba890fc8bf5fd19bc60f69b64eff4420948ad.nq.gz
    ├── a868f073d8a0e35dcb3ec812b41b1d3f0acdd84d.nq.gz
    ├── a8e51b4567fd49035fd3b570ba7c57f9a48b01b1.nq.gz
    ├── aa767fbf63ec7ddd2f5863d05c03f647303a101f.nq.gz
    ├── ac45ca048bdae8b5741164b46ef439948f18ade8.nq.gz
    ├── ae8378615ec6bc5998d52d87429971d99e2b7ae6.nq.gz
    ├── aebf6e3ac1271528b2aa25c06b6ded762e5d764c.nq.gz
    ├── b0b5171dc627e2484c9566cc808ae405d60149af.nq.gz
    ├── b161300b185919abba6e22dfee577a74dbaeb1a7.nq.gz
    ├── b1ddde05f98458ebb75fecd4283194c91a09a7d2.nq.gz
    ├── b2395720d4c5693213001c449ed09869be9bd944.nq.gz
    ├── b273d54b348adb6ee0df267264250e0e130265e3.nq.gz
    ├── b3025a489a91b4cf986e8873705dd276b44ad129.nq.gz
    ├── b4829671f62a99d3a39d01a77f8fad86f5b0445c.nq.gz
    ├── b54266fba20a167a1d83b7afd503dfd2f849ca57.nq.gz
    ├── b6497bae286e507898046fc580f4551edcad774a.nq.gz
    └── b77a8a8cf95f75e9adc79b62a8b95d201dca21de.nq.gz

9 directories, 200 files
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

[cloudflare/zlib](https://github.com/cloudflare/zlib)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
