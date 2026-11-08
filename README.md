# Repolex Knowledge Graph of canonical/snap-openstack

RDF knowledge graph data for [canonical/snap-openstack](https://github.com/canonical/snap-openstack), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/snap-openstack
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 06c3597a4731f3f2e6131848df74eeee4dd30a73
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 06c3597a4731f3f2e6131848df74eeee4dd30a73
│           └── chunk-001.nq.gz
└── blob
    ├── 005b6db0d48acf28330ad53b11748f47cbeb1433.nq.gz
    ├── 01255d0387462acf830626bd6fe408778bbfb4a4.nq.gz
    ├── 0192c7a1eb22f2fa53a3fba85009e6dea0403cd4.nq.gz
    ├── 0367951ed179ad74523ede86c2c285ac953d2d36.nq.gz
    ├── 037dcbeb0cccf29bc2fc1a85b92b889392740967.nq.gz
    ├── 0516e575f7d6f83ddf37c8a0a74ae7066a9513cd.nq.gz
    ├── 05373a73d3dee4e05b7915fc97c7345ec4da2a5d.nq.gz
    ├── 05e6124908cbddfed79f9e62275aea9898049c93.nq.gz
    ├── 069d54f74c3a9fd5e921cf1444aedc38db3ac8d4.nq.gz
    ├── 06d5e251b807276d9f9305d9aec7decdfb4f8efb.nq.gz
    ├── 07d975ccb773193c64e6abb0a1fa1646867498e4.nq.gz
    ├── 07ea9684d4612340b125bf3a2382c57f98670d1e.nq.gz
    ├── 0822e4410e42e2447d4c78ae6f8c4ec162e8b6db.nq.gz
    ├── 08e93b11e082ac32a681f311b1892463cbe0b255.nq.gz
    ├── 090636cc31e44543810b8ac71de708adf51756f9.nq.gz
    ├── 090d829d5bc17d834daea6c628a68d83c16d00a5.nq.gz
    ├── 09313773e4404715c9f10fb4fd5315272dfc4d81.nq.gz
    ├── 0940b224fe40847d5143ea6225da167e46a23aa4.nq.gz
    ├── 09c669f95db42d6706deb6b2261cb2f61153c1c4.nq.gz
    ├── 09f77caa636ee5927bd43336ff5a6208e9c2fab1.nq.gz
    ├── 0a3bbf68591cbf7ee445379f51ec0e26d27c4f8c.nq.gz
    ├── 0a8704dc6bc15feb7b607c98430e4eaf450a8cc7.nq.gz
    ├── 0d1e6a432cab1f86824173781071223108db3cce.nq.gz
    ├── 0f188b0587b005393867b3757af94f1cf9e757ad.nq.gz
    ├── 0f9a21196d18bb3b740f9be83f1fa0c6064e4f8d.nq.gz
    ├── 10ded825dccb74d05d07cc6344be5c14bab600a1.nq.gz
    ├── 10f0fc0e048ea04b9f18b8873c97e1e7782465a9.nq.gz
    ├── 1119f254a90bbe6b467d66537ff4446c117f5d19.nq.gz
    ├── 1124c04a126e73cdc9f16e1a84ef2fca4c26fba4.nq.gz
    ├── 11b4e7fba35676e0c76e672c7cc08b9167b06bf3.nq.gz
    ├── 124b6b8db49031f16d4c63e62115c24f21660193.nq.gz
    ├── 12519b28dee527ae3fef56e8198205765b62ccb7.nq.gz
    ├── 12d9d1c64de25f83215f3b80f0374937e4fa1429.nq.gz
    ├── 13a1c96434f78c73ae7840aaa92880afb48f8cd7.nq.gz
    ├── 149586c85d36c3a49b003c6c75d78120ca612205.nq.gz
    ├── 1599aee3c53e275ea1aea88cbe3f6d4ae8444b8d.nq.gz
    ├── 1675e5373e74d4ffe1baf6c7e765da0e905de7a2.nq.gz
    ├── 1686cc2785c73efade7235f84d03736bc72eb33e.nq.gz
    ├── 16fea422cb9dff9faa4075d8a430c4e01545e75f.nq.gz
    ├── 1a563225f9812290161fa9c5657ab74a17037018.nq.gz
    ├── 1a670f61264072f61c4a68d91c804e0bfcfa6686.nq.gz
    ├── 1ad50210a8a5fa40ac5804a81d847be1a7cdf03f.nq.gz
    ├── 1b710637a104521b37c519a7a3cd0f14449d8dc3.nq.gz
    ├── 1c65564e1c0f9ca60abf0a84b16e4ff899d2707b.nq.gz
    ├── 1c8e010637f9f7d0cfdf364557d277b49eaa0d84.nq.gz
    ├── 1cc195e3a492cf6d4a7661f50b11ee1473156881.nq.gz
    ├── 1d4874637b1be80284def707b0044ece29590b34.nq.gz
    ├── 1d85c4b086a22eab1be2454e9a83b8f7f829638e.nq.gz
    ├── 1de7e6686558b3279603047f91654f43920c8aae.nq.gz
    ├── 1e243d41dc9918f893156efb6760aa47a291c752.nq.gz
    ├── 1e4d02392da5d148b67e3dfb40d856f8f762e291.nq.gz
    ├── 1f444b1fd339084d60b71ae333dff012c567f505.nq.gz
    ├── 1fb43f56c5b12ad228a8fbfaa2ee1747f5c33834.nq.gz
    ├── 20a8c28f9b799ca91d2f69c1888960de24400488.nq.gz
    ├── 20d74e88b2153c48e61d00b36ecd3c5cfb9485c8.nq.gz
    ├── 2165df83c37d80aeb46f190bf3d47036d58d1b2a.nq.gz
    ├── 21a50a66698090cea4fb6311fe2e75bf35d1239f.nq.gz
    ├── 2223dbb880cb6ff91820b4c639802d858a1c71b3.nq.gz
    ├── 226d08365ff8973c700e2541e7c364bcfae341cb.nq.gz
    ├── 228945e2335d2a6749d3ffb6eb271e0e7c8f0ecf.nq.gz
    ├── 22976ce09b81d1e60e698afbb74fd74021292998.nq.gz
    ├── 22a1c60bd7ab2c5b3f13e94ab010c1aa62e54b96.nq.gz
    ├── 2304aaa890e3fb6ea825d124fdb6d6bd39cc4716.nq.gz
    ├── 231c0758ed831724cef25618a04f9268f8d3962f.nq.gz
    ├── 240c668f578106d58da92fe5172b22e3e9d58253.nq.gz
    ├── 242b3706f3af7dcc96e19151f410c641119b7535.nq.gz
    ├── 24455feeeb31c1ad5968abc420a5dd1e5f8f52cf.nq.gz
    ├── 250704ef047afd28319e84d345e3238986dfe61d.nq.gz
    ├── 25f5f8bc869c119e203865127410290bf6145f4c.nq.gz
    ├── 260bb0eab869255e72013e11966d331c990596ba.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 2703cb76dcf731e8f660da16acf27ad7830bc9bd.nq.gz
    ├── 27db4d5f24b5d585a6e05ff6dca283dec69edec2.nq.gz
    ├── 2854001b5f1827b258c0296848c97b0447fbe82a.nq.gz
    ├── 2907699472c89f4de7f9b33476322af7cfec4d96.nq.gz
    ├── 2b39674d621a99b7ddad71badc98763899cbde69.nq.gz
    ├── 2c966c490a2e13811b777a6da519026101ccd385.nq.gz
    ├── 2cd074e44818a87c75fef0e820ff529667364f5c.nq.gz
    ├── 2cf002ffb9123d124732cccaa36168268d115a9a.nq.gz
    ├── 2cfea3cb58ee1c1b3a06ef0a6c50a258af750f94.nq.gz
    ├── 2db363c43fdfaf21b8b7910817d67b3775d924d1.nq.gz
    ├── 2dc05e9b0203f65ad78149f181f4e45d5d06f188.nq.gz
    ├── 2dd6a80157a9d2f4b3c8fdbdd35c20518fecc05a.nq.gz
    ├── 2e6d7ed0721b95de87ff09ecfa31746c12aece8a.nq.gz
    ├── 2e83b6cbc22cf24493b17d93cef2424bdbd79805.nq.gz
    ├── 2e97a85573b9f03b3fd5c0621d600c822f8a8c80.nq.gz
    ├── 2eb945d131c0c1df1bce0f5f74f7015df170e205.nq.gz
    ├── 309eb3680b028199bb6b736aca1ebdcdd4d43fea.nq.gz
    ├── 316955369995dfba60fe7df9c9a0cb9583fe7c5d.nq.gz
    ├── 321ba8da7f3dcfe644f8590b52d7ef6f61e750b4.nq.gz
    ├── 32864ac1df538cc1e74b9f153ce1bbd24af2ef8e.nq.gz
    ├── 32d46ee883b58d6a383eed06eb98f33aa6530ded.nq.gz
    ├── 3410ec4adda4976677fc23f3674e7effc7391071.nq.gz
    ├── 34600e672eb15a33ce43a5f4714a38437186e070.nq.gz
    ├── 34ad9fda901b3451fa79d2dc3e30875baac0ff37.nq.gz
    ├── 357563fdba4ae91167c2917bd9e8c6e828aa9826.nq.gz
    ├── 36b4db0904acf6708ea19701c744f5ab8630a707.nq.gz
    ├── 39350655b57c05bcfd8e1c0cee9acce2ded0682b.nq.gz
    ├── 3a3dd90e98534cb82d64b66cbf12521712ec20e7.nq.gz
    ├── 3a6b50eee935631d2b1e9c16f1fc1a0effbee5e2.nq.gz
    ├── 3a769f7ee2cd9332fb4032ace16021a76f71912b.nq.gz
    ├── 3b45f6e919ac32d51204c83ea889a5f18b35185d.nq.gz
    ├── 3be6fe8bb5b58ed80263e25c41b79b5a1bfdffad.nq.gz
    ├── 3c2ad8c4e84ec13bb236676eb6e4b71cc308f569.nq.gz
    ├── 3d0f0ea2f8ebf4926edddf198ac0018c88d5bdd5.nq.gz
    ├── 3d3d7ae1b34c71e19add02f582f0d90832f3cdfa.nq.gz
    ├── 3e4155c9bc229488f60085a29f7de38c60d17969.nq.gz
    ├── 3efa1a1bdb1cf6dde268899a0cafe97f0ca1d45f.nq.gz
    ├── 3f102bb59d5102432e80ce6d44323a047f8ab742.nq.gz
    ├── 3f7dfb0d940dbea2c46c115c039fb95e4b6de98e.nq.gz
    ├── 3f836c791abd456d6a3794fbb168a431805e6a64.nq.gz
    ├── 42bc478c2700a1eeb917a47389c8b7a240f6b31e.nq.gz
    ├── 43060020e4088051229050fa4a06eea432553eef.nq.gz
    ├── 444afc0c7412a5c23822c67edf54754b1a93b4d0.nq.gz
    ├── 45451861a2267c79df96b13583f3a622e55bb370.nq.gz
    ├── 45db76b8f3ba786f2f19f133520b6814086fb643.nq.gz
    ├── 460abe3d41a93825fe9f2cab3b12679cf37ab783.nq.gz
    ├── 4672f7e4d0f7544c65d6ea379c14789b49b0ea0f.nq.gz
    ├── 46f7b4e4bcefe8fd4c679bb6a458c4287c43f671.nq.gz
    ├── 482ec09c16d386407762940248007f08bba03599.nq.gz
    ├── 48b593dc8dd5474a25f9a7947b89825a0489a4f5.nq.gz
    ├── 48be8b06d3bbf1c00c4d0c3298d23a082a1d1f5d.nq.gz
    ├── 48d80d3d3d2e31b51523b5b7c397cb5173ba5dfd.nq.gz
    ├── 48e7b85feeec8567d7dd737c38ece0acd3c26314.nq.gz
    ├── 4925cd39ec211fdd6c2dda2098f670de01503098.nq.gz
    ├── 495b467f29986b3e98da9d71080feee930fedd96.nq.gz
    ├── 4a2df4ea044459b625f715f652e7fd3bfe3f6620.nq.gz
    ├── 4a5fd3d144a6289c31ffb396e45ccdcf194797b8.nq.gz
    ├── 4a99ff7009e732e42240bd6dc2a90031980beb9c.nq.gz
    ├── 4aa92c70c65d35a1a0e906ca99ed9837657959c2.nq.gz
    ├── 4b675be828fc0ffc5f0495523c78a289cac2e893.nq.gz
    ├── 4bbc625af997940db2e57ca4798cb43150d42a3a.nq.gz
    ├── 4c103156d0fd94f44a684912f7b1190b30912ae2.nq.gz
    ├── 4ce599c42781ea1c1eabe31f5c58f40948becc20.nq.gz
    ├── 4d244ec0763e8c4bedd5d3792a2eec17e622668b.nq.gz
    ├── 4d749e58c0dcc80537b783195f1fc4f3da751d8a.nq.gz
    ├── 4d86c7904ff9b1d09d7588657871ed7694d93823.nq.gz
    ├── 4e10f5d9cbe1bd9b0e6175d566194bb0dcbb4055.nq.gz
    ├── 4e174e219ed1ecd266d28b041bbd2d10c76055cb.nq.gz
    ├── 4ea8bd0fdd48bf6bff0c672bf6b14b0bab1e1477.nq.gz
    ├── 4ef6e260b40280452141c37dffc130f63ae8b5a6.nq.gz
    ├── 4fa55430c728c1cc511a3ea23735a4208fb99b20.nq.gz
    ├── 4fc6d19245e877b875650b886f272a29a16196eb.nq.gz
    ├── 4fca3824e5171607ed969b52a578dc864e56a48c.nq.gz
    ├── 4fe2de253bdfaef7ed33908079fc45505c8864c3.nq.gz
    ├── 50306a9ad4461f0c7181d8fb1e0683ed8b3533a6.nq.gz
    ├── 51f88c8097005114dca85d8812aed393a691c610.nq.gz
    ├── 527814d94944be021d8545544a875bbed8654b54.nq.gz
    ├── 52d56fdacdf997f80163bc9f7cb50d99da406c9e.nq.gz
    ├── 53474ecf9a087d1bf176281c2e1ac0827b7dd521.nq.gz
    ├── 537344ad3d8c501b6b53fd23a376a213973dab13.nq.gz
    ├── 542ef40ce0d11e72f2617027c476cd7dadf62cbc.nq.gz
    ├── 5489aed1c75a063fb12a66e8eb8442e1e72e3c55.nq.gz
    ├── 557572b764b493ea6c18da44ec0c7776373d89c2.nq.gz
    ├── 55a734abb3c1ea9ff3035f6906ad0af6f2826a40.nq.gz
    ├── 55c55bf038eb0dec2808eb522770130499a947da.nq.gz
    ├── 5626845836f95d0792ba0ea8cad4201f6d8bde8d.nq.gz
    ├── 57a749b78eba6934eef707dd04f3e5cdcc15cb31.nq.gz
    ├── 585edee0fc5bd6960898522041bbbd9fe414f5a4.nq.gz
    ├── 58d612c6d4801497dd10b5b49887a77ffd998ba7.nq.gz
    ├── 59cb927c7b949ff86c9985557a6bc71722e63d70.nq.gz
    ├── 5ada1b45b81543aa667c3db56021f051a9efbea1.nq.gz
    ├── 5add9aa940c7d3882571c0b033b095efbc3b6985.nq.gz
    ├── 5b92a08282a48ec2f721d7427a61d02fdf9cca76.nq.gz
    ├── 5d26148e21b2b847b429e64745720a62b8fd50ae.nq.gz
    ├── 5d2c3bca8bc0f6e3a2bdb536341f7fe10ea58373.nq.gz
    ├── 5dbe563f0973cee13cc77b9ce417e5ebc5f78896.nq.gz
    ├── 5e310cfbb0d7999ca487e4414f32312cbd635b5c.nq.gz
    ├── 5e9204b1e4848a9f56c9653e91cd9e8f556d5ab6.nq.gz
    ├── 5e950575ff8402955e6ac8d9bb0a98328138d25e.nq.gz
    ├── 5ec2fd502465a1be543651549e68e4314a87310f.nq.gz
    ├── 5eede36db46630d680a771e9177007c471fcad35.nq.gz
    ├── 6004554b8a84c99579e5ab485e71b43ca11a0e7c.nq.gz
    ├── 6009f3598b634aa807574ceb4f5f28fed173dd03.nq.gz
    ├── 617648a408e8a67b193aa5019cdd938bdf870f3d.nq.gz
    ├── 61b50848f8f6694070fa9f4aff6b76dc0a834baa.nq.gz
    ├── 61be540c2e015985690d68e0438c791bf47e02a0.nq.gz
    ├── 63a0388467972b4c5cb2075a94b79b423fa5e4a9.nq.gz
    ├── 63fe3849d80d20fdddf0c0beb0d7249710b2be2b.nq.gz
    ├── 6563d1702f28de8a99714938eaec4f7d0ce796ff.nq.gz
    ├── 659413c57f35d29bacb56bcfbf27654e5ad8ec08.nq.gz
    ├── 661702b0c2cf79af00506025be3c7a58c5e23a62.nq.gz
    ├── 6744fa76c6e506be337ccb09da72dc2b6c878d94.nq.gz
    ├── 684191f788cc56668a266360a2770847ebd48f26.nq.gz
    ├── 68f03f984eb02d7dea4654d144edddfb8b89ef08.nq.gz
    ├── 69468e78b2792306eabaf1f061fde9b324392dd9.nq.gz
    ├── 69efba9d3551712e9309f14515a501365a4a7a06.nq.gz
    ├── 6a288afe5d4a33f04719ccc00f3914ff6ad74cd1.nq.gz
    ├── 6b17b458524b4500a0ff895088886054e5b06d6c.nq.gz
    ├── 6b8f0f574b326eeb319c76a6b95d61c55234d4b9.nq.gz
    ├── 6bc5a78cc648dafa97ed6d7606951fed41867b9a.nq.gz
    ├── 6be4d53f9c6b02ded26dd5f73076b55bd2d569ac.nq.gz
    ├── 6c1ac2f79dfc91473bdcfc02c4faf36aa39e4af1.nq.gz
    ├── 6c4bcfa594510f6732556f9268f01cb42aa93d9b.nq.gz
    ├── 6c90cd13b9ef21c3122171e2faab6d11c0dca0b0.nq.gz
    ├── 6e2626928c36f09044a5c79021a96d078ce7fae3.nq.gz
    ├── 6e273970676d5b517f35be676c234ec3f7e038a0.nq.gz
    └── 6f19325a3689869c53b42d3915b526fae744ba5d.nq.gz

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

[canonical/snap-openstack](https://github.com/canonical/snap-openstack)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
