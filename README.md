# Repolex Knowledge Graph of huggingface/safeagents

RDF knowledge graph data for [huggingface/safeagents](https://github.com/huggingface/safeagents), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/safeagents
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0de8e22d2345b2379779161abbbffa72738a78a2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0de8e22d2345b2379779161abbbffa72738a78a2
│           └── chunk-001.nq.gz
├── blob
│   ├── 01f543611dc754bb42a13b989092da6baef921b9.nq.gz
│   ├── 0426be5f615a0e89f20ccbaf6191bf77595097be.nq.gz
│   ├── 0431f78449b39f952105fccba5331e0c5321fd20.nq.gz
│   ├── 06011cf21672853d81103c1c3671b79198b99074.nq.gz
│   ├── 0bc446413148095d123d643db0eedbbcd6146471.nq.gz
│   ├── 0bc558d918ececc282888b3f496c56e89eb7b507.nq.gz
│   ├── 0d7314e7daa50667f410cde66a9b5a1f267b495f.nq.gz
│   ├── 142fa069deaa5782c21dd8dfd6df88a78cb41e6a.nq.gz
│   ├── 1553617ee333f8ec6f82ac221d21e9d74b25cb5c.nq.gz
│   ├── 17a2d5c0ac94c55eadae13cc9f23aba88a84bba8.nq.gz
│   ├── 183aa0e1b39913366aa2321ac59672b147f16cf0.nq.gz
│   ├── 1c128df56b8ce8849e598477c96b1cf890de8232.nq.gz
│   ├── 23dbf740335f9c158b52d6cbeedb8ab8614fb43b.nq.gz
│   ├── 268830a2b0eeea8de0f153b45ed444b90c503a78.nq.gz
│   ├── 2837ee0f10305cc9376e242fdd75cfc2746a76dc.nq.gz
│   ├── 2a4bd29909e7b73b72d48da36c3893aceb41a342.nq.gz
│   ├── 3127519cc8b8077fd8bb2c621cd36d70ba378d22.nq.gz
│   ├── 39b1b6ef0f706f2b03d82c1ae08eb97f7de8794d.nq.gz
│   ├── 3a796f328661e0119a051f429e95f1719f4ba28e.nq.gz
│   ├── 3e95b719050df0be96da5d3a8bc40c769328777b.nq.gz
│   ├── 4330ffbd52ce7227ae9488d52888d1a473a55737.nq.gz
│   ├── 4f3904c4bcaf8c232fdc4776cbd996ed6c4fe412.nq.gz
│   ├── 52c5732fd855bb38798ecfe4ab272c57c234fd5a.nq.gz
│   ├── 54c2a49ad22852c70b2511a0f1d9a2f2d314d2b2.nq.gz
│   ├── 55a22cb550760334388f07e39ea5b15632ea24c9.nq.gz
│   ├── 57c0a2826bab387a98156de3920cd37c282b4f67.nq.gz
│   ├── 6028ca1396ffcc64ea2f400630dfd3a882bb7114.nq.gz
│   ├── 62b77754f54a230058d1e197cecaee9a2675a289.nq.gz
│   ├── 637111c4f875fb5bf6a14f887e8827b2978b5f18.nq.gz
│   ├── 64396cac19294dfad4d4386bbb0d0cae37186485.nq.gz
│   ├── 66123d4f23b87d11c75e58aba11d20efbcfe9bf3.nq.gz
│   ├── 67f384c6eafcbc5ee856afc4b0872c231f7a8e60.nq.gz
│   ├── 6ae2878c1c8f379e30ba139b54a693ecacf7f361.nq.gz
│   ├── 6b418769cc058514ca0a5d0a13135e1e01f8ebc0.nq.gz
│   ├── 6e7abf5f582a7772ad364f49a29418a195e6c7ee.nq.gz
│   ├── 7d311d7445b9af68ff96efa27a3f31975b71d9a9.nq.gz
│   ├── 7ef7c073c9dd4ad7436d88c7ed52512e3fb0d376.nq.gz
│   ├── 864990da250481ddd61521f47a4dcc1293bf6911.nq.gz
│   ├── 87812a68432d0b220d8271e8987919ce36372c6d.nq.gz
│   ├── 8a8f63ea3f2487f775ba334b1a950daf000bab09.nq.gz
│   ├── 8e5a97c11d81fab2edfbbff2110ee0d2b17ba94d.nq.gz
│   ├── 8eacc14cfdb80543ccd33dd77c18f7dfe7d29697.nq.gz
│   ├── 97d1a7bb844d7ea334941dc0e639680174d365f9.nq.gz
│   ├── 9cf55f6395edb47268a21af83b9e7762ed5b0b6f.nq.gz
│   ├── 9f1a370cadd70e9ea9f2d6260fc9cc4fc324a107.nq.gz
│   ├── a21f284efff4116d7d52ca3bdcde250d65d8e234.nq.gz
│   ├── a4fbcfb4238c6a21739e7d22ccdacf358df49a95.nq.gz
│   ├── a7eddf25b8cc7ecba33b8ed775cc23b6dd02e0ca.nq.gz
│   ├── ac77f01b120e6b569f446af6ba11a8fe5703ed15.nq.gz
│   ├── af98d594698b0317ea375616d624f9ee1a4d4b34.nq.gz
│   ├── b81acbfed2c948eacddbf02b210d580d10e39f90.nq.gz
│   ├── bf392022e8d56530e4ca7b1d35a829a014a2b20e.nq.gz
│   ├── c21b2e23e7722fd3a56c910bbf59df826060de5e.nq.gz
│   ├── c47e85b9ab6e212265f2ed9c31540f5818208eb3.nq.gz
│   ├── ca8872f6db47fd3177b8e079568a3186dc141fe9.nq.gz
│   ├── cff31ce2f72eff38f215e180dd4ba35ba8526667.nq.gz
│   ├── d2c968ddd77800f60aaf983cd6aaf8453e64e694.nq.gz
│   ├── d5e42daa6a1d2df804e405d266a8b8cf96cc0e15.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d7ee9a501a0d8fe4b978962c74887f4012715056.nq.gz
│   ├── e0282582d388d213446bdbed69a18cc70af16078.nq.gz
│   ├── e55c1275ddc86a471bcf261e8dcf217b4d2fd885.nq.gz
│   ├── e6c624b85ff8675eb3db69c0c10e206038481916.nq.gz
│   ├── eafb57338a79d12a9f0f6970d9df17f81b56c330.nq.gz
│   ├── f40b00b83c128822bf922b58dc4d13ae087b2e0a.nq.gz
│   ├── fa634e4c4e24c0ddc83f47110dc8a092e24ad823.nq.gz
│   ├── fc50b369fcd781b7fca2a20d19378d44e2b7f272.nq.gz
│   ├── fe9004e66097cf8ab961dea11c2a0bafd4775fe2.nq.gz
│   └── ff19c108dcac299ba8a4194cd014d6b992e69212.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0de8e22d2345b2379779161abbbffa72738a78a2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 77 files
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

[huggingface/safeagents](https://github.com/huggingface/safeagents)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
