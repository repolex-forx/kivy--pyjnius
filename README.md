# Repolex Knowledge Graph of kivy/pyjnius

RDF knowledge graph data for [kivy/pyjnius](https://github.com/kivy/pyjnius), parsed by [repolex](https://repolex.ai).

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
rlex download kivy/pyjnius
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 24a328500175f7183ffebe700dc73da532d27f2c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 24a328500175f7183ffebe700dc73da532d27f2c
│           └── chunk-001.nq.gz
├── blob
│   ├── 0081357a2fc847868d4035328efad179012342b2.nq.gz
│   ├── 01032f1b9ceef30aa8b6a999653985f6e75291da.nq.gz
│   ├── 06fceef4647bd8280294d924e1d7b1b9dcd81ed3.nq.gz
│   ├── 0777b6ad9a76f51a328e5ca9419185193daf2b9d.nq.gz
│   ├── 08b3c735a1e791d02b1df4552058801dda389f8d.nq.gz
│   ├── 0c40ff9063defe5d3e696e1377b6ac7433f6dc10.nq.gz
│   ├── 178c4dcbb938ee2af71b61152e58ea27cbb70df2.nq.gz
│   ├── 1887418df1f8415d3b0ba1ca24b64ab5b787dfed.nq.gz
│   ├── 1898c57f07ad16191d5eaefa471a2f48a1f3e6c4.nq.gz
│   ├── 19d1f95560587410f1d907185ea12361bd48aac4.nq.gz
│   ├── 1a1da61385f6ee92cc0ed973b7daab67a3d82f3e.nq.gz
│   ├── 1e69f50ac3c33dd8ed6162031ec1ab6849cab3a3.nq.gz
│   ├── 218b051e5628ef76b39da582ca0637a4caa7f338.nq.gz
│   ├── 235b3ea151b62280ae2aadff6a295871b67228d0.nq.gz
│   ├── 240893d271a5a7de944ac5de22df77119e4403c9.nq.gz
│   ├── 244022ac0cb13a6931f6675ea1695d527892754a.nq.gz
│   ├── 262b71622dbe54dee14df196c9f2c366f875f309.nq.gz
│   ├── 285b54b72dc052a76836e1aeb4057f12d2934a4a.nq.gz
│   ├── 29d18faa24b01a0961febdbc549acede3d161a63.nq.gz
│   ├── 2a54ad956a2afde18e4e55bb82d95efa803173f9.nq.gz
│   ├── 2a8ce64eb39f968e5ee1689bb77ed0952da17bb0.nq.gz
│   ├── 2b6edd5429bcfee69b1991b0b40dd64b7d36f94e.nq.gz
│   ├── 2fffc90a6a38cd5a7a6a86adbf8b725bdcb0d637.nq.gz
│   ├── 3047c9545188990c77c5fa3704c68252a885faeb.nq.gz
│   ├── 3051b09377fd9c01c1f83c825898d6e2f8bbc804.nq.gz
│   ├── 316b634082b1cadd9ec5313f5ed26cedb6577609.nq.gz
│   ├── 33750f478f59dbd16fb80ccec87aa371ab9771b2.nq.gz
│   ├── 35c58e931d60486196ba2d08103fff58e76b663d.nq.gz
│   ├── 3634356ddf76fa607926fc3235cc4418bcff9a39.nq.gz
│   ├── 38a2635338cd366b93deb0707b70d74d96bf85d8.nq.gz
│   ├── 3a76dd529fa310b151631d9494610ea62d92ffc9.nq.gz
│   ├── 3ab53deea9aa9ec9bc458a5942fdc01fec64534b.nq.gz
│   ├── 3b56ebdc9d70fcee639fa4b19789f75e4903fb6a.nq.gz
│   ├── 3ef3166ad31b03b12de6324ac61aec97a3f270e1.nq.gz
│   ├── 41d6f427b0030bafe391e7f7c25fa5c9fd13f6d7.nq.gz
│   ├── 421e771b47d7c790d0f4da4372be4213dbd1be85.nq.gz
│   ├── 4278cf1277ecc3627cdd0ec14fc2a3db16e70bab.nq.gz
│   ├── 42d4f4548f91cf01dd258e94bbc864fd0101a40d.nq.gz
│   ├── 45e4f4af4185b08bb98b3388a5709ab45d0bab2f.nq.gz
│   ├── 45e7408034d6a8dd3ae472fa9d7672700bf4b652.nq.gz
│   ├── 493bfbfc698e58ab749f2584749e813e1e7976c5.nq.gz
│   ├── 49bbaae2c98929aaefaffbd705c6f083171914b6.nq.gz
│   ├── 4b01c84c8abd47ff9b462f9da51444f9395d1486.nq.gz
│   ├── 4bacd767765372ffc80640850147875906bd13d1.nq.gz
│   ├── 4bf379d15e201d194ec429eddf94a81557002293.nq.gz
│   ├── 4cf897740c42af7fedd2e3a13bb7a0aeb6fc6100.nq.gz
│   ├── 4dbb335393d1553b2e794349fceca7093f404f20.nq.gz
│   ├── 4e3506010a8a57901c413ef0dda95c8e0299719a.nq.gz
│   ├── 51ef9629ba4168d4b06c1548c8939e13f000dc24.nq.gz
│   ├── 51fa697ddbf4cdb390a8a574b85a98d416f29f0a.nq.gz
│   ├── 53a3e84ca179c8d91f77e5127f1859b394057eb3.nq.gz
│   ├── 575b19a8cc7729073ede2ee083c196be83f0b957.nq.gz
│   ├── 58ac9c6e1c8222bb48d449bd7b56530c6836d4e7.nq.gz
│   ├── 5a94d4faec267e5f018d17c0b3f602a3ef309e69.nq.gz
│   ├── 5c0c1dd51926074d252d1c9d8ebf63fe20ada728.nq.gz
│   ├── 5e3b6bce68af981fda2d872e2056dff7b8976f4d.nq.gz
│   ├── 61b9a5cc2865a2073ca7252bf8c04c127be42ced.nq.gz
│   ├── 6216154d8e81dc40bf048ede5b1f6d53318f0107.nq.gz
│   ├── 637eaef023b33d53c1a22fafabeb6844fc7a7724.nq.gz
│   ├── 639c01edd812d129ec01c32f2915a46503432e96.nq.gz
│   ├── 655d53b5de7c87fce58f5344bbae7075a6b67669.nq.gz
│   ├── 66f5046da0486c877e59cfc829aa6bcb7cf83d0e.nq.gz
│   ├── 670db15b2d62b85b9748b5b7549a259703e66fe7.nq.gz
│   ├── 67c2d0a8a7bcac57f7a53e617c5d6a440de268f3.nq.gz
│   ├── 6809f0e67620fe59d21301afd1ba68a33a1c1592.nq.gz
│   ├── 6a01ea408be83a2f64fb7e4c054daf6dc2f66664.nq.gz
│   ├── 6b0954617116fee46b9a8c7e9172a7dabd25ee7b.nq.gz
│   ├── 6b576deb209a45175b171d90214ee4350623757d.nq.gz
│   ├── 6fb8e32e765460a4731dc51d2297171aaad176ed.nq.gz
│   ├── 713e8f71b0de43120ff5420e242195e50e0868a9.nq.gz
│   ├── 72f06e585bc680da3393a7f4642c39917a33f217.nq.gz
│   ├── 75d38c28b58f5fafbff4ca3e1ef0fd4c22887864.nq.gz
│   ├── 7d1c49db74c1761c98209d49194ea1dc398c9008.nq.gz
│   ├── 7dea03131ee54e17d8e76a56af5808b644d604d1.nq.gz
│   ├── 7ee4fd0f42d1df612390c0333256e79f42d4a2d3.nq.gz
│   ├── 83bf36261a2e21a814e3c13e7a2b91b6ebae7d98.nq.gz
│   ├── 8514df6a66b7d8d349360f1f7cb7176fdc10a1ad.nq.gz
│   ├── 87a6beddaef49a0eca366a4dfe89b457e8392bd1.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8d6fc626cfa6bb39190d44638e48f7f9d0a0d049.nq.gz
│   ├── 8e56ea862556eca0bcc849ace07b9e365ea6ae39.nq.gz
│   ├── 8e84b66d16d1d49fb1848eeeae6e161f26c15fc0.nq.gz
│   ├── 92542aa7361306aabbe1f93c22670e7bd3fedca6.nq.gz
│   ├── 98801127dc3d4304b0f40d41ada1011f74b586bd.nq.gz
│   ├── 9973ce7e87a0cf7c3a0ec72ba06dfd9b0120f2a1.nq.gz
│   ├── 9990564d720b4874806f949d68cda079762848e9.nq.gz
│   ├── 9afd72151997849ca1a76f831d98b40708ec6498.nq.gz
│   ├── 9deeec59896e3bd8e2846c0b8273b0d9b69939c1.nq.gz
│   ├── 9e53a7fd37ed326d5c2115906551da7a68578ddd.nq.gz
│   ├── a1941ac6d73268b91a1d93c3ebb67501e7b860cf.nq.gz
│   ├── a61045dfeca009df4ca9c8021bf1391d64db3c72.nq.gz
│   ├── a680c42cf724bce0005a3973ee446b7abe8854d1.nq.gz
│   ├── ab6bb3f34cb203a7f4c83b2285c859e9ffb99587.nq.gz
│   ├── ab7498dc48318607689a60d13369c5ce5529e796.nq.gz
│   ├── aedca02e1fb795e763a6a3803d6c49bcd880b4a8.nq.gz
│   ├── affe32785559cf3b1785fd5609afa757759b02bd.nq.gz
│   ├── b09df7492df464e52e43c8bb28d0c005b87d37ea.nq.gz
│   ├── b5f396b1acbc43076b48a8b65f82f930be3373cb.nq.gz
│   ├── b6947fe1ec7a14373382264dc2916435bac0520c.nq.gz
│   ├── b6bb24e8b556e5dd506513603aa39748d2b2656f.nq.gz
│   ├── b8058148151b54badeb7901acb66f85d840f0df9.nq.gz
│   ├── bba7af30b0ced281a4e142fb1e2af31f93547c0d.nq.gz
│   ├── bd8f750a33edfef1454e87b58b64ea7d47d90ca2.nq.gz
│   ├── be8031367b93773f1f103c0f26ea7bc1fccc1038.nq.gz
│   ├── bf8a4ed1fd55a1f1dc2558fd47954201f9de6fc4.nq.gz
│   ├── bf9dbb21d7b41f872b6e013cb7eaea177441e42e.nq.gz
│   ├── c569fc1305b704b92df6c8177b5cb6364bb8b637.nq.gz
│   ├── c7693abc93d156a8b27cdf1154c60f549b67a0b5.nq.gz
│   ├── ccf5042170143cf968dd053f52f3a5ea15a5f893.nq.gz
│   ├── d29527d3d74c1a0eb75153aaa605a75a7a3c2de2.nq.gz
│   ├── d2b3933f31f99379b1f7db8714e99bf89f112de5.nq.gz
│   ├── d2e0958123c1a52ab7e04766c70dd99967c9b977.nq.gz
│   ├── d2f68ad6946e65c4b52d57f901808bbf0a762cfc.nq.gz
│   ├── d4206795cd2169f28b77dd6cbb5dd494ad4f160b.nq.gz
│   ├── dc0fa460c9ecfc803e88424b66f5d56c4730e0b4.nq.gz
│   ├── ddf1e072e2f3bb23db8ec1885099e7607076554a.nq.gz
│   ├── decdba28a16fb6a6dc9a5381a0199585f5751d61.nq.gz
│   ├── e1177944c62eb2b21b70a6663bfa094e1b2144c3.nq.gz
│   ├── e59b25528ae3958e431b81d24055101e9c91c27c.nq.gz
│   ├── e6e659a8c0a6f538594c3f06309c20ca2eeac8bb.nq.gz
│   ├── e7ec05b058165bf14b709867b9a545a19a35696a.nq.gz
│   ├── e8361768cd1ed18745f3c6a655c2a853f88bf380.nq.gz
│   ├── ec5afe97e7b188c5744ab77f602875b8babd9dc5.nq.gz
│   ├── edca65a20c46b56a47dac2434cd6e06881e91451.nq.gz
│   ├── f56728f5a64a7b798bbe1b89e7d0e536ac8b4a24.nq.gz
│   ├── f688d9336138491e5d2c3e902591fc4351cc120a.nq.gz
│   └── fb01c87f6f23c6209c25c22f9b79dfc20c475311.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 24a328500175f7183ffebe700dc73da532d27f2c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 135 files
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

[kivy/pyjnius](https://github.com/kivy/pyjnius)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
