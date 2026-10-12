# Repolex Knowledge Graph of executablebooks/sphinx-togglebutton

RDF knowledge graph data for [executablebooks/sphinx-togglebutton](https://github.com/executablebooks/sphinx-togglebutton), parsed by [repolex](https://repolex.ai).

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
rlex download executablebooks/sphinx-togglebutton
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 76bb31f8824428cf66acc864ad6506dcbf90051a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 76bb31f8824428cf66acc864ad6506dcbf90051a
│           └── chunk-001.nq.gz
├── blob
│   ├── 020601e7359ae9b7ff5813eab854cc17beb304cd.nq.gz
│   ├── 05cfc6c94d8949ee5a01ea8ee0c1d2ac0cc2078a.nq.gz
│   ├── 06b91bb2b81961e6060aefeb7bc783c42d392a59.nq.gz
│   ├── 080365996f524cf3fad8a0f2417959bdbe0842ca.nq.gz
│   ├── 115c20c3e160cc1eef00cb9fd7932540dee1bf51.nq.gz
│   ├── 15fc833dc9533d74a0f077aaf9a00180835c9605.nq.gz
│   ├── 1e8ceaf51239fc15e62243a7b1eae1e5d6ee6194.nq.gz
│   ├── 22d6c7e80d86d9414dfebdf570fb898f548ddd45.nq.gz
│   ├── 2a6fe24c9f72136a46a40878695e7c1cd503fd49.nq.gz
│   ├── 2b2ede6a5d2d4736c9e1279a1b427c508de878d9.nq.gz
│   ├── 2f1bcf1ab315d7156b8cea4a2da529032c8c73fc.nq.gz
│   ├── 30a2b039697e40f1596132ec5297f9af99e2476b.nq.gz
│   ├── 30b0be09561fdf3f8068fadd28f5256771b2efd5.nq.gz
│   ├── 3272a99789f4b55a1767bff65ed4c5ff9074b468.nq.gz
│   ├── 35810f9e910541c35171823af730ce30eb43a9f8.nq.gz
│   ├── 35f2cfcdbe78ecaaaa65897ca0ccc1cc275e7b47.nq.gz
│   ├── 38483ba8def8c2de20759a941082e71a0cf3b40c.nq.gz
│   ├── 3bda369657bdf758ece869f902694ed2219b4ab6.nq.gz
│   ├── 485cbdb117faa2a78602e262e636456fe3ca7bcd.nq.gz
│   ├── 4b822bb424aab391212696941d7fb3806276954c.nq.gz
│   ├── 4ee2cb7dec307dab91c8e0e432867a6741d4c3b5.nq.gz
│   ├── 55395958e1b5bed738778bafec4ef6d4bc7a7be4.nq.gz
│   ├── 560f453eff403f4e1578cf668fc09ffc983845f1.nq.gz
│   ├── 5704221714a0f41cf72799f96ff33476935200e1.nq.gz
│   ├── 5735e67e05504c12f51637251ec7624fad2b4d02.nq.gz
│   ├── 57c72bccb692102273a3c234edd687a1e895b1d2.nq.gz
│   ├── 590884c5c6800544382b96a6017540b2b3f0fbdc.nq.gz
│   ├── 59ac8b196b0aeba78e375b4674c6cf1339e202d5.nq.gz
│   ├── 59f376ffc62af84bdb6459412548901a93a1023c.nq.gz
│   ├── 60021177f38140313af6a401edbfb03d98f95274.nq.gz
│   ├── 606849326a4002007fd42060b51e69a19c18675c.nq.gz
│   ├── 63c8e858ffc165d8787cb9c2a1ea44aac6b139d3.nq.gz
│   ├── 63f81e0dd3e9bb1727c290f86cafc82544b82893.nq.gz
│   ├── 66efc0fecd1554e6e4681fcb149692591f388bf2.nq.gz
│   ├── 68bff258a7d0855d3c330ffd140684021e92de5b.nq.gz
│   ├── 69a5dea6920aec6bfe99047730fbce6e4c9552d7.nq.gz
│   ├── 6af26cb210446b101c7368dc792179ce9c7ac27e.nq.gz
│   ├── 7b4c992b7474a535c1acd6ffe2e666ab0b3a6675.nq.gz
│   ├── 8217e7d92912eccba2ebab875f3c705c6dbf4c4a.nq.gz
│   ├── 8324f6c6b802ccb28d069959c0ec1cd0b09e4a11.nq.gz
│   ├── 85e701ef83635c7644a51c64a5c9df21689fe0dc.nq.gz
│   ├── 86a735ccfca649043f502b8e56646701f889deb4.nq.gz
│   ├── 8dff863da016003276534924d9c16fc89b7d27ec.nq.gz
│   ├── 9789d3be575d9ac53596997ff3c39d72e1275134.nq.gz
│   ├── 99c916fddae65d34765ad12760e85ee6290051b1.nq.gz
│   ├── 9c3f8205c5d2e9b86a89d57389a56c1791b2c792.nq.gz
│   ├── a03667fa0d19dd1f6d5c0200ac929d9ae64344c4.nq.gz
│   ├── a09723705e0c330c993d2c696f21beccde30653c.nq.gz
│   ├── a318d887101d7664b570aba0204cb7ead5952c6e.nq.gz
│   ├── a7e1104ef7b765d693ab2dda55d9d6ca5b1b92a5.nq.gz
│   ├── a81de3db035d7ad9c633af509ddfaa819b63fc04.nq.gz
│   ├── ac90f238585f76e45c5c1aaac6138ad5aa47d7c4.nq.gz
│   ├── ad2a490268adc878bc196c3d17195e91a9e9eda5.nq.gz
│   ├── ad640c0d369461fd458b7ea4a70ef9b9d17df489.nq.gz
│   ├── ae676dc6643c10db8a7f2a8b479d36c40c1a8f27.nq.gz
│   ├── b109b690b5afcc99c3c24419eea707b31c1f5bc5.nq.gz
│   ├── b16c536554a4962680a7b19ec19b248ee7c3afa4.nq.gz
│   ├── b2b458a22ac5c0006cf651be85b836f7faaecbd2.nq.gz
│   ├── b6a68bd3d0ffcbff8e15bbd0177d069a80c6522f.nq.gz
│   ├── b9cffa1c73f15cf08cb19ad56551fa1bb03f23de.nq.gz
│   ├── bf37e5f5cce6002574f1aebce3cd8df364da01d5.nq.gz
│   ├── c10fb4ddc1ba2c076af678c49dc3d0f167f720db.nq.gz
│   ├── c6af43ceede5eb95747833cf7074e46451ce02fc.nq.gz
│   ├── c777a46961502854ad3a116b369f4f06dbc51f64.nq.gz
│   ├── c8f53e329cbf442f9f7c6f915719c80d04cf672d.nq.gz
│   ├── cdb662f8131b07bec2fdfe2ddfc1a9e3ac298cf1.nq.gz
│   ├── d55b5415eba79d98cc8286c4e85d6bcdd548eb31.nq.gz
│   ├── da60039f134925ea55d91c4d43ed95c8034fbb0d.nq.gz
│   ├── dab6ba48f3dcb26eae65920afb84113b1ebb141f.nq.gz
│   ├── dbfeffcd6e7bbcd593965c89bdb8e111e107f458.nq.gz
│   ├── e0074aa34e987476a214065f5532b302f0613e6f.nq.gz
│   ├── e1264139b37bc1e47de8397800b93d60fc2e53a4.nq.gz
│   ├── e21de4dbfa2e7850add9e0393685364b97e708a1.nq.gz
│   ├── e5f0dc284501f30b188f9db5635f7160e07f2666.nq.gz
│   ├── e75629e706c27bbd26af4632ccc74c0c86e5b14f.nq.gz
│   ├── e7b67d639ee3039d471ce683fecf5dea36d96890.nq.gz
│   ├── e7d2af6ec410e6c7cffc6501359024f057458e32.nq.gz
│   ├── e8fc04d1981d920b528343f76549f8847c1b1eee.nq.gz
│   ├── e92c03ff6343b99454cdbefc7400af4780496d89.nq.gz
│   ├── e9ddd5a349625b25a52417fa2ee3fd3913a41306.nq.gz
│   ├── ec6f79e804f0ce28861c03f12233b14b92523ae6.nq.gz
│   ├── f1df7baeba2025c934e6b5dce12a2f31f56a57d9.nq.gz
│   ├── f6273f6d4d710413bdb49120e9654cb34fc62639.nq.gz
│   ├── fc536aa62b559eb7ea502a2f52a3b8616005d700.nq.gz
│   ├── fc8ccd9deb1e8af81c7c5c55db2810a92e7803b3.nq.gz
│   ├── fd65b47c4c5397475566941e6791a028a66d5b67.nq.gz
│   └── ff9790a9c5949b4b506c013b546623f7092a6ea2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 76bb31f8824428cf66acc864ad6506dcbf90051a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 95 files
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

[executablebooks/sphinx-togglebutton](https://github.com/executablebooks/sphinx-togglebutton)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
