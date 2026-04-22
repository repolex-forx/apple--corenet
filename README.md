# Repolex Knowledge Graph of apple/corenet

RDF knowledge graph data for [apple/corenet](https://github.com/apple/corenet), parsed by [repolex](https://repolex.ai).

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
lexq download apple/corenet
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a5fa11a33f505c1ddce03a609e75ba667754afb4
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── a5fa11a33f505c1ddce03a609e75ba667754afb4.nq.gz
│   └── repolex
│       └── a5fa11a33f505c1ddce03a609e75ba667754afb4
│           └── chunk-001.nq.gz
└── blob
    ├── 015ff820881a3880f94463054e2d977feca770df.nq.gz
    ├── 01b8a02c027d6b4b2dc4990cd669320236298cd3.nq.gz
    ├── 01c8e6b301e6363ff632f9b49e4e2ab9a19acc97.nq.gz
    ├── 01d10fa27caaa69bceae7e2ab3f9ae822991c004.nq.gz
    ├── 01de538afe468a39491f62d847e325c5da8aee30.nq.gz
    ├── 02fa0ad0740b5b47ab66682d0ae2efdf734f7221.nq.gz
    ├── 0397343f51f83607354dd7159fbd8c18533b167d.nq.gz
    ├── 03a7681ccf1c890555b94f1f8c422d8e00c1a77f.nq.gz
    ├── 03a91ece843b7469851c8222fd157868d8f781ea.nq.gz
    ├── 03ac0ca3aad46ddce92bda5be9c9f6f058187ddd.nq.gz
    ├── 04883c1b092e40f01b448c831d5bb98c9a156434.nq.gz
    ├── 05ee78106974bcbc6f944d84117ed6e21015eb10.nq.gz
    ├── 05f5e37d37bdb53d617b83080be565fdf49ac781.nq.gz
    ├── 067e63639071bf8ab1801d71b162205f88293a73.nq.gz
    ├── 06ae81a76ea2206d05b05a0ee2e975a1b0db9558.nq.gz
    ├── 06ddf4f462a0c7e19bcfa69d7c59c71d1c846bf1.nq.gz
    ├── 07354c2a8f2fd4f9a6d1426a654190e93237d316.nq.gz
    ├── 077eb9a1e6e1a4919c34f7c3bcbb484d3ff64cd4.nq.gz
    ├── 07c23b4735ed0577b3e1becdcc1a0670e5e7af63.nq.gz
    ├── 083b98e8a903d2f56cba269d43b2a5c9f911da96.nq.gz
    ├── 083c8d06a746df173cd36da5cb0dd6d30d3489e2.nq.gz
    ├── 087f03c5216aca70f64f6422397d8661d86be865.nq.gz
    ├── 088d57cc9d7db79a72e08379a8c7533983585b23.nq.gz
    ├── 093642475fa4c34af72fb4c8e96f3dafef428945.nq.gz
    ├── 094e95a6b6609e878d1b47f56d5bc1e11c4a092a.nq.gz
    ├── 099bb51757a40a6d605af0bb323a61f940d017c6.nq.gz
    ├── 09b2b0be3260396198b5c277d7da2722b96c915a.nq.gz
    ├── 09cabdf21e02cf8d89940f5eeec1e9d242871494.nq.gz
    ├── 0a1a44ba3fb24593395eb93da3e2b9b761719034.nq.gz
    ├── 0ac85c6280d05248a0e7fc19c028bd315af89b6a.nq.gz
    ├── 0ad1cf3ac88cf091df1f1a32b5887247185d99f8.nq.gz
    ├── 0b5a06821eec237862190f7c84e6d2f4deaeeac8.nq.gz
    ├── 0c883419e5d6b44596ebf080fe1d7022c9bbb3b4.nq.gz
    ├── 0ddb44a4afc084d93f9878f3fd053b00403919f1.nq.gz
    ├── 0e539e0d932a1a6568030087c93b8ecd7ab2ce3d.nq.gz
    ├── 0e6bebe88018efa39d66a7054d02a574daf8c85e.nq.gz
    ├── 0ed92805ca29d9a957d07a957de66a4c8515cbff.nq.gz
    ├── 0fee6d72a67a360c2e90bd61f433d884d479ebb3.nq.gz
    ├── 0ff112c4748472d886efcc1dfb48b4a801a88b28.nq.gz
    ├── 1027800c838b3a6dde68a46599923e1240379ec7.nq.gz
    ├── 107b8f816677a07cd8318febb711167528713f8c.nq.gz
    ├── 10d12375062b939eec94c56e144d5752bc54c999.nq.gz
    ├── 1195fa9e71e9c37f1f3ece90e0cccd469427612b.nq.gz
    ├── 124fd605b118dc95ce130223220d9fcf8e346c49.nq.gz
    ├── 12724f41f74b9530c8ccf99e2db3be2b0cb29ec1.nq.gz
    ├── 12a0acd3f03c97c75e9aab26c88c614566d4d5ea.nq.gz
    ├── 12ac560c089c8373b45606636b8275220dd243dc.nq.gz
    ├── 13d5695b3e2d53e98d69130283d99f9acb644dc0.nq.gz
    ├── 1430036c285964d2180403aa7142b0deaf652a79.nq.gz
    ├── 16296738cb6a996ab1aa4f4dbbe0f4e63fd6b19f.nq.gz
    ├── 162ac9915b32dd27cc70685e3132fb13450f37c9.nq.gz
    ├── 16db6307e3850048e36d664987c1d052c5a9df0a.nq.gz
    ├── 17c49ca596fe9c4eb2c1eeb4cba008132b837418.nq.gz
    ├── 182f21829b8ddcf0c47588daa5bc22181fbb98fe.nq.gz
    ├── 1832aaf01f2c2c716a7169c34610208eea5bfeab.nq.gz
    ├── 18c5f8ea417d49b820337be99247f7863d66b0ea.nq.gz
    ├── 18d06e2acbceecffc2b0f7f14e69a78b6cb04856.nq.gz
    ├── 19869f5718e0f69d149a12c183e0aa4cf8eb1ae6.nq.gz
    ├── 1c08ec76b3d3794abf87babb6d74b3e634bf8e5e.nq.gz
    ├── 1c255933777a85e7d39939c72276cfebc7fd4196.nq.gz
    ├── 1cb8af6bd29081911181d602e6262d3d0ff19d64.nq.gz
    ├── 1cf28c4e18e1feac86bfd72fa166bfd7481a6a3c.nq.gz
    ├── 1d5240b78346546f59f43ba21652244c50b0e002.nq.gz
    ├── 1d904570f89ff3899e956e10063a1401603dfd97.nq.gz
    ├── 1e95addb7a494ef03686cbfec3b4e9c22833ac64.nq.gz
    ├── 1f1ea3d2980a24d3f55292d83aabf243004ce344.nq.gz
    ├── 1f4cf6c37ec8a5d8eae85972043b1050fd7c2574.nq.gz
    ├── 1fc203cf7006dacd2fbfe8dcae1808ec2103ad84.nq.gz
    ├── 206ca595400b91cd534e24b3ad1fd64590dc31a0.nq.gz
    ├── 20db7b69f991128f820ea68a9300b54a3c999e85.nq.gz
    ├── 20f38051b691dcf559a1a9a5bf2e9fce2ea80650.nq.gz
    ├── 20f4e08d252b5444292d05fae1b9ae5e7913ba88.nq.gz
    ├── 21195b99cb50b7c1e82cbd26d5587ba45748e06b.nq.gz
    ├── 21a594ca789879b0ed9f0f9428cdb5d5800566a9.nq.gz
    ├── 21d5c4b789049bfb0c58f1ed45e22417cd3462c0.nq.gz
    ├── 22459ec554e628142238e23eed4c16610e8e45f8.nq.gz
    ├── 224af9298cc3f4279528b621d576f9d37e9419a1.nq.gz
    ├── 22d1adac5338a8b78347e8684a8d2e4c8874e3c7.nq.gz
    ├── 238ab51fd74e64798c26818bc3f42347643c3d6a.nq.gz
    ├── 23ef399fd19ae3ab8ffe7c75686768a3ff70bf96.nq.gz
    ├── 23f6ba146f33e7a6ab970912b15df07d0d692aa4.nq.gz
    ├── 241fc8d328379f45f2e65ddbfaeaff6f2279b652.nq.gz
    ├── 248f92c8d6c5a910cf67bf9f95b171b76d84cf1d.nq.gz
    ├── 24b7b6311ac4eea6dd422d4b89b628618e677374.nq.gz
    ├── 24ffc92e3832d335088d242194d2e6c714eee7ad.nq.gz
    ├── 254af58b9a7ad940b9b32617e170d550dce39eee.nq.gz
    ├── 25e167bf037f2d4715eeb4b3029837dbe2e8c82b.nq.gz
    ├── 25e6852f4132cf086d5668c1a38a78e1565c1483.nq.gz
    ├── 268cdc9526ce686382e821ed324fbdffc8296d47.nq.gz
    ├── 26934c1d65bd4cae8bc0f56ede8dd29b2b6f44da.nq.gz
    ├── 26bc2f4d0654627c3faf9262cc235640b6c8e549.nq.gz
    ├── 26e54965c77c1538d57de767f0d9a90ce3e577a5.nq.gz
    ├── 26e85543e55b36f4120b5f1d1c3fc1cc3cb9661a.nq.gz
    ├── 274e5a7562146084f2ceadcd28a2baa3dc8e58ed.nq.gz
    ├── 28bfc5ba7faaf61aad6e3ecd0ce7eab60117b996.nq.gz
    ├── 28c23c63ff6c5359015e52bce5ed7a4d147d15f1.nq.gz
    ├── 290021adb9568779787b629d78457e736a7ebc40.nq.gz
    ├── 29737cb32811909aa961cfe90bd143039893aca4.nq.gz
    ├── 2a1b45ae0048a5c6205594bf9712132b07b147d2.nq.gz
    ├── 2a2641650b67ec9b8e463139195e6747cd225a64.nq.gz
    ├── 2a558aa2a51975a8e68a65c59ddf7187b56fcc34.nq.gz
    ├── 2ad7b71aadeb6796608040c760381bd7af210e59.nq.gz
    ├── 2b5127c78c1c2d43f230fdd8fb63462e8d31e971.nq.gz
    ├── 2b8eb8fcb22824d75a1d39935153a9f4baa851cf.nq.gz
    ├── 2bb8149cc7acf002436b2021a5f4d646ef89bf07.nq.gz
    ├── 2c01e2a7b609b2cdfe9c3af8162905fe4e4747d3.nq.gz
    ├── 2c17296c422032179ad670d70f24792d0c64079a.nq.gz
    ├── 2cb05caf200185c2a086e132336305d0af7631c4.nq.gz
    ├── 2cc04aabeb2b5fbd993d7c14aaae55217394d27d.nq.gz
    ├── 2ce38831527efc0ccffff21720f262a3338d978f.nq.gz
    ├── 2d4b9dcac3b81aaece028e892b3d50cba6601972.nq.gz
    ├── 2d4f2f5f6f5b83c5fe06c4aedec96b3e4348e160.nq.gz
    ├── 2e19b1c01265a8572085f72d40b8e6535448ffa4.nq.gz
    ├── 2e89253accc76bb346af63eceae812282389b61d.nq.gz
    ├── 2ea23744acd06d0406a2c28f20aa9d74710555a2.nq.gz
    ├── 2eedea103b0ca6ecc315c9602f9a8cd4433d4d8b.nq.gz
    ├── 2f526534339eb553dddb45af4747387f615f751b.nq.gz
    ├── 2f61787a3caee05a8089f51be02556302e600596.nq.gz
    ├── 306d278f3e2b76346e81bd02b024eeb4764626e4.nq.gz
    ├── 30e7db6d6d12f2ab4db7e0971065da004e66cf5c.nq.gz
    ├── 3110d150de8ad25730d6cc9b39b201d034901ae8.nq.gz
    ├── 3167c409e9288513afe2ca4bf78c0fe594864611.nq.gz
    ├── 3175a2739a30908ba9fc6dc9b164acbb412c70a0.nq.gz
    ├── 318eefcb8019b32b85dd3b9b51788fa436e58fdb.nq.gz
    ├── 31bd4b5188c8bc5ce84f4f4c6fb8d433b2b4f24b.nq.gz
    ├── 31c926245ff65ce0027881ecf2fe221fdeafa4b6.nq.gz
    ├── 31f355804c57048da9f634b0ce64a617f8699a54.nq.gz
    ├── 32292ef184fec56c6833db2b29878b27095f1eeb.nq.gz
    ├── 327d4950dcf40e14b34418d0b476567973130e7d.nq.gz
    ├── 32b864ea15248cdcc1d3b12c1ba9104fa1359aa5.nq.gz
    ├── 3307d6b60da80ad553160a3fb7d457cb7761d927.nq.gz
    ├── 33166f4b048be8c88b52bf64bf10a61143dbab33.nq.gz
    ├── 33bcd94b6cb78ad9b1a751021e1aa91fd2465c29.nq.gz
    ├── 33efc241ae14fd96f23149407f422d39b671df65.nq.gz
    ├── 34adff2b40a3a30ffffbdce70fed5c7732a1cdb5.nq.gz
    ├── 34c596fd3d95cf4d9171e18fbf1cda2f6b39d79f.nq.gz
    ├── 34db3e23f9200abbb99c636d0ca3a68b644bdb5e.nq.gz
    ├── 359df77b48b2af6b8f372348486dd8178e1e80d5.nq.gz
    ├── 35f6ca01f660680ce1df7dab85c46d63ebd0efe0.nq.gz
    ├── 3630fa2bb99c9154a74810ab96a07b2f2ed2ed8a.nq.gz
    ├── 3664a9e2e1f6b6fc13ff049c26ba2192cca60af6.nq.gz
    ├── 372af7f9838dd13faafd12563138963a2911321f.nq.gz
    ├── 3745ff449a1c2b5cae2d9ae504a9432e2179f96c.nq.gz
    ├── 38838329cd72bc85bd705ce0e120f7052292b460.nq.gz
    ├── 388dc39faecbee406de42351d534afee14bac409.nq.gz
    ├── 38926c993cc06b42e10590440c54c7a3a666aaad.nq.gz
    ├── 38b2360f61927d7a4079315e704745857bd4bdbc.nq.gz
    ├── 38d297510d18f6f3b84bf252dcdc65e2ca480c53.nq.gz
    ├── 38e08c27ad8f4dbbcf6571e8b8955cd327e3a2c0.nq.gz
    ├── 3906a819589510c4ae014f4b4d443ddc969c36a7.nq.gz
    ├── 398618a50fba679f61e1c844a471580c1a28ede3.nq.gz
    ├── 39d0c256860a9ddbf8f4b98dd156693722e5ccfc.nq.gz
    ├── 3aaa00a5f948ea7795a8cec3510f59c3df3fac86.nq.gz
    ├── 3ab800f3c53ffe1ff90887f9436dee0f95c78ae0.nq.gz
    ├── 3b05f80a045579439eceecb83479200cab10d9cb.nq.gz
    ├── 3b91dca60b2e10f87d5f35f2bc9a584c2387ceed.nq.gz
    ├── 3bd4f8c4d66737a5de2597d7835335779355c367.nq.gz
    ├── 3bfd8afc48247f8b6732c9c71695537dd6923ccb.nq.gz
    ├── 3c8b9751def78e90016dbcc2d2537e7695ed5459.nq.gz
    ├── 3c9b5a51a5cdcb582799b684d9e0fa1fb690d28c.nq.gz
    ├── 3d173aaaa45ab281adf639b5b69107cae475f9fa.nq.gz
    ├── 3d2eb328cef5d8bd4a08bee3473e7e752bce780a.nq.gz
    ├── 3d4ecd534cdae6601fde2e4ad206b0b7d23ddac5.nq.gz
    ├── 3d98c1132684e9e5bbf3aa059f2dff93aa67750d.nq.gz
    ├── 3dfda087fdc3e84e29227ca4ab6a22f35bd87302.nq.gz
    ├── 3f0bc0aecc5127b3760e6816a3db7df5f00d2952.nq.gz
    ├── 3f6af906eddf0f4f8a602ff85c8734a016ce821c.nq.gz
    ├── 3fe825ce0ddc16d4e357462bdc3060a867d87829.nq.gz
    ├── 3feb3c75ad8dba796ced89c39b1185a9e0d71713.nq.gz
    ├── 412d6169cda878a9f4b4e3cc6271b2cd0a20fb9f.nq.gz
    ├── 4137d61615f5fcb5f28c1c943a8e725e34b7434c.nq.gz
    ├── 41d1ccbd64aece0dea1749d725efc4d43d57ade6.nq.gz
    ├── 424b47e532ad9aa2007bd95b00fc4eb026f653c6.nq.gz
    ├── 4265e836b4bb236c0d46bf50a5788310450b1803.nq.gz
    ├── 43cbe1c7f9197af6be06ca7cee82a8ef23755625.nq.gz
    ├── 447b8d79c7481cb9bbb72fddb6e2c6b39bace396.nq.gz
    ├── 4549e278080b5278f91505f60db56d5c44e89302.nq.gz
    ├── 458e86a481bdc809613f1889c79d5d9d58d1b3de.nq.gz
    ├── 45913eccca483dcf4baccedc04a1142eea9a4029.nq.gz
    ├── 45b65a550f2fe5e047ddfdf93fcebf7dd7470cfd.nq.gz
    ├── 4784e8a01e0bc8d37d8bc061e4542eb9d7698261.nq.gz
    ├── 478d11abab770fcf119d113a9831603d31315d84.nq.gz
    ├── 490a120a8b5e90a11776a87090bbdfaab4fd9a8f.nq.gz
    ├── 497b8ce3469a2f3a99c7caeeb038b06465603a89.nq.gz
    ├── 497ee9c1e504d076002292ee52b583182ba867e4.nq.gz
    ├── 4a8dca52a0e799d0fb947335196bcf60b3f1560e.nq.gz
    ├── 4a8f229d4679e6de632ad356c846e938a8eeff6e.nq.gz
    ├── 4aab8edb15ab9df3df5c6cd1de01eaa29e4e83d2.nq.gz
    ├── 4aaf0a8e45ac9f1f1c9e220dafd06e373ea6caed.nq.gz
    ├── 4b4c90e0ea8e4f5aa0a6847bec2279bf6ae10fa0.nq.gz
    ├── 4b7fb5c3c1d08b37fa87a13dcb97e4a1b618140d.nq.gz
    ├── 4ba3d165286096fbb3f61c4d1f836af09d5f56f7.nq.gz
    ├── 4bcfc1c61503c0eb148eafa83d9292d7eb866ac4.nq.gz
    ├── 4be2022692cfb02f9eec4b65d3429d4b1a16e549.nq.gz
    ├── 4c5a4856446ce735abde4029f4c41a1f336be8f3.nq.gz
    ├── 4c77db37b2cc9b8c3457cd815fe3c5278bd8f505.nq.gz
    └── 4c796705992d098fc373095274b58768d00f74bb.nq.gz

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

[apple/corenet](https://github.com/apple/corenet)

---
*Parsed on 2026-04-22 by [repolex](https://repolex.ai)*
