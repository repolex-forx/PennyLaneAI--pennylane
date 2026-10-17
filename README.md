# Repolex Knowledge Graph of PennyLaneAI/pennylane

RDF knowledge graph data for [PennyLaneAI/pennylane](https://github.com/PennyLaneAI/pennylane), parsed by [repolex](https://repolex.ai).

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
rlex download PennyLaneAI/pennylane
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9792b3ea46a7b41ab709357b6efc63110e2ccdac
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── 9792b3ea46a7b41ab709357b6efc63110e2ccdac
│           └── chunk-001.nq.gz
└── blob
    ├── 00ba3deb252ebfd89676319ea2e0599c9f432a1d.nq.gz
    ├── 00e337d3b587f7e6d85875e8562b9f83c67c1146.nq.gz
    ├── 0126a6d01849a10fc40be49af94e694d07d981e5.nq.gz
    ├── 01f3a4acbef6258f1841bbda2c435e3e781d9465.nq.gz
    ├── 0213339f24c489b4458739eb41a45c50a04b6974.nq.gz
    ├── 035cd144a16fdebfea77cd44efbe3e95cf60833c.nq.gz
    ├── 04063b3922ec058417b6989e85e9abfa6620645e.nq.gz
    ├── 0471388d3fc0ce4723747f7b9e0ebde21e2be128.nq.gz
    ├── 0651b3911c5fe2bf7f60ed89587c744449673bbe.nq.gz
    ├── 0691c7465ece81af9e65b9a9a82be4a63458cbbd.nq.gz
    ├── 06baa364fbd45f713a097b28e106215b89f7254b.nq.gz
    ├── 073a4733049e590a9287ee6c415909867a6602eb.nq.gz
    ├── 07b3dfe7e5c5f8486400c2fbe56a2045a3f1b304.nq.gz
    ├── 08a8c3dbdc79e9c9bac95593db8046c0760f0b4f.nq.gz
    ├── 08b3fc50009f1195a56212c43b5dab11131ca50f.nq.gz
    ├── 09197228d00d4689013badc5953546da726e8147.nq.gz
    ├── 094bc9b1bcc68b65df171867f6f2c20963d9ae32.nq.gz
    ├── 09becd7e3031d73997b6b11a53849d9bae914068.nq.gz
    ├── 09cc491669922666614610c292f28ef6a14a6c81.nq.gz
    ├── 09ec31b958df8290c4dc86b76fea8ecd24fb7cfb.nq.gz
    ├── 0a7eac4e05ae2ee291be2c8c14856b65c1ee4311.nq.gz
    ├── 0bb679d9f1ec32ac6d8256c51821a44402864d31.nq.gz
    ├── 0c28746cfd1fedeff6f83a818527b7d7c78c2955.nq.gz
    ├── 0c57c9b168c5fdb48ae0f429654b361f4eb7c6e9.nq.gz
    ├── 0d8cf5f80d64a002d9a8ad2abe0bdb1ff578bad7.nq.gz
    ├── 0e0b2e95f2ce6a7b8ff2ace112d91aebd756c842.nq.gz
    ├── 0e56bdb0f3526c65deef991dc5b8e5639bcf90f9.nq.gz
    ├── 0e6bd9a72e6650fa583cd2e86ccc4319e1838858.nq.gz
    ├── 0eaf071ceb8d0a04be5077f5a72aea57ad6a1b15.nq.gz
    ├── 0ed1cb41125966b1fd9caee4af5c4104bbd83bc1.nq.gz
    ├── 0f846b68225a1e0f01831cd2c114262988e937c7.nq.gz
    ├── 0fe65a69167de47ebb3aa6896d3822c87c04e60c.nq.gz
    ├── 11bd2d30b41b770cd109efb26529f2175eb0a7ab.nq.gz
    ├── 124ab58ca1373d7a0896119bed2998f5199b648e.nq.gz
    ├── 132607a9e7c1d821107f9895ed51ad772ed9b33f.nq.gz
    ├── 13a73ea587b37be153ddeec6e468f5ff04c1ab6c.nq.gz
    ├── 13b85e546b324d8ac45eb4b69ca0a0a04500783b.nq.gz
    ├── 13bc52a6be613ca6f02d11e3d6408c8b2495f267.nq.gz
    ├── 140360e70189c8d16a77560c8d612145918ed5e0.nq.gz
    ├── 1473fe02baf7c7aac0bfcf052e84a224fc11b9d9.nq.gz
    ├── 147afeae8cc04b20bd18d8e2dcfc8d0d7f5bf366.nq.gz
    ├── 14aaf18b57aeec573a401a1beddef1f0add6aa9d.nq.gz
    ├── 1500d1b1762af17b4db8f433f6a9dcb62f0b7bd7.nq.gz
    ├── 150312e7abe45493554c7d6f32c2777694241d5c.nq.gz
    ├── 15744c4847e71661046db135ecb5750a82c7caff.nq.gz
    ├── 159f6820f9ace499c50b933f9859f64d8c2f86d1.nq.gz
    ├── 16859a6386bbce5b5bec8dde749cb3e461c9ef45.nq.gz
    ├── 1795b229738589867e7c8544cc4bb824caf3fe9f.nq.gz
    ├── 184bc7dc795ad56cc763b8e6b7a9a6eabdb6cfef.nq.gz
    ├── 18763e920175385a9a6238708ce20e267e5daaa1.nq.gz
    ├── 18984aea6016dd1cdcea466cd697c17b203c8029.nq.gz
    ├── 1917571cf22cec542ef2d6d6daf296471fa3865d.nq.gz
    ├── 1951e73255a052f96a1072ce816ecb9cac929e96.nq.gz
    ├── 199c47b08f0ff4a782980284dbab49e9bb5428cb.nq.gz
    ├── 19fae66978bf78483d465bb3296ab622c0405c11.nq.gz
    ├── 19fd75e9b0ce07d17e5fe80d950cec326dd3bc86.nq.gz
    ├── 1a0ffef6e7f1292e4113db247781a31201083145.nq.gz
    ├── 1b457c236029359b59cfbb56e26a6db78aadab4b.nq.gz
    ├── 1be384c651d654e075471f85ce6d2d39205ec20d.nq.gz
    ├── 1c57bc7e3a32e74423f61ed24d41978c1c3f11c1.nq.gz
    ├── 1cb0074f98df541abd6ab95bf9e2ebfa13245de1.nq.gz
    ├── 1ce4421234bc0e76d795ef6ceff82643c25d8e29.nq.gz
    ├── 1cefbeb491085c40a501f3474b63a0514a3d19f8.nq.gz
    ├── 1d4a022d8b0c1cdb3fbaccfc7b263c6eb0c1467c.nq.gz
    ├── 1da1d0cba607d8608be1af0e4ff3b74e1bc9c9c3.nq.gz
    ├── 202519c61e5d85a3e41e986d12cbd0d8600add4a.nq.gz
    ├── 2035141b09bfe02bae173973112d1711ecd28773.nq.gz
    ├── 2079fd9aeb13394c6c94bfa82a21ec212c3bfe27.nq.gz
    ├── 20b826409d537d69d5f750f19c73fadeb3c54bf7.nq.gz
    ├── 20c6f21ba30203206797d0f05601ff6629f7e574.nq.gz
    ├── 218f2d93ea8474bf419bcd942511eb470cbdd5d5.nq.gz
    ├── 21fef0beeeac715f177025aa7fa3a51f6dc5c403.nq.gz
    ├── 225a382c47ac9017ceab14e94d55f3a0432b9d0b.nq.gz
    ├── 226e49a74a70a3702f8ee7172538c60d7feaf12d.nq.gz
    ├── 2317a6a050f632585279fc9faa1f4a07e4e3f627.nq.gz
    ├── 235f546951a9ebc4cc02b77597f5cd37604c9aab.nq.gz
    ├── 2369c694e5a338c2ac60f229550252594b8537f5.nq.gz
    ├── 2381e9795c131ea4c452f76ebe77cfefa645c57a.nq.gz
    ├── 23ce96fee6bbbd9f0596db2dafe26fed3cdb21a0.nq.gz
    ├── 24e9c702fcebe9204ef80346bca0f12768881ae8.nq.gz
    ├── 2616d07a38294f711c7e0b720b4a6fe1a6ad144e.nq.gz
    ├── 267aa3985811ac274121fec8dd3caa3f052cebee.nq.gz
    ├── 26964d9234b223e08bd9727e412830460481a05e.nq.gz
    ├── 26c05972f88b7952c1717f822f8694aa0d3c527d.nq.gz
    ├── 26e29853a801c0a2087e3e09baccc493f172a89e.nq.gz
    ├── 277a9de0c8ec0a262b3b04fc15142329145a3aea.nq.gz
    ├── 28178ed6747ac1128144af9a9ea502c6d5f0857b.nq.gz
    ├── 292f287933ff2ec20b67c9c7744ad3a998cbd535.nq.gz
    ├── 2962717215482c89e52c2114a86602c200d8aa5d.nq.gz
    ├── 2ad5590eefae4856cc2e153421dce4aa579fb5fb.nq.gz
    ├── 2afb7197ba143cd62b10a27da81f371b68265de1.nq.gz
    ├── 2b0d81caaf99591778e6b85ba573594ff1dd0d23.nq.gz
    ├── 2bc5b0eec4ae879aa7cbaecd45f43a6758c5731b.nq.gz
    ├── 2c2ccb91eb42380f1b103d396067f2cb7a0de4e5.nq.gz
    ├── 2c5542d7cb7b2c50dfaf25ffee5dea803c654611.nq.gz
    ├── 2c58e6963f72f3bf9151c7ecd879d384884cefda.nq.gz
    ├── 2d3e265982cd5d03dbc48cb03fec3491e8aa95a2.nq.gz
    ├── 2e86625eb4701e8fe3b81289b63f28430bc342be.nq.gz
    ├── 2f4e2ef5303ccb2c271dc468c3884d4f73a1039e.nq.gz
    ├── 3008677d470631476914e0dae051870987c9b27c.nq.gz
    ├── 30cc2833df9199b7c96aeb3d520af24287899bf8.nq.gz
    ├── 313d3d962fc6081a987d872865d9a6637805ec1a.nq.gz
    ├── 316744ef594f501c60b2f4b1da22f3af0e96e70a.nq.gz
    ├── 329d82c9eba3376b76f4e48076780c616dbff1ea.nq.gz
    ├── 338baa66c309a812c8613db2dfb91758e3e662a4.nq.gz
    ├── 339b25a81d774cd8ce75ca7b0ff68c146dd02f87.nq.gz
    ├── 33b4524c7e2b13565168a6d9026530e29ee368bc.nq.gz
    ├── 33b61a3cc2e5007ecbe5992c2c219dfa30824f27.nq.gz
    ├── 3548cc219d567b91c01f15e0ab837dcaf0e9e479.nq.gz
    ├── 35a84f4d0cac7bb06d3bb703a7f8bc09054a5f30.nq.gz
    ├── 361f41afca101ccb654f51875da6203e8b8321c0.nq.gz
    ├── 3840ec9c7c7279cce8fa7ae9b6b4cc9d3441765f.nq.gz
    ├── 389e111b40095edd2cefec52f2f2d1c3db634c37.nq.gz
    ├── 38cdc841adc151384658da52c904cb6cc1c27d5c.nq.gz
    ├── 39348ff478eaff689c6db8c12e2757bee10d9b8d.nq.gz
    ├── 3962797f7659bc1e189d40a49f4802b87267033f.nq.gz
    ├── 3967fc400781d9dd011737df3f7976b11e1b8531.nq.gz
    ├── 3a078cdd56ec8909025e475a003be72b6abc8c45.nq.gz
    ├── 3a42f42fde9cb217acdd461d00d49a9bb4bf64b4.nq.gz
    ├── 3a5659d20d6484e60303ff203048662938a85430.nq.gz
    ├── 3a632f74a8c1d9e4320d42b0295844ea30710f5c.nq.gz
    ├── 3a7686feeae95ac9c71af6a309002e6ea2a53cdf.nq.gz
    ├── 3a9c3793749e3bb09035fa5de89941057d83d2ba.nq.gz
    ├── 3b1a1368ebedbc30b90150734c67b1a594daaa39.nq.gz
    ├── 3b2c580a363af56bd7edaa9f611cd9ac72ab7b9a.nq.gz
    ├── 3b33c6f7a5030f404baea7da744ca01998dd05f0.nq.gz
    ├── 3b3507ae3ea41c69b47269c17df67b3cb7bf18d9.nq.gz
    ├── 3b76c86c00d3cb5737be691c324604c389b960d4.nq.gz
    ├── 3e1cbcd3f7469540116c0b960bcc0642bb7f3bb2.nq.gz
    ├── 3e241d6b3d722fd88526ed095263f86f7e59cc9e.nq.gz
    ├── 3e7d23bb5b9ec159b6a41f3cf1e02a0cd3c5ee63.nq.gz
    ├── 3eafeb4d4c13ec7b3c591907c0ce16f3fd18ec45.nq.gz
    ├── 3f61cbef3f5d938a7a4efdb33c2f3c775e201ce9.nq.gz
    ├── 3f9a75432fa154e446f2b106f7cd3202ff3164a3.nq.gz
    ├── 41712a781e5180b5622ca8c5789c06e659079501.nq.gz
    ├── 41cdc4eee3a26397e9ca20e93e6f9f6c57918faf.nq.gz
    ├── 41d3342fdf39575f6315beb9205c4b5c3408023d.nq.gz
    ├── 4333d2d41fd8d0a84c661498344f546362b2ce93.nq.gz
    ├── 43775c13ab1718712b0b0b7f975618117bc8e801.nq.gz
    ├── 4381c4ed1052a69ea966a89bc554efc250f64578.nq.gz
    ├── 4388ca994d2c177c80997d5238b841b2fb323041.nq.gz
    ├── 453505309b7b9ad8d3785af7819f9406babf2b13.nq.gz
    ├── 4547e6a3807505fe15611d5b15b0493bf891c922.nq.gz
    ├── 46c37fed96a192e387bdc176894ece581f0bd907.nq.gz
    ├── 46cccac44af3b6e1419e3e10fbdf38a16d2ea34a.nq.gz
    ├── 46fa5ee6659acb39b910c75138aaec2787192e6c.nq.gz
    ├── 4764b0b2151d21a0a2f046c0f4cb9b1a0eb63299.nq.gz
    ├── 49a31843f1cedfe6009e87f729b93a14b6715f0e.nq.gz
    ├── 4a1fcb62274db2c01208369e9750dea3ca000d10.nq.gz
    ├── 4a6ce5d22ec7f4be00adb6b63c6c868ae11e20a1.nq.gz
    ├── 4a88294df568a983618791975572c91d93c75da6.nq.gz
    ├── 4ad9f1bbda54a8e09bfdd0a1b5a7feef2edbecb3.nq.gz
    ├── 4bf7c31fbaf5e7c48fe4c22a3db4da5f9fbd1ee5.nq.gz
    ├── 4c73629d6b4e2e30a7e8fba731d119c57200e25e.nq.gz
    ├── 4d6c2dd77001058e140e46e30f79fc66eccb8bb1.nq.gz
    ├── 4d8fc8fa1146c0d1495d2f996800bf0748e3b34e.nq.gz
    ├── 4ddf7cf1d87c4e14d01acb5075428658704fd272.nq.gz
    ├── 4f6b08f20cae06bafbff5f84b1ed0cf27190e99b.nq.gz
    ├── 501f8f270d5a8301af9b5c290bba91ba1bd31948.nq.gz
    ├── 50504816944e9165ebb91565c45cfd7841f3ee82.nq.gz
    ├── 51105162be7e0c79a0982545fe3f251f97030232.nq.gz
    ├── 516d532c836a9ca14af036098b83a5acb074329d.nq.gz
    ├── 519c61001d6ae510f7ddb7a4324fc61b33ab9909.nq.gz
    ├── 51ca6f39713d2166398321fc9f9f5ab828f5d460.nq.gz
    ├── 51cfc3c2ea5c90c0996a3f0024aca347ed6c1c89.nq.gz
    ├── 5344a4f29272bd993cfd0ef9a2dfc4b8bfbc7e5e.nq.gz
    ├── 54fdb53cffabbe6a116b5bf2d5bb6207e9abd417.nq.gz
    ├── 550a0460309c2674336128300bfdbd3ee9bad884.nq.gz
    ├── 552c8d0b70326e8eea4096a66bdf971275c60372.nq.gz
    ├── 5597370d3333ff3e4c5d9b0197d3ef487d2d169b.nq.gz
    ├── 56c599dbf2794cc792df99fa552c2aeb70b0b298.nq.gz
    ├── 56ceed64e8a81c988ba7fa89a1f9fe75148be57d.nq.gz
    ├── 578be7c38e3c4988c4f12091d6a61d30412f58a0.nq.gz
    ├── 58c8bf5994a431d026a4c397f24be5ec35019b08.nq.gz
    ├── 5949ee006ee9f6dba9c1cb0059b0dc83a2d3bad5.nq.gz
    ├── 596638c64d0be43b27d9b2dce05fb7513e6c372d.nq.gz
    ├── 5996df4bd0a44567f5743b49c12416b7ee37a3a7.nq.gz
    ├── 5a1772da3774741823d84db11211904ac80d5d80.nq.gz
    ├── 5b3d94d112ef55d119173ac44d09c04821eea055.nq.gz
    ├── 5b3ee7a490ab23b5861e15d85619cfa96de5fd9e.nq.gz
    ├── 5b6b3c281bb65bc6fbd287d3a2e74a5839633d9d.nq.gz
    ├── 5d1d0a2f7a11a22a5694ba963dcc4042afc6e2ab.nq.gz
    ├── 5d6d772fad116e29c0c5bf4563ab3ca830a426b9.nq.gz
    ├── 5eb740e904c1bc11f540a9ac14a59b8ce8df9770.nq.gz
    ├── 615a7eba3f25cf894478b93eeae42896b9c1b3ab.nq.gz
    ├── 615e4c14ccbd72117c757f74c5fe198a0ce35136.nq.gz
    ├── 627761d17397328ab06b950a3932fc75ac948a46.nq.gz
    ├── 6297ef50bb70e61243bdcb6742ef18518858935f.nq.gz
    ├── 62c2855bd87356c003263f1fb1ba5aae4b9520a3.nq.gz
    ├── 62d0e109e707e8caf3db9f7c24780adcc7b50341.nq.gz
    ├── 62ee845986893aab8c8a593368fa2b931948e6c9.nq.gz
    ├── 644934877618c57bc232ccca70f2bbc33ec17ad6.nq.gz
    ├── 644db1cf2226bd07f3a70d2463c75951807a0aa1.nq.gz
    ├── 64aee8bffc75ce0575c894958cefe1ea9f8e8dfe.nq.gz
    ├── 6545b1fc9b52dee5a8ac000be8d22725c94386c4.nq.gz
    ├── 65cdd1be5b355b0c1cefbecdf0d24ee09198852e.nq.gz
    └── 667ac0750ac5e4238d8fd96f683ef108e160bc96.nq.gz

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

[PennyLaneAI/pennylane](https://github.com/PennyLaneAI/pennylane)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
