# Repolex Knowledge Graph of pallets-eco/flask-debugtoolbar

RDF knowledge graph data for [pallets-eco/flask-debugtoolbar](https://github.com/pallets-eco/flask-debugtoolbar), parsed by [repolex](https://repolex.ai).

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
rlex download pallets-eco/flask-debugtoolbar
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5751c9ddac8d9571c0bcb25ff586a9eac27af022
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5751c9ddac8d9571c0bcb25ff586a9eac27af022
│           └── chunk-001.nq.gz
├── blob
│   ├── 00e5d6c2f9634e3b17c02627249b6a2a2cdb3014.nq.gz
│   ├── 01afed7b1700b5220565c1b96e513e1cf09dd816.nq.gz
│   ├── 02070f1101fca68ea363b20e40f2d5599258cc89.nq.gz
│   ├── 029e0c9bd65f5dc2aa11d976d4528da4d9abc977.nq.gz
│   ├── 031d59d290bd9fcdd5b27ff5b40aabaa52b72a44.nq.gz
│   ├── 03ffa987c28ae2f8b61e659e69542b606930a2fd.nq.gz
│   ├── 050e1124c53fa8ee6db513f61e548e883350b123.nq.gz
│   ├── 08e170ea9a27a8bc23abf1b120047dc71611af34.nq.gz
│   ├── 0b80c75814e69b7106c82e39e4596d422f961a45.nq.gz
│   ├── 0e96ab21e1c7f32035bc352f98366c29f4ae9088.nq.gz
│   ├── 113947bca035cf7cfb8679b9f58f3b3aa0a84d44.nq.gz
│   ├── 14583c18da9293223610cfd0f1c17deb10b30da3.nq.gz
│   ├── 16181b3be3703e184ea18b756a0be6dcd04e11f0.nq.gz
│   ├── 1850600c11b5a6d01b58e9495636e48c852dd4a8.nq.gz
│   ├── 18d710cf3a30a4647206ef5eb0f506ef612eb87a.nq.gz
│   ├── 1a86433c223039bda5f68f8b6ef10d15e5e0eff7.nq.gz
│   ├── 1c20bd819aa555048d24126387cd1128f412a9a5.nq.gz
│   ├── 1d26967e11c3a2fc6ecd47d7cf8212a1facc6d75.nq.gz
│   ├── 1d9c50793324962cb4109f125f67fe3dd6511164.nq.gz
│   ├── 1efde82b173ffe47e0b7410a7d28addacff74a11.nq.gz
│   ├── 1f47f125e5c06e827ba4df75cffd838547a4163a.nq.gz
│   ├── 2117e5af14e02a68d6df41195c1a0e836217080d.nq.gz
│   ├── 22228a1cd2fd561782e0fc49bbbe17d61007f4d8.nq.gz
│   ├── 2429c1f7258255698058bb55cb729738f6102117.nq.gz
│   ├── 247d41066d8a696f1ac6abeccca43810f499231b.nq.gz
│   ├── 2510ae16cf7288da165dfe6a29717eb24a3a58cc.nq.gz
│   ├── 2a2d47be53f7e15c31b683a4f166461339b87a7e.nq.gz
│   ├── 2a445f9c62843f5205e3e4a920fd49c1808a399e.nq.gz
│   ├── 2a5caac281d52cdfb89b6be892f2fcccea7b3797.nq.gz
│   ├── 2d47c79edf941442667dd9dc683eef0f3d503a53.nq.gz
│   ├── 2d79f4aa7963f3d3a49c1de4379e562017101abb.nq.gz
│   ├── 2ff985a67af35fdfd1076354b771c425867cdab4.nq.gz
│   ├── 305422579da157e225b17981372c45ad8985bb24.nq.gz
│   ├── 32995d090561f80212044efd4b44c910cc071f25.nq.gz
│   ├── 33a3462b34a6e895763b0e1e41330f86b3b723da.nq.gz
│   ├── 378eac25d311703f3f2cd456d8036da525cd0366.nq.gz
│   ├── 39ed090500ca80177fcefb825716cfa4f91d0310.nq.gz
│   ├── 3b296e4ab5edd373970bfc1a7fa0c98120131415.nq.gz
│   ├── 3b30b3c58eabdb47a1c420ad03c8e30b966cc858.nq.gz
│   ├── 3b6cb4167cb977cd40b70ef87e3e6cbf5c5c71fa.nq.gz
│   ├── 3b77829f43637717ca022abc3464645d70047c96.nq.gz
│   ├── 3fb0f3cc42c7bb842337cf635dac839f96129eca.nq.gz
│   ├── 429c90b5c8348cfee20d7f67f125169fe03929fb.nq.gz
│   ├── 4378d8842bf3abd4eb200dd2ac42feea041c78e2.nq.gz
│   ├── 4387cb94113c6b839df50a4b05752f81e0bf0628.nq.gz
│   ├── 462f486346f0a2b45df85fda4d8da1b5a8cc91b9.nq.gz
│   ├── 47d66a012e6f0b765ad64e6807c24ffbffa83658.nq.gz
│   ├── 493e3a639af3411207bf31c2ad2b0f2662507df7.nq.gz
│   ├── 4ad7f1a15a71701630451372a2617a989c4ff963.nq.gz
│   ├── 4cb467efb00fc0b70df58b179906604a3432a3d3.nq.gz
│   ├── 4efea63e0d604a03ff6a253f8cf7dcec814f01a4.nq.gz
│   ├── 4f18fd14d9425416ced354652cbeceac805c3a57.nq.gz
│   ├── 4f2bd66d2cde821c6a90454db8c2f94f538c8527.nq.gz
│   ├── 502817aead179836b357d897685bbd321bfff281.nq.gz
│   ├── 53647f23fa0c89e67f56e26307e5ce927f6aa26b.nq.gz
│   ├── 5406a5ceaee14bbb82ed2c6f8fb941a55f099690.nq.gz
│   ├── 5434a8dd8b15229b7794fef836dfe15dc58bab9d.nq.gz
│   ├── 59e2641a016eedc79ee7c43259ee1f6923c384ff.nq.gz
│   ├── 5c764673ac0b63aa4e3baed927ec22aca2bc056b.nq.gz
│   ├── 5ef505ed920f9c29a54949f88ddea7ea90594c41.nq.gz
│   ├── 60e84a92649d2f5313e0575968fc1974e85d27e2.nq.gz
│   ├── 62c1b887d73cc6325731f0c9c97927df23a42d1d.nq.gz
│   ├── 63ebca9b2ce69957a9f5a0e2954d4aa9e2ecfc6c.nq.gz
│   ├── 652824155b1a140a96e49e3d29967a4e95411af6.nq.gz
│   ├── 655906e93b5166fe67df28ed4eeba2c62a5d8df7.nq.gz
│   ├── 65d6c212767a64d4dc34df33d3185d56fc6ffc8b.nq.gz
│   ├── 66443fb88b63909e0206ea1b07ac1be1f075c941.nq.gz
│   ├── 6a6c2b869c16fa2f38bc67c443d66a10c6c4e9f2.nq.gz
│   ├── 6b6b775e0adde912b9d08a74a9be738f9c1cfd75.nq.gz
│   ├── 6b70cb080e39e06a4c06ba6337a7b8f086de2730.nq.gz
│   ├── 6e3fbb02bb697ed625eae26cff4790fbf5db93d7.nq.gz
│   ├── 71e55cbd9440567601057b7783786213bc5327b9.nq.gz
│   ├── 725bb2c74ebf2c0f3b8b2ba167ce67a647d40746.nq.gz
│   ├── 72c88f28c7ee191bc4bbdde7e9e716da27f6018f.nq.gz
│   ├── 7315c9992e822dea9c9c279f7c8860608a37cdfc.nq.gz
│   ├── 736d16ad02655b15a9d32101fcd03de7544df70b.nq.gz
│   ├── 7387792baaefcd538f47f1cc1b39c78623430a7e.nq.gz
│   ├── 74157867f25acbc146704d43399d6c3605ba7724.nq.gz
│   ├── 75e0665482b1839ac37f450d63d9fbffeb70a46d.nq.gz
│   ├── 769f3bade4e26c126c37bfac947a781668da9917.nq.gz
│   ├── 78112fc6bc84579dec206340dc399e403a545dfd.nq.gz
│   ├── 79e5142d9f136f464690ca5fdf9d1186089a3c7e.nq.gz
│   ├── 7c14dc9202cd0bc2b25d55b76dc0f66e03a7aff3.nq.gz
│   ├── 7decd5875ed9d28675d34276f4cb6870fb10e310.nq.gz
│   ├── 7fa129eac6cd0d3189ada2d38bcc290cc0559fc0.nq.gz
│   ├── 7fc6807f8bf731d4d36b4b40b588c11f2710f79f.nq.gz
│   ├── 865c68597994a02456d113489a5d931464d2b9c5.nq.gz
│   ├── 88680cec340d551bc796b0cf49779d1ffe951e95.nq.gz
│   ├── 8950bf0c8bd4d516323fdac9ce8645cd99b626cc.nq.gz
│   ├── 89971e9d072316276da5d39f7ffdcd822987037e.nq.gz
│   ├── 89f4b5cb4223a4d4bd0bc60529f5423a4168c2d1.nq.gz
│   ├── 8a307f802c4b24d14b75f04fb2cb679080d1b75c.nq.gz
│   ├── 8e3747e74808d9c135b4afff23ce215d074d9973.nq.gz
│   ├── 8e98c47d62dd81903041d0583eba48d2790667a7.nq.gz
│   ├── 8f8342eca231d7c2234dea5725555c7a21c1bfb0.nq.gz
│   ├── 902db6ae1f243b28ca1bce8666b6d98b9dafa8ca.nq.gz
│   ├── 918866b42a7709e69143605918c4adc30863bbdd.nq.gz
│   ├── 95d459ecfc403380226bcea3951d2df141e2bf01.nq.gz
│   ├── 95fef407bb65feab5a56d0afb9d1e578a5c7673d.nq.gz
│   ├── 96f4115af8a96e1fb2ab78d5ac0d9490f16c7469.nq.gz
│   ├── 977e284e0f2bc785c3ec89030af88796b99ed1af.nq.gz
│   ├── 979fae7129bb8589eb9baa6f9754f20cbfc9a60a.nq.gz
│   ├── 97c4e2cf92079aa02e30e8b5f8f9878eee5ccd13.nq.gz
│   ├── 9ac522f7d49d853d2c0698d16a109852b2fa104c.nq.gz
│   ├── 9b75305283520153d681c07651777a26d948d060.nq.gz
│   ├── 9c94e67028e42e52659eaa84edb172628bfeffcb.nq.gz
│   ├── 9da7da626d5eb9aac2c7741f15c6772b03eec019.nq.gz
│   ├── a2ac2e8dffbcdf12caa76515848e472380984f95.nq.gz
│   ├── a466be6bcb177133056b4f87213a79a96fd1cc24.nq.gz
│   ├── aac5041089c2b27b6e9cdd08060cd527f46dd644.nq.gz
│   ├── ac09fc4035781366af9b7693ceaf19cf30deee27.nq.gz
│   ├── ad65d1e1ba707dac768aeeb2fa40d5d7d8a540a2.nq.gz
│   ├── af95753e092ca474a78eebd7cc4b31043e2fa62f.nq.gz
│   ├── b4fd5a25023f91378596f9061bfe8ba46ae30d48.nq.gz
│   ├── b647efd0f15fbcb6ef2cdc0d30d740994f27d6e7.nq.gz
│   ├── b698d14f8282452dc9d18484707b05587e3f81d1.nq.gz
│   ├── b700d86079b7e16b346db0966399efa299cace49.nq.gz
│   ├── b70cc4cf6b73ad39ccec83c2635aea292e6a6198.nq.gz
│   ├── b755e5d09e5d95ddc4d785112bcee77c31639520.nq.gz
│   ├── b89e619eaf08b7b3ca0886b77a5e0b6bd68bf6b8.nq.gz
│   ├── ba3fd777497d8a8369916141293596d11055363f.nq.gz
│   ├── be9c28a7f5f2c0684b92c33945996e0990bd3c14.nq.gz
│   ├── c2e4422897529293d0f344e35d5629a09f41d35b.nq.gz
│   ├── c2ec5c2f6831f512b2eb8edd9e939004f4d93875.nq.gz
│   ├── c46416c7501a40fd130b3f2b180f4ac2e888d8a7.nq.gz
│   ├── c4cdf9fc84241858a6a99b982611d93b985b405c.nq.gz
│   ├── c66a658368ba8b9e637fc649290d3cd26f7886a5.nq.gz
│   ├── c683641554d2fe4e621a1a97a426e1be6f72777a.nq.gz
│   ├── c76f9036cd81da671676b40ce9bdc84bbe696b74.nq.gz
│   ├── ca041800ddd15a7f2bf71447044b1550296a2f38.nq.gz
│   ├── ca96d17a7ddef350d565a5bd306c24379b890476.nq.gz
│   ├── caf78db09c1b4ac63b52e4389d2d0b07bcc66884.nq.gz
│   ├── cb45f9e524b9c5f174187d13c0880710282154dc.nq.gz
│   ├── ceb52942f208c1f72f5924d870d211dfba9713fb.nq.gz
│   ├── cfe8a774ae49c5d0c87356f5aefed2a27d63702e.nq.gz
│   ├── d08808b56c7cc87b044fd12cd44d06bb9ee125a3.nq.gz
│   ├── d0a2a9bb7107f175e8ffeca6be5faf265a0d25fb.nq.gz
│   ├── d0a5d430cacf07486842e77e55fdc429d70c6f70.nq.gz
│   ├── d0ce0cb566b9fb4334fdbaede603aa72ece2800f.nq.gz
│   ├── d16c030e3327d9d338af208ef9b9df52c9dfa277.nq.gz
│   ├── d24782b4f47066f002ae4ff30a3fbf2f112e4ca8.nq.gz
│   ├── d3a13c765dca5afbd2b8a69ebef4017033bdd68b.nq.gz
│   ├── d40e9eeabc1f60b7d73751a35461fb2219992d41.nq.gz
│   ├── d8f17efbe197a780a6d2fa7d84e050586fc1b3a6.nq.gz
│   ├── dba05c0f133d2837aaf5bf527d7139cdbaaa1458.nq.gz
│   ├── dbb67e35faf4686efb8c52eb25dc763f2f38e6e2.nq.gz
│   ├── dbbb7e4960a2fb2aff57dd267321c699e233673d.nq.gz
│   ├── dca5b0f610890d9f15e117937237b1da04982f10.nq.gz
│   ├── e1891191eed88fef0e364f0bbe6a37ccd824b252.nq.gz
│   ├── e50ff72a138fc9b07918a4d57c070db3712b2655.nq.gz
│   ├── e58933223cefc2f0f83586c0baf978f7cb65cce9.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eab4114712f09b3ae5e33206e0e8977885f983f0.nq.gz
│   ├── eefa8bfc12231458b44c00bee02bc2d729c5650a.nq.gz
│   ├── f01d066f134c9eadd457605ec2a8ddb83e6c68f2.nq.gz
│   ├── f1dbcf5089cbf5e29be811d4fd672c8694b63201.nq.gz
│   ├── f223f3d0ec4d1ce37ef2e9d2fd929e895ee93013.nq.gz
│   ├── fac668fcf42af844a3af0a239fa638ddbc08443c.nq.gz
│   ├── fb193819475ced31fb729d40823fceed0df516b3.nq.gz
│   ├── fb5160b45559cdf6461ed8b428a76adc4cf696c5.nq.gz
│   └── fc58d857d9e12773147a609a3e0d90685ca6f9b6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5751c9ddac8d9571c0bcb25ff586a9eac27af022.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 169 files
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

[pallets-eco/flask-debugtoolbar](https://github.com/pallets-eco/flask-debugtoolbar)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
