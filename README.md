# Repolex Knowledge Graph of pytoolz/cytoolz

RDF knowledge graph data for [pytoolz/cytoolz](https://github.com/pytoolz/cytoolz), parsed by [repolex](https://repolex.ai).

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
rlex download pytoolz/cytoolz
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 61a0e4885162cf9e0a70d9c77c5b5cd2ea28a37f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 61a0e4885162cf9e0a70d9c77c5b5cd2ea28a37f
│           └── chunk-001.nq.gz
├── blob
│   ├── 0205bd6859588d6ab3d052667cfee7ee8c960e12.nq.gz
│   ├── 0b0b5162e12651996b70393c7c0148965cda641f.nq.gz
│   ├── 13309f4461b3ff02585f24c8a27404f726126a74.nq.gz
│   ├── 15cd4f8ec33eeb971071385158d85d0b75b3c882.nq.gz
│   ├── 165b11fde3dee9d4de4e48b3c49a18412a076362.nq.gz
│   ├── 181235c4d701bbcbd654e89c4cc6986307eff0a1.nq.gz
│   ├── 185eec5df49872d33c91170aae49d25f073363c1.nq.gz
│   ├── 188224f601635493b11959b306f207e4c2ea3f1a.nq.gz
│   ├── 1dd90514cdc1aa5e3bb221d4e0346ce2c3ec4999.nq.gz
│   ├── 21555874ce75129d098774581a0a8058c25c0075.nq.gz
│   ├── 226d58f2ef8cfda69486c5b8b39ea7a5dd7d6edd.nq.gz
│   ├── 22d91bcf13cc1d3d172bb6e9a64e31dd7348a263.nq.gz
│   ├── 2356b47bad4700f8c523af3f9162e8e52762c5b7.nq.gz
│   ├── 238bd791eb645375c710a81f525842531f061581.nq.gz
│   ├── 24efa3d091a2443d110f0ed2adffd54ed53ec4b4.nq.gz
│   ├── 28bef91dc80cbbe412da6d860904f23561705f3d.nq.gz
│   ├── 29075f4022fa21afcde6c197f727017bfcfa6d7a.nq.gz
│   ├── 2af5c4508a94969f6220f099d9eecd91ee9842a1.nq.gz
│   ├── 2b62f24f40510ace436e1c5eb427f01531996b06.nq.gz
│   ├── 2c283721f3962f4798ebdb77eb1f33d007405f24.nq.gz
│   ├── 34d48d7d767d126fa1a8fd20434a68a4d77cb1ed.nq.gz
│   ├── 3778dc47593b42dc5008b35fd18e0ca39d665f3c.nq.gz
│   ├── 3fa1b7a90c97aa1bcc81374adcd752cddbf16d66.nq.gz
│   ├── 412e8fa563ef5d7085a190c083178c780b75b7b0.nq.gz
│   ├── 4338520b402bce541882405365680ef35b0faaf0.nq.gz
│   ├── 4ce9204dcdd73eeeba7cbfc13001c65b2d2da3f6.nq.gz
│   ├── 50924f54a29890c1f1c7914ed3a5924ce712a5af.nq.gz
│   ├── 53114e3ec72eeb0b2b62913e871dde11342a394a.nq.gz
│   ├── 5e9316bf9a4dbef81e4a5cf1ef9369425ce4a51d.nq.gz
│   ├── 61107949db49c08623832c58ba7f8238e3ddaae4.nq.gz
│   ├── 6a8dc8903414db48a5cff7dc2c5dd28400f3da3d.nq.gz
│   ├── 6b5c0986592103792fe4f5a9f3838f94c36e04d1.nq.gz
│   ├── 70dd8bc5b49a0ae7e20c7d6f24ae7a95660a3777.nq.gz
│   ├── 7bf944388e42ce2e3b4f7dabda1c655cf6eed4cf.nq.gz
│   ├── 87fa7f2390a78630f8003c5352af4494f50423d2.nq.gz
│   ├── 8ed7061837d32eb99240f17948a1187ab1a24b28.nq.gz
│   ├── 97fc4b6592fe519a2dc80d4c48d79198567e4922.nq.gz
│   ├── 99b5de8940be6ee01caf754eeeb153938d477b47.nq.gz
│   ├── 9d112e4cb80d6e36b0d28c1d0cb56c151d6de91c.nq.gz
│   ├── a392a6fde7e14200e2a63defea38663f74d1728b.nq.gz
│   ├── aa0bc3938d09ca806b50b9528a5818a409810bb4.nq.gz
│   ├── aa1dc0c7db09dd428b532bc2a66a3237e5494a2f.nq.gz
│   ├── ab331e8beb5698fd285e717c564c7a89323737a9.nq.gz
│   ├── abb5afb5276d5edf8e1ede1e3cc5b2a09610afd0.nq.gz
│   ├── bc91e279cc12086329e321393b3e39d80c4b7cf6.nq.gz
│   ├── bde7f37391d8aa83fd9a69e97772ad509ae84770.nq.gz
│   ├── c08d2ff8fbb7f342496314f2a17b07939ad5e8ce.nq.gz
│   ├── c5db297bbb8dbeb636fd04bd45b06e7279992227.nq.gz
│   ├── cb83693d29d0c223008cdedd0496a3aa8e0b69df.nq.gz
│   ├── d0396b2e5e9a555740152acecca8375d077bc932.nq.gz
│   ├── d1fe7913bffcf125292ad89486df376fbaeaa786.nq.gz
│   ├── d380307298dbe8c2fd3bfbe3cd0a741f407f01a4.nq.gz
│   ├── d7badeeba7b49d82464a3d26fbbde3f788236d87.nq.gz
│   ├── d999c48c1279fa742751a2406e190b7991e74f23.nq.gz
│   ├── d9b7277449d22470d747df9fb24c41137b06b5ff.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ec635144f60048986bc560c5576355344005e6e7.nq.gz
│   ├── f0d36c954bfec9fef48b771155ec2537bdf496f1.nq.gz
│   ├── fe3768af5b81d0500947d9782bf27aaef8b33489.nq.gz
│   └── fe5d56d142bbe4c4d669e6aca43deccf264d8216.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 61a0e4885162cf9e0a70d9c77c5b5cd2ea28a37f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 68 files
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

[pytoolz/cytoolz](https://github.com/pytoolz/cytoolz)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
