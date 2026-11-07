# Repolex Knowledge Graph of ansible-collections/splunk.es

RDF knowledge graph data for [ansible-collections/splunk.es](https://github.com/ansible-collections/splunk.es), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/splunk.es
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d72a10b4e972abc8fe7e173d17914409a1c8cf89
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d72a10b4e972abc8fe7e173d17914409a1c8cf89
│           └── chunk-001.nq.gz
├── blob
│   ├── 0045a04695e85cbb1485520b2d988cacad34d3f0.nq.gz
│   ├── 00649f728b496a4823e2096330ef0a595b42fa46.nq.gz
│   ├── 03be69242da7cef859cfa70dbc358720e819ee9f.nq.gz
│   ├── 07e30ca884011e3a4c0fd72e08f74ecca66d9418.nq.gz
│   ├── 08974bab59bff4e7830824ddf18650c7081d67cc.nq.gz
│   ├── 099a17706bb87990a75866ed35a87e23046cdeef.nq.gz
│   ├── 0a7f15bf18d7426b068956497798cdda76e70526.nq.gz
│   ├── 0c1b8a8de4cd8a876d6fd4f8c9a46bbfa9a3d7d0.nq.gz
│   ├── 0cb9121878752bf72d2aa36b90a03e30c3c6ccd2.nq.gz
│   ├── 0f220ae49d4f5995a5d3223719069f2daa7bed2b.nq.gz
│   ├── 0fbfa5c7fdd456cca55e3f6d703a885adbacae30.nq.gz
│   ├── 135c551d1bfac30c63c1f367357ac4991e1f97c7.nq.gz
│   ├── 18ec9db497219a30924321074b5311d9c74ef726.nq.gz
│   ├── 1c0c383ee159b2ec6f4342b96d6f90c8b66da33a.nq.gz
│   ├── 2018127503f4976edc26f7bee828a4242a3dbe7c.nq.gz
│   ├── 22c308df4f934938e40d4f02a66999397e53c6db.nq.gz
│   ├── 23d65c7ef4514be9029e7c1d73b885867d81c383.nq.gz
│   ├── 24eb76a7636721ef70c3153d9a7b743066280fff.nq.gz
│   ├── 252ddc7df156d60300aa2e854f0aecdf773291ff.nq.gz
│   ├── 266833422a8cbf4966c5f19b3d8a9523b7c51467.nq.gz
│   ├── 27157304f35ac882e9dcfd7be6ba7672a34c4094.nq.gz
│   ├── 27cedb07e03b14d5ac40d9a5ce023c651845685b.nq.gz
│   ├── 2a07f4db9b28f772a27b20860d0f8077e99e2199.nq.gz
│   ├── 2a852434e8f06329b8f7cd6f6f0a45451d812296.nq.gz
│   ├── 2afde34d884398f0938527104689efda08612e2f.nq.gz
│   ├── 2b823e3e74202d41ce97849b660d53bdfc61e69f.nq.gz
│   ├── 2ef58f9c3ae4732cf502d4aa1034cfa3b3695f9d.nq.gz
│   ├── 2f261efb9782f8e6858440e79985083f8cf786df.nq.gz
│   ├── 2fcdaa9db171e43051fa9cec1c322cf97a7d1c1b.nq.gz
│   ├── 34994ec1a97f55d019bc18ddd5d3780f7dea12ea.nq.gz
│   ├── 349ba902b6175824c5903071c5aa804f461295f0.nq.gz
│   ├── 363f0f3b58173070ce92759a6e02395ef07b6695.nq.gz
│   ├── 367e8863912caf827b12d8e356d1dbc9a52e1262.nq.gz
│   ├── 38868185dee65e458e610b87edbf14b22bcdbc63.nq.gz
│   ├── 3c81aed42272bc6c4db94f0f3ab9b5a74770cb5d.nq.gz
│   ├── 4138e32fb7db92c07e017bd790619730eeed1940.nq.gz
│   ├── 4482b25d68e9c8ad61c2c75d47cd9f0615eab903.nq.gz
│   ├── 46b42f7e297a8b38b896ee0f2ee097db7f791604.nq.gz
│   ├── 46f2e77114e1def7a4f4ceb5fa027c910c631dfe.nq.gz
│   ├── 47cf117b2de5ebdf3b3499ce9e0fb4098c345700.nq.gz
│   ├── 4ad739da5ca6f705cfd0a3730fb0b840579f1fe7.nq.gz
│   ├── 4c1e5681280877776e0c2a556679bb301b5ba4cd.nq.gz
│   ├── 4c2f174679a209b196f188a2c5e519365075f75f.nq.gz
│   ├── 4cbac1c04ed4d21374b980450378ee4a58f087c6.nq.gz
│   ├── 4d8ae665b68e2f1debd74df5a1edefccfa507203.nq.gz
│   ├── 53f461f8e628ffc36fa63e9aaeb30476eb4e4b18.nq.gz
│   ├── 55dfbab502cf50bf9b077e8fae29da3e3abd9ce8.nq.gz
│   ├── 5750ce071004e94da68938728d0c9237c73cba32.nq.gz
│   ├── 5ad0c8badf1bac43c149e675e627ef549067544c.nq.gz
│   ├── 5b32d4c1097ae6224bc65d88f0406972563164da.nq.gz
│   ├── 5f1bb84b51082e27db03dd6b2eff2a5b8846b601.nq.gz
│   ├── 5f709c5aac15f11a4cb08bbb627883011ff762b7.nq.gz
│   ├── 62c42c5e720b171b9b672354581a02ba7da4ec64.nq.gz
│   ├── 66a92f79afbee6bed028632861bfde2ecae1f6a4.nq.gz
│   ├── 68020d6a3d214dded573d5baf66940306656e2fd.nq.gz
│   ├── 680962c72ba58bc31bc27589c2bf12c35ca59de6.nq.gz
│   ├── 686e29bf4e45c1a3d9aaf8cec881a65bdf195f23.nq.gz
│   ├── 6b7ccd1e0aa69ab53517662ad45a5db057a875a5.nq.gz
│   ├── 6c949f830b1a73c8cc9a89a164f135ff758d1ec0.nq.gz
│   ├── 6cffd9049408dbd6829aebea42b38efaf9437797.nq.gz
│   ├── 6e4ad06fe608cc8bdc58ef2b3fad845737ad0f25.nq.gz
│   ├── 6f0724104c2a004c3bf5c537293cf66fb467cd14.nq.gz
│   ├── 6f5230231e80c08471d5eb3cd946ddc8cc5779d6.nq.gz
│   ├── 6fe2c43ad80ed3695917f9155b12d97ba5afda5c.nq.gz
│   ├── 72343ef051b5a37da6426c8c06ae1a1cf12e5d79.nq.gz
│   ├── 753002a30adcba8c77d0358196da799858fdabc9.nq.gz
│   ├── 755c3d117140107594c7ed99dcb00362abf99591.nq.gz
│   ├── 774b14f2a1e6e3c9be6d99e305948818eb00d0a5.nq.gz
│   ├── 778783e966ae03fb73d5fecfd4c16687a9aa277f.nq.gz
│   ├── 77bc755c5efa6a8d2a08464c64dce0af7ea955bb.nq.gz
│   ├── 7837af0fee4df4dbe99c6bacdae4fe34719d8ed2.nq.gz
│   ├── 78b87b0f4e00c3ad15bfde9af306ad257caaa639.nq.gz
│   ├── 79904a72b20b926d36a4249a35ba834e93597af3.nq.gz
│   ├── 7abd401b2894865cd70e65a44fea09c020876b03.nq.gz
│   ├── 7dd4a0cff51d6853426789ae62200da102e7dd8e.nq.gz
│   ├── 7e79bcaaad632eb0935ed48b3094633f0c2b7de5.nq.gz
│   ├── 80818ecc7d770df0138054552a718cf3192ffa5e.nq.gz
│   ├── 8248c2cd02737896813366dcf4128476476c25f9.nq.gz
│   ├── 845b933387c1e6fc759428a4510c3209afe2161a.nq.gz
│   ├── 84aae20769cf42520beec280ee16daa98813e5f6.nq.gz
│   ├── 8592cc68440df8a89bcd6850dfd01e8e51fd96a7.nq.gz
│   ├── 87612f439c386200735557944c1d56925123604c.nq.gz
│   ├── 87747ada4d8f5458cd7828659cc622bda9165783.nq.gz
│   ├── 87f1e169090628eb12a9c46e2401606cdfc77a10.nq.gz
│   ├── 87fd57a838a0c23556c527e747517799f313e5fe.nq.gz
│   ├── 894634ef20b27ead7407c19d72032e332493b578.nq.gz
│   ├── 8ae1b9670036f2aa593f3055c278e49ea994d999.nq.gz
│   ├── 8c274d3cf88bce2fe57e92b6d16cfd0989cac7e3.nq.gz
│   ├── 8d89b4c96c8929ba8c1395f33f5fb851b377ce18.nq.gz
│   ├── 8de698add33d3e8bdce67de286d356c5d35e4767.nq.gz
│   ├── 8e68aa3ec801b174874ea29f387635ce82446cc0.nq.gz
│   ├── 90fd88f92e3a21ce8f6c5a0ab782423ab4bd97a6.nq.gz
│   ├── 943a537d6e1b4cd0743ddf2e7230d37396708640.nq.gz
│   ├── 95467aacc2274d492f3cfc586b93efcd2866ffa7.nq.gz
│   ├── 99b22dcabce8932272f422de15ddbc326bac2e33.nq.gz
│   ├── 9a633eb11723fc6d693569ae252ae34b8f1b0ec9.nq.gz
│   ├── 9ac80cc15a882f734a8f4a253bcc186b6dc6f374.nq.gz
│   ├── 9b97662e1ed6ead5d58abedc0fe29402c54021f2.nq.gz
│   ├── 9c4284b6ba5406ecd895c668aad29728b1a19962.nq.gz
│   ├── 9eddaaf209b2a7a4911903a637d48bdcfabf1896.nq.gz
│   ├── 9f980a682661fd21aeb97703c0f2dc3cf262251c.nq.gz
│   ├── 9fb608dd420c5a2d36f06d0e5d2dfa388c913080.nq.gz
│   ├── a1b5ac9c88e0e6792b114221dc2909f89cdd6ee8.nq.gz
│   ├── a358b4be1f9ac5e04525d1408dafbe89aaf9f46d.nq.gz
│   ├── a3f8c75d78b45e05637518551d04957ec8a08cf7.nq.gz
│   ├── a60f9307ce9a3c1540a28e1b0440c15454a75218.nq.gz
│   ├── a65e25b803caf9095cc6b8016f593c46870b2555.nq.gz
│   ├── a7a65e7cd1b4db0859ae8944bed91855bf15a82a.nq.gz
│   ├── a7cadf468d5781cc8d537eeb34c25ec8603aca4c.nq.gz
│   ├── a96298b01afa2efdc858adb78f9fed4d124da565.nq.gz
│   ├── aa646020ee42b013461539c7ca48b627fa45651f.nq.gz
│   ├── ab4a4a278659c5598a403575c8184f886a53c610.nq.gz
│   ├── adaa8048163e6b46edf8ee72ed8f239be8599361.nq.gz
│   ├── ade481eb03a26260b71ab15db5007723e47ec615.nq.gz
│   ├── afe50189272580646b646d2ffad0d9cba8b9e37f.nq.gz
│   ├── b0502df25f7c23bf4a227162ed7506e971ba0f0d.nq.gz
│   ├── b25f073573488f1ac86ebd3be7f204b2b8b3b1c0.nq.gz
│   ├── ba9c980fb86bef62c1cd5c86cd09c6cde80b0cd1.nq.gz
│   ├── bae720a3a659264180ff16dbba98b7031877b1d9.nq.gz
│   ├── bc214e4e40d4170046cadbe9093f39b4b0dbc9e8.nq.gz
│   ├── bfa908ee62a6f17d4f1b9c1581076830611e3567.nq.gz
│   ├── bfbb7247c3bf993d82c5ce0d889faba7102a99f8.nq.gz
│   ├── c0f06fff5c9bbb05052ad4a4b5146c3f0d9a6663.nq.gz
│   ├── c0f17637dbd6e38a37bdeb4cb69b29c2a7fa7875.nq.gz
│   ├── c22a4d116eeb960a9e22519d77969e63ede82dbf.nq.gz
│   ├── c48607568acb67f472a2dffabf687b4e1e73fa9f.nq.gz
│   ├── c5935e4601e4f7e2f0e4a615878a871d1abe0245.nq.gz
│   ├── c69f1169c2d1843296a83c9daf1575ef9fdb86a0.nq.gz
│   ├── ca2020b108fc19af31e8f596250f720b69aff85f.nq.gz
│   ├── ca2a2f9793acd950c95a31bd11571fe813cb8ebe.nq.gz
│   ├── ca3308f114832ba3b76a07a3d39b20d9a53007e5.nq.gz
│   ├── cd427f9981ffbcffa404679b40136884639c1bb4.nq.gz
│   ├── d12998142f35d1327550fa65ad45c8cf856c0edb.nq.gz
│   ├── d12c1efe28855cdc80e307a52f723a465d57920b.nq.gz
│   ├── d28a392400a837a8c186992418f22ea3757266a1.nq.gz
│   ├── d2c82039e3f344be44944bf7e423adaa578dcecc.nq.gz
│   ├── d575990e21ff78641142a93068df21d6dd0bebc0.nq.gz
│   ├── d76055233d260d398993236c90f94330d45a6bbb.nq.gz
│   ├── d999d280801e7ef3caf1e9642c2830c07a538425.nq.gz
│   ├── d9e0e935219dc3ee917ce098a8d742b0cb369694.nq.gz
│   ├── da13dadfa638b33425c3fdff0c81ddc51d412ff3.nq.gz
│   ├── daaaec773dad341d705d3c1fae9da81dd591ada4.nq.gz
│   ├── dcba770318ba28e25df2b98f6055ed6400b804b4.nq.gz
│   ├── ddfb77caa7f71de1226f7a5ff806fd0bf2af0f8e.nq.gz
│   ├── df210c99520beda34303d34d1f4299b72c8b93f4.nq.gz
│   ├── df95a35aa1b0ddd3d2e1cad471c8778bbf23c5e1.nq.gz
│   ├── dfb936ff05b46f1757cf5956c58b7df17a47d512.nq.gz
│   ├── dfd094670aea4cae046d80c83bac38e23c000a92.nq.gz
│   ├── e09514e209d78a2aee735dffc9d45697a9bd11c1.nq.gz
│   ├── e1480c2f7cbd0a8b1b03df863c39c24e26eab703.nq.gz
│   ├── e2435f2ce65e8916aabeb4491699a8cb38f296d0.nq.gz
│   ├── e2fa5c8cfeecc32fa4b60f7a662e08fa382692e7.nq.gz
│   ├── e3e5966e40943337d9c5a64a67fb543c55caaa6c.nq.gz
│   ├── e5218aca35440bc5600077c00ae746b92e92181d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6c9a685a158c95fd2f4b6e6e1489adb09c85ec5.nq.gz
│   ├── e78d8615b9d6df008597c0e07741e07ed24f9a5d.nq.gz
│   ├── e79ad31a6eb53d17c403d835a500fda9afbd6caf.nq.gz
│   ├── e8446110756b5849c5190ed28c6c106bb910ef18.nq.gz
│   ├── e8a6c83563123b820ed4c319a3b55a9f6137a6a9.nq.gz
│   ├── e95417a55f82cd6b823efe3603187bb3792a7624.nq.gz
│   ├── ebba41e355ef8642a932d9cbb84a4b36f9e5bf60.nq.gz
│   ├── ec0ff90104bed690ddd5b25e5d5451b76657c547.nq.gz
│   ├── ed00f6e506d683efcc3b6f1ea7cc380a17cadad9.nq.gz
│   ├── ee1b9020c5027839f2415710d1c3bec2e57fac8f.nq.gz
│   ├── f0124db389c5b1549b92e0582d06fd65fe7b508c.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f425a0f12c136b9794b754c672abd6f2a186b6b3.nq.gz
│   ├── f42f49e7fa1b812fb5a86448460c35815e7c8dbc.nq.gz
│   ├── f4abab44009cd70cfdd151cd139bd052dc96ad06.nq.gz
│   ├── f5003ee0695506e084625fcc0662a34b89be0748.nq.gz
│   ├── f81832ab7423b92c2ead8420b51ed63ae59442aa.nq.gz
│   ├── fa4225f3eddd267a91bdd4c2d2ccee679c90ca97.nq.gz
│   ├── fbced61b46e45ce3a9dea3c5005eb48066be5a03.nq.gz
│   ├── fc00e6cd0aec43173e887d6006af0e8bfdf3fac1.nq.gz
│   ├── fdd3a9946df7952c8df222017e8b45f28d1f0137.nq.gz
│   ├── ff3acaa91af41cb3f0958ce19c086e50b0a45b8e.nq.gz
│   └── ffb8f12fb3d09bdc670b45d133e3adb13ebf357c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d72a10b4e972abc8fe7e173d17914409a1c8cf89.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 186 files
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

[ansible-collections/splunk.es](https://github.com/ansible-collections/splunk.es)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
