# Repolex Knowledge Graph of webpack/webpack

RDF knowledge graph data for [webpack/webpack](https://github.com/webpack/webpack), parsed by [repolex](https://repolex.ai).

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
rlex download webpack/webpack
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 0065223c4ddac3bf872bc8d660ef1e9a63afa080
│   │   │   └── chunk-001.nq.gz
│   │   ├── 0105bc1f005d78e3819a567ffb91432683569070
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 04a7d052b5c04628257ec23244f234622c7f394c
│   │   │   └── chunk-001.nq.gz
│   │   ├── 04e00736b03eee0fabfd32eee5323ddc3701083f
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 0756c7eb697a7759afe081a1fcf8f5481ea06bc3
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 07b1ac0213bcf9591a8dd5633535a43ecd248192
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 08770761c8c7aa1e6e18b77d3deee8cc9871bd87
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 08ecfbbc035b12f2ed5c0b83b53011dfe57ae7c9
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 1018ca80b31ea72436510398cca5be335b6ac81c
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 11c1be3d0838e8de31900aacabcd449e9da77eaf
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 1486f9aacca11d79dbb7ddbceed29b7e6df7a7ab
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 14c813a0b3709e142b3ed03355c6c15fc11b91a1
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 1bd06e333346656ef6542e36478f02055cab7369
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 1d9cc240a29d17f3986d9e9f96f2589d823e832c
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 1def19ea8ab9921d1adaed30ba8f928badb133b5
│   │   │   └── chunk-001.nq.gz
│   │   ├── 1e18b1d1c74e26a84e9adee519c045e2d8ed40a4
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 1f99ad6367f2b8a6ef17cce0e058f7a67fb7db18
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 21be52b681c477f8ebc41c1b0e7a7a8ac4fa7008
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 21fcdbb8f2bb3820d3309df8e399c6deced12b42
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 2470d8e74c8b647203063826cae1ea5e691726a9
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 24e3c2d2c9f8c6d60810302b2ea70ed86e2863dc
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 263f29189060529198b7ab4dbddfd2dca46bd96e
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 277460b33bcc49c51acbbcd688672aa4ec685732
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 27c13b44c861908793f160f9f7413b32543c0522
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 2a5ed4a2dcbe06e852f84a8e7f63145af87cb139
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2b2b705cc5c53594adf5adebca55f7273a1615c9
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 2dc8755dc40e24e3ba5760e96738b74990116711
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 323d65e2b1f6d275bf1b4a93ef753f027de78193
│   │   │   └── chunk-001.nq.gz
│   │   ├── 34e2561addb0f65a7a6fb0ce7ae1aea4cd1d599f
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 36051a5ca77b4fa33fac651e1af650c7b910a873
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 3612d36e44bda5644dc3b353e2cade7fe442ba59
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 3849f45961c60d4bea91b4ef43bb7da7992a0c3a
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3aed1fe0249f8730a35fab62e3cdc3b399b0b6e9
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3d5503a5b535b89bbdde78535c1839cefd88e4fa
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4156b20644d309c0e8acaa1e22ca3a4fe546c0b6
│   │   │   └── chunk-001.nq.gz
│   │   ├── 44da94f433c4adeb7ac56abc69df2b0f8a213486
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 4a0aa5d204dd0cfbaecd99f87be97deac5a883ff
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 4a2662381ed8e6a9d849b494511459f5858d4e82
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 4abe329dcdaea60371c03c0d85c3a3994d875138
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 4d4caf13add84f996790e5bbdf79b66a548f8273
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 505a5e744fbcf4471ddb534bf1d4aebea9643c1b
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 58dfda2796edc57c9d18526053d6bcde6f06b8b7
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5a26b7c4a923c42022ca97fe9cbf46907a20d6d8
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 5b87bedaf418b3cfa713d520bb70191098943917
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 5c016a8ec1bbfd73a7fc20d4b474938e61ee3a57
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 5d297327bc1f208de16c29f5c9b31d2b8a06bce4
│   │   │   └── chunk-001.nq.gz
│   │   ├── 60daca54105f89eee45e118fd0bbc820730724ee
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 63c14ccbfc6698cb974f8469e0a829ae1d8f44ec
│   │   │   └── chunk-001.nq.gz
│   │   ├── 644f1d12716ba8f3c96d2efa279262560dd8c7fb
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 647aa17cc7fe16d382b3d48efc47258c4e96d699
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6661bd94fd724bb4610d348a1ffe48030dc56726
│   │   │   └── chunk-001.nq.gz
│   │   ├── 69d4e174b96f197ef5d9d8396edaa25178f22725
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6be4065ade1e252c1d8dcba4af0f43e32af1bdc1
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 6c9f912af2dfbb3e0e1a2a3ecdc3881c96363432
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 70e3d9d5dbd3548431b8878dead4647beff5c14f
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 714a0e3496f2189f76b5d2c98eacdeedae9e7c06
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 71d9a21c32974b5166f9ce2f5549849d0c7ad310
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 7774d7ec632e66b8c6a8c0f320b3469e86ed5e26
│   │   │   └── chunk-001.nq.gz
│   │   ├── 789e58514b5747f6474bc247e4e104ce22892a2c
│   │   │   └── chunk-001.nq.gz
│   │   ├── 8241da7f1e75c5581ba535d127fa66aeb9eb2ac8
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 82edd9150f8e54bab1497c9c29edc01bc39a88b4
│   │   │   └── chunk-001.nq.gz
│   │   ├── 83c534ca3a6385ee7037220c7ba510ba5a8d944c
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 87660921808566ef3b8796f8df61bd79fc026108
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 8ac9616280aebfb61ae7484f06ad1979d73e6a56
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 8e0e0eb47d47fe33e4c9ef9bc455d9584f7ea92c
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 8e50ef2035b9cb727aeaa97d7561545d1c102b91
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 8f87b50dc7ac24eb5c91fd0d55a22e34e252863c
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 97b1718720c33f1b17302a74c5284b01e02ec001
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 9ac1728ee359efbbd1eb317f4a12c0f8136a690e
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 9d21401151b32abcefad0ffdb3238da91e2089ef
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 9ed05afbeaf87442d86863a20a6c30b0ab437fb5
│   │   │   └── chunk-001.nq.gz
│   │   ├── a1948fb2247adb5121ded5c3c4a04ed384b96c03
│   │   │   └── chunk-001.nq.gz
│   │   ├── a82e0cd00e26d8452295f0d680417e4656a6d7cc
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── a8fd8b7598e8a599871765e0167cacf8318944a9
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── a9cbd85abf476fe8aba0cb1037f7e630f5f8649f
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── ad1e3b46f46b9acd5bb9c377afcdc101338d5c96
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── ad77deb6ed0b9540f9d2cf1a1c08f9d058a95da6
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── aff0c3ed2b31ed16ce8738e02f4b8f97966833f4
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── c2079f7e7666a913d6fdad4b9102ffb0d3801cc8
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── c66e4ce32027fd31935ce9197c219e46308ebd3f
│   │   │   └── chunk-001.nq.gz
│   │   ├── c67a73abbc3d3b333b31480bd7ac7a50e8b49e3e
│   │   │   └── chunk-001.nq.gz
│   │   ├── c7ebdbda637ea73a03a23446f5db0f600e304772
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── c80b069dca8eedebfa8ede9ce740891362fdb8bf
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── ccb3b860520c9472eff3d411a48105f882cf482a
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── d044c857305fb48693bfa961bec3485d82ddef41
│   │   │   └── chunk-001.nq.gz
│   │   ├── d3a0f8de03f26a83b4d5db3cfe177617a3801df3
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── d3cd4cb6e38338237fe722d4b7feae2244c425c5
│   │   │   └── chunk-001.nq.gz
│   │   ├── d49b49ddebc6c06703e19ff6391915d2b09b0f2b
│   │   │   └── chunk-001.nq.gz
│   │   ├── d4ced7322229c7d72a7a0d2ca955bdde0c910a0b
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── d95a0418b64bd366f0c51f2635ef0c24158b8bce
│   │   │   └── chunk-001.nq.gz
│   │   ├── daa0f1ed1cebc28c8cc9034f95f3b56e9253ec5e
│   │   │   └── chunk-001.nq.gz
│   │   ├── dbf7bf39ab96e1462603435c150d601bb69ebe4e
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── dfdc8b133d3d49371251e29efeefb9d31b982c9e
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── e0219482aafb9087a50ca0be45110727a33801fb
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── e20fd634fd24fab2c821a6e6114ace706ca052d0
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── e51f8347026588c90f9bd91681597e97f24f40c9
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── e9de77aae42bd8f7d799a21dd16c98206cd170f6
│   │   │   └── chunk-001.nq.gz
│   │   ├── eabf85d8580dfcb876b56957ba5488222a4f7873
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── ecdcc1a1d02a3097acb9ebc0896365ae1f4d25e2
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── f011c70aacbd4dd3c4e518b9b9d8ea945dce0a9a
│   │   │   └── chunk-001.nq.gz
│   │   ├── f0f0dd548871566c77c69cdf3d00eaf0faf9a5cd
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── f1bdec5cc70236083e45b665831d5d79d6485db7
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── f593d98453e7920bf65f24bf051cd67b5704b59d
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── f5a263750611f33adffb7644064b40b0432d6c65
│   │   │   └── chunk-001.nq.gz
│   │   ├── f5bcac4a061897822bf10a8191231b5a71c59273
│   │   │   └── chunk-001.nq.gz
│   │   └── f8eee102c20a3d79eddfed0194113c4d5759d9e4
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   ├── lsp
│   │   └── d49b49ddebc6c06703e19ff6391915d2b09b0f2b.nq.gz
│   └── repolex
│       └── d49b49ddebc6c06703e19ff6391915d2b09b0f2b
│           └── chunk-001.nq.gz
└── blob
    ├── 00002648b85c40bdee3fadca343c142f4af1e0e8.nq.gz
    ├── 0005a20e660afa452721829b994a23091ac4fc60.nq.gz
    ├── 0007abba68e455ec54f3182a42e5c759315c27cc.nq.gz
    ├── 000a93eb2fe3484e8b71fe271dba4ae1247f4da9.nq.gz
    ├── 000c3a240de508410f9f0a4558d63a8bba18610c.nq.gz
    ├── 0013e59279ca21b76dbebeb0901ae5271e68a582.nq.gz
    ├── 001c4a5151ca6c897c542666859a96a1752f20fa.nq.gz
    ├── 001c5f0682f1d7d7f9a06492cf5aa8641a614b88.nq.gz
    ├── 001e3ed04c6ac4610e1176155e4e175e1cf7b5cf.nq.gz
    ├── 0025ebdf4d0d1def1082e59310c91c4933c1cb96.nq.gz
    ├── 0028456b129cccee235992c427cb3f4130075b98.nq.gz
    ├── 00295692143bb9749b9f96b0ca0b160db7df3d3f.nq.gz
    ├── 002bd6add7fc82227c3452e164d8fb7309640c5d.nq.gz
    ├── 003080806d506eade9c828b8b57b5cc5da5d8af0.nq.gz
    ├── 0036d615d35e677052203fa74badf9b43b23d4f2.nq.gz
    ├── 003ba7cbee594b7619022ecdd8ece340b44e081c.nq.gz
    └── 003c340f1082f3da3dec9f0723e4d9242d7a4583.nq.gz

113 directories, 200 files
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

[webpack/webpack](https://github.com/webpack/webpack)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
