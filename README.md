# Repolex Knowledge Graph of Cognition-Labs/Synapse

RDF knowledge graph data for [Cognition-Labs/Synapse](https://github.com/Cognition-Labs/Synapse), parsed by [repolex](https://repolex.ai).

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
rlex download Cognition-Labs/Synapse
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4c06412c583855bf839b54c8b387f1dae21129c2
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 4c06412c583855bf839b54c8b387f1dae21129c2.nq.gz
│   └── repolex
│       └── 4c06412c583855bf839b54c8b387f1dae21129c2
│           └── chunk-001.nq.gz
├── blob
│   ├── 01a7e243b284baf0202663a998289b0e1be3bae3.nq.gz
│   ├── 02e6209b3a3746f45d9f2a3e31e43e8fc37e9164.nq.gz
│   ├── 04f0568b153b9c772e0340466e21eb2c7a35c4ff.nq.gz
│   ├── 064a05784f840b4db2178d6f195d7db116f8e5a8.nq.gz
│   ├── 080d6c77ac21bb2ef88a6992b2b73ad93daaca92.nq.gz
│   ├── 082f98f233d5a947ce0b0a73a280e635d2c2e1c5.nq.gz
│   ├── 0bea32793a432be044a0391d8e3eb143a53ada5c.nq.gz
│   ├── 0d307bd6abddbb0a678ee7c64fcfa27bfe8b65ae.nq.gz
│   ├── 0e74b115e276327dc88eb7059198cb0f8da8ddcb.nq.gz
│   ├── 0ef00445af28c84493c172d7b6270786c8fc372a.nq.gz
│   ├── 0f8390eb5effebad6bce466c7d9f880c1bfd3855.nq.gz
│   ├── 116921db8108eb2adcffec29d6d1e3bd16d1043e.nq.gz
│   ├── 14e578d247d87b16e2f2a91795e50135319c5090.nq.gz
│   ├── 1c7bc3072898b0aa3c8038cf4d087762cd5575c7.nq.gz
│   ├── 1e576ca56a9045a6619b4c7dea55ade7f5481472.nq.gz
│   ├── 1f03afeece5ac28064fa3c73a29215037465f789.nq.gz
│   ├── 1f9121c10eb43e6447dac44f6ccd061ba4929f3e.nq.gz
│   ├── 1fd14540df8c7de8f648a4b56ca82edb8d99d381.nq.gz
│   ├── 20570f2f33b858c6a37cb7a92480b8622ea0c4e6.nq.gz
│   ├── 2466dab8664d49abe29e3b223c008148b88f69e5.nq.gz
│   ├── 251085e97f8fa9ed729b0629161da5b23c71b2cf.nq.gz
│   ├── 260a46cb0b4d59377e02f40f299fb8874f409f36.nq.gz
│   ├── 267915b5d59e6358fe4b7267f14f4e5378934829.nq.gz
│   ├── 26c39ba7c4aeb5b40852392f0e83c70991ad4017.nq.gz
│   ├── 2749f70afa62702f2e1122fd74b0c40a7fb52c81.nq.gz
│   ├── 27a3ec5280ae4972fcdf3a82a29b9c16f54a2429.nq.gz
│   ├── 28a62fef0e5b1b6bd8db9b3832b88be03d716b2d.nq.gz
│   ├── 2a0a96835ae18b19d572a5315073b326f11a7674.nq.gz
│   ├── 2c7b3aeab80563825933596a920a734ab90b3e32.nq.gz
│   ├── 313cd499d7958b0564a376120511e496aeeae330.nq.gz
│   ├── 327b81f00e7bb03dc908d7257ccd37e473a2a656.nq.gz
│   ├── 327fb321b5758ce62ee719725b913a9960f01826.nq.gz
│   ├── 34774b5a0489fc7964930189cfc8b0008b3754e3.nq.gz
│   ├── 351a9dab9840c43ec74e3334371cdd3ec3480f45.nq.gz
│   ├── 35a631b7c0044906a859f11464d107697b66d1cb.nq.gz
│   ├── 35dc618d6f89dcabbd514deb34ced0ea7f99f60c.nq.gz
│   ├── 375a2e122845b568ad5692de9005f42bc41d5be7.nq.gz
│   ├── 3ade730a71628552f03098564bfa9a6ca8fff599.nq.gz
│   ├── 3cebf30d449a8b13d214ba3ec02dae2670e6c3a5.nq.gz
│   ├── 3d8959a042108172b7aa3f52e748460c23d1ebd1.nq.gz
│   ├── 3daff96677aee329ad1f314f6e824920b51483e7.nq.gz
│   ├── 3ff48d7b91ae443f317367c9f4ef75e7d41615f9.nq.gz
│   ├── 41599f3e2dbda70b495ce06bea0de9bea910c0b0.nq.gz
│   ├── 44911e206eb0f8258cebe5c5d17810f583d3f0a3.nq.gz
│   ├── 44faa5906cc3f758eb4f916c62e4f6e3aae582ac.nq.gz
│   ├── 4546becd127c7f1dc430d5f89b602801ee4463b4.nq.gz
│   ├── 472748219f79d1f9daabbe0f6b8add3313d8151e.nq.gz
│   ├── 49f410d504b812beab0b11e0ba06c704ce22456f.nq.gz
│   ├── 4a7ea3036a20398caf9a9daa984acb4a019f3090.nq.gz
│   ├── 4aff6d9655ae3f4ce39f94a09ed10b4a51114770.nq.gz
│   ├── 4d3dd7255affc3c8dc8a927934e04858ce30a9bc.nq.gz
│   ├── 4f5196963e1ff384298ef93d0bbf64aaecfe1b08.nq.gz
│   ├── 4ffa1c0b0ac1ac77d63e82b440909d83344b6d2d.nq.gz
│   ├── 5008ddfcf53c02e82d7eee2e57c38e5672ef89f6.nq.gz
│   ├── 5253d3ad9e6be6690549cb255f5952337b02401d.nq.gz
│   ├── 53bc8ae85811c085c3b8d4d296cf64fcf403d6c0.nq.gz
│   ├── 56172416c79d29acaca9177b942f6b7fb2c94db9.nq.gz
│   ├── 56ab315eea4a8c3681fa14d7be66731c2c18b08a.nq.gz
│   ├── 574c425789e2f9e220a15dc8a72320e3d96623fd.nq.gz
│   ├── 583fe6e71cca8423ee47df49408b1bdc8ee4fdd3.nq.gz
│   ├── 5940b65a3d42d62f38317f14270b28fd8dd568a5.nq.gz
│   ├── 59ce058bc19cccc67e73efdcb82b78a066b35a90.nq.gz
│   ├── 5b9886185316f11b0f84d6051f2761cf8f42cbd4.nq.gz
│   ├── 5bd3bc500960c04dfe1103f34d3dc7ed68e0067b.nq.gz
│   ├── 602962e2d0de9620fe56699a3208ec11f2067009.nq.gz
│   ├── 602eb23ee2eb4cdf1980f10c53fdba15ed65af34.nq.gz
│   ├── 614b90f0475a1556901760f6a873b5cb4c786807.nq.gz
│   ├── 63423dfecb8a433cae122101224a277286584a8f.nq.gz
│   ├── 668d69bf03df9a13aa70078bfe37bd9f5b468c62.nq.gz
│   ├── 6859deae8d995d9332f10caa23b31f8daf5bd6c6.nq.gz
│   ├── 69f6152091ca2bd493ac80870a75488cdc7c94ae.nq.gz
│   ├── 6b85efb62cca546063b389afc4540be5222634a5.nq.gz
│   ├── 6cc31e66665ed7ab5d20e5bfc474e7c5871139c6.nq.gz
│   ├── 6de06285a650fee96fefe2e50f20ebbdd7f51f31.nq.gz
│   ├── 6de0ec0e03268c0551cbdb8e9c5e2f27f253ec7d.nq.gz
│   ├── 6f974eef0b7c87a984f842089bf59a0dcbe602d2.nq.gz
│   ├── 74b5e053450a48a6bdb4d71aad648e7af821975c.nq.gz
│   ├── 74d87a0cf105db95f543775d6be1cda0b3038d3e.nq.gz
│   ├── 755a6e51d53e9252f90c19cdb4a373bebb80af98.nq.gz
│   ├── 7775eda3705071e5eaee06b4c1c3adfbc9935ffb.nq.gz
│   ├── 7cad53588c8775e66159744f7c3b00a857f89c50.nq.gz
│   ├── 8255ab58cea944436e3e6853aa5da9a8a88a1082.nq.gz
│   ├── 82a8ec778a4e1df3ff788615c581c6f37a7da588.nq.gz
│   ├── 84b8436afefab2fdec11824a10ee1a5a7b457d24.nq.gz
│   ├── 88e2ab1c9fbbdfd8c65ea6856df8051bd0e44695.nq.gz
│   ├── 89d242ba72d5da5d31f1b1c87a5df98827c7d67a.nq.gz
│   ├── 8aab2ff5c3f4579601b5842324de40e678b77c17.nq.gz
│   ├── 8f2609b7b3e0e3897ab3bcaad13caf6876e48699.nq.gz
│   ├── 9035e7c80b671a2ce8c7ce4eb7543261cf944681.nq.gz
│   ├── 9133a79221f1bbd4285d80d032128b679c4e39d0.nq.gz
│   ├── 91f649ac3634c94dafbc1ea7363cd21d8de214ea.nq.gz
│   ├── 91f8dca84ed5af3ecc1c288009373acb5d3e6b6b.nq.gz
│   ├── 92a214148a3c578a8bde772e628145b11d152d8c.nq.gz
│   ├── 9421aced4320f5555fc0f943ec6dff21df14b43d.nq.gz
│   ├── 97a5661aeb0b6f20fde68d9e6dd1e899d8fda63f.nq.gz
│   ├── 985f75eaca665f7d637eb8b4676fe33e3e23106d.nq.gz
│   ├── 98948ea682c47f298f588b92fd54bfbe30a653e5.nq.gz
│   ├── 9b562ff51e744624534823b1c76f8b44e4812d71.nq.gz
│   ├── 9ca893251ca184f9c794a4e21bdfcaa0e9e3af32.nq.gz
│   ├── 9dfc1c058cebbef8b891c5062be6f31033d7d186.nq.gz
│   ├── 9e47a9f74dc2df0ea5e6e98e9d0b014445d51e5a.nq.gz
│   ├── a0152d868da7b1fc5e85df9efe058e6b0f687935.nq.gz
│   ├── a267f477b56f5ea2ae6650bce0f93eb2f62f97dc.nq.gz
│   ├── a5562edd6201107397b9a1758001aa0b7135b140.nq.gz
│   ├── a58608397d7a70f53f4261bd775ffe782383f617.nq.gz
│   ├── a6d9ca6c32c269e35777f3ec3dcd8c6daebecc22.nq.gz
│   ├── a71f9d0d549825ef5e85ca6f93d4c830b30548f0.nq.gz
│   ├── a8a1a5f7c14c1c0ce636ab9097bc339cb4cbd91e.nq.gz
│   ├── a99880cf7209d097cbdcdceeb98510bacefebbb1.nq.gz
│   ├── ad39e9241b1c15d3f6dcfad03e75e0b5e25c1fc5.nq.gz
│   ├── ae26f70c60599ca4482c523e5d07a48e0ef7cd87.nq.gz
│   ├── b064abf9f5540d4eaa1265d5c8b3937e3be16c3c.nq.gz
│   ├── b258156b391d27b7fe946208ddb5b03572e4ef72.nq.gz
│   ├── b5f3a69b4045175390b0e9c094129ad0f2191f00.nq.gz
│   ├── bb4e8cd2ef1f0848ba38482187a61972702961ce.nq.gz
│   ├── c0c6178ad42a79763d8c49d20b16fd602398ea87.nq.gz
│   ├── c1abcfd2775f10f9961f96c1a53f2ebe668a88d2.nq.gz
│   ├── c2213ce890a3d807acf6eaebc03b783ea246ecfa.nq.gz
│   ├── c2885de682427844aaf0382a124da8de9f14eeb4.nq.gz
│   ├── c31cbc5581518f2e44fea0482c51f54478448ed6.nq.gz
│   ├── c5b32a6f7b4f02f888432fdc11f554c42ae919fe.nq.gz
│   ├── c661bc1d9fccadeaa22c0e09a6ca9bacb9b81547.nq.gz
│   ├── c6f9b035e9e2967843374f5fc7e021943127668d.nq.gz
│   ├── c8c57558b2a2cd6bb71cbfe95e8bbd8a5b1bd737.nq.gz
│   ├── cb7fbe29d46301c3f08ea14561d4269e33059be9.nq.gz
│   ├── cbbaebd1863387326822fc266a255253169f10c2.nq.gz
│   ├── ccb0ba8aba0d8376a7cbe4b0025fcd6389735470.nq.gz
│   ├── cd51cdc500009551dc92454c4ef4bcca04919309.nq.gz
│   ├── d14519cd040cf5de68db2c75e80d74551f46ce84.nq.gz
│   ├── d6679e63e40387c0972abd1606e84f00e4bd9fe8.nq.gz
│   ├── d85ca53247545a65694f30bc77b4948ee0018c14.nq.gz
│   ├── dad3e20e6ab5ea28feee9d2d3bb4b7a97a288ef7.nq.gz
│   ├── de2f9ac9c6e98363507de940b8337167db97ce53.nq.gz
│   ├── de6ddcc19d8a1804c83908c81e1d24105257160f.nq.gz
│   ├── def5076bece8afbe9d30b11f080b66af5131f08b.nq.gz
│   ├── df0d8b9c93604b0a0dad6bcb03eab0ed446cf2aa.nq.gz
│   ├── df924c0e23459ac7bcf383e4c0fb10477b29ca7b.nq.gz
│   ├── e23f9523a3ea3c809eaa0b1e45855c2b55ac3456.nq.gz
│   ├── e5ba573435fe3822e187def9ca57187aa474d7f3.nq.gz
│   ├── e95eb8d573fdd73ad7d924eb4cfb24745288e875.nq.gz
│   ├── e9e57dc4d41b9b46e05112e9f45b7ea6ac0ba15e.nq.gz
│   ├── e9f2aa293802f2f5ebf8a135a056117cfbc0fc08.nq.gz
│   ├── ec2585e8c0bb8188184ed1e0703c4c8f2a8419b0.nq.gz
│   ├── edced71a228aea86e9e6aed732c06d95a99b24da.nq.gz
│   ├── f3041366b5085cf2d4af559e3c7c1734e13629bc.nq.gz
│   ├── f43a8c9db322c4a8565316c134e138dd5b50302e.nq.gz
│   ├── f5a2326808a40f156aa4dd16daf59a21f46b6084.nq.gz
│   ├── f7ce67079063041b7c2401b969303b9f9864071b.nq.gz
│   ├── f7eedcfdd70611a0477a48f7b396c2821fedab72.nq.gz
│   ├── fb57ccd13afbd082ad82051c2ffebef4840661ec.nq.gz
│   ├── fd2d106c8b20216c1d2dc52b82380e80db4a0d18.nq.gz
│   ├── fdbf1dfedb1b8beae7750d463b4e25ad83b97d21.nq.gz
│   ├── fde5f0198cc8e1de379c5000dd70fa6670a10bdf.nq.gz
│   ├── fe551d0754ea11bcd1573106cdc8cbb31c9ff175.nq.gz
│   └── fee8b0e7b9a5a6ffd925e21fc44e68eaba315b93.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 4c06412c583855bf839b54c8b387f1dae21129c2.nq.gz
├── filetree
│   └── 4c06412c583855bf839b54c8b387f1dae21129c2.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 163 files
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

[Cognition-Labs/Synapse](https://github.com/Cognition-Labs/Synapse)

---
*Parsed on 2026-09-30 by [repolex](https://repolex.ai)*
