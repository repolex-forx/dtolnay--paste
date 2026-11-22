# Repolex Knowledge Graph of dtolnay/paste

RDF knowledge graph data for [dtolnay/paste](https://github.com/dtolnay/paste), parsed by [repolex](https://repolex.ai).

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
rlex download dtolnay/paste
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a2c7e27875277450ed28147623ba5218dd23e732
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── a2c7e27875277450ed28147623ba5218dd23e732.nq.gz
│   └── repolex
│       └── a2c7e27875277450ed28147623ba5218dd23e732
│           └── chunk-001.nq.gz
├── blob
│   ├── 05b8deba835ff62d47ef63dc2ae169105e72445f.nq.gz
│   ├── 1a74a61d73012bbb461af136055898d5714ff5f2.nq.gz
│   ├── 1b5ec8b78e237b5c3b3d812a7c0a6589d0f7161d.nq.gz
│   ├── 1e9f2d0a24350606e49c19348f2438af3ed386d0.nq.gz
│   ├── 1eaba3147a47d9fef922c7d63268ffe2a4802dbb.nq.gz
│   ├── 25387b1140112c7d3783d1580118aea2b35f7930.nq.gz
│   ├── 2b39c8f599f64a36d77155e4e0c96e0cb105f160.nq.gz
│   ├── 31aa79387f27e730e33d871925e152e35e428031.nq.gz
│   ├── 39cb770d98f09c92ffc09a198c19a0e683005978.nq.gz
│   ├── 3c7043541fad869e6fc46a07d76c023e31b7c87c.nq.gz
│   ├── 3dd66aabdd185261fd63dbedd25c5306e61546ba.nq.gz
│   ├── 44fefbd3e0dd2a85ae6efc68f382a254a7d041c8.nq.gz
│   ├── 4f26c9cfe5ef68fa9e708aadb678292096236d49.nq.gz
│   ├── 50b3b0dd019e3420a093fe0c82679a27ee2c5290.nq.gz
│   ├── 55255ef90251dede32feda23a97b32ff9e57b8f1.nq.gz
│   ├── 592a047021d1ca336f2fb1b6d09861612e742e0b.nq.gz
│   ├── 60de9ede2698b6df02bd40d9bf2246ea0d69db6a.nq.gz
│   ├── 63ee5161c787b9f21d2092ec8f3d092e1f9866f0.nq.gz
│   ├── 693699042b1a8ccf697636d3cd34b200f3a8278b.nq.gz
│   ├── 6a8cf3c44b1b1bd8e1059da05851684247b24e2a.nq.gz
│   ├── 6c49808651b0fd469bc6fdb62eeb773ef1a67f34.nq.gz
│   ├── 750707701cdae985156601cc906195021ba6a6e5.nq.gz
│   ├── 7974a6249e43040f8ac079e1f0c7ba3abb61329f.nq.gz
│   ├── 7a9c490d8c88495e4967f256593f8726bddc83eb.nq.gz
│   ├── 7b4bc4604d813b9a95c83b876f91bb4d7ab794e4.nq.gz
│   ├── 7c5badb257f6cf68f319257ccdf3604254d64f59.nq.gz
│   ├── 83099129dfddd7413ac0b7dcc7e22e592e13292d.nq.gz
│   ├── 99fe68f1ff5a502cd01f21a1f257d9ba0f1e06f4.nq.gz
│   ├── 9bb86bfe093047710fbf4681a44a4e0f6878ac0f.nq.gz
│   ├── 9db91eb5176c31e823550768acf699d47a1d9086.nq.gz
│   ├── 9ed32244666ffe749e3754d5320d99c8b7c9ef10.nq.gz
│   ├── a1ef2e2f586a1e5a9177cd307ae24d73c85aa292.nq.gz
│   ├── a65b36ae80318e91c725fd1228a6fc94f22825c3.nq.gz
│   ├── a802b4580f4eb692128433ff9205b390464fc18a.nq.gz
│   ├── a8e6bd860d14f243a09841721137a45c8496d8c2.nq.gz
│   ├── b49a5b409719d5453a8874b730eb9520f33c4ce5.nq.gz
│   ├── b5c60af450c47dcd0ab63b6a46925a66e7043f63.nq.gz
│   ├── c32d4245d03a2b813618ee5cebd2942682c287b3.nq.gz
│   ├── c6d8c3d59c554eec128517b1630b3f5555079777.nq.gz
│   ├── c9e5fe1c03dda53f9909f189ae5c8ae8f3db3e9a.nq.gz
│   ├── ca1585e8cf227fb6afc0ca2ca167013c7937b8da.nq.gz
│   ├── d0edb9243a95fb8e108cf9e70aad5833db560b67.nq.gz
│   ├── d66b843b2752b9822cb0750aeefac58b27112ac1.nq.gz
│   ├── d723cbc7ed92f1ddbb4184621e0f0069416bfe7c.nq.gz
│   ├── f66f5c15e02b73017cfbbe6c2ba57353d96e6ad2.nq.gz
│   ├── f72737589594128c33eb067c63f31067d77f9875.nq.gz
│   └── fdea4d619d7cf75b812e3e5e44c12eaa8499916b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── a2c7e27875277450ed28147623ba5218dd23e732.nq.gz
├── filetree
│   └── a2c7e27875277450ed28147623ba5218dd23e732.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 57 files
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

[dtolnay/paste](https://github.com/dtolnay/paste)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
