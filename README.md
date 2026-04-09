# Repolex Knowledge Graph of nedbat/coveragepy

RDF knowledge graph data for [nedbat/coveragepy](https://github.com/nedbat/coveragepy), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download nedbat/coveragepy
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8130bba7b4a22df5c775b9a1439d2d5370d349e3
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 8130bba7b4a22df5c775b9a1439d2d5370d349e3.nq.gz
│   └── repolex
│       └── 8130bba7b4a22df5c775b9a1439d2d5370d349e3
│           └── chunk-001.nq.gz
└── blob
    ├── 00acecbcab80dc3f3bd2b1ba407fc39c8855d63d.nq.gz
    ├── 00c243de63c28fb8ee891ab34ce2f4d3f43ad161.nq.gz
    ├── 00d65624f3bdea390893b93976cf802e9ab32fa4.nq.gz
    ├── 0175f5afda476589f2e6e6e4a03e44595f4f1f37.nq.gz
    ├── 0182ebd21372e5f84fa0aeb6d7c10f9f724002da.nq.gz
    ├── 028a19fd516a52fe577cc3df24491f02b57d6dba.nq.gz
    ├── 034e288eb9a3ce18d88dfd6ff676032a651079be.nq.gz
    ├── 0453424b48841a380a89bdf091a528fb3e37ab46.nq.gz
    ├── 049ee1fd95ebbbf1d7f97def97d292bc310f142d.nq.gz
    ├── 05173369f7896c0541b209ffc1a60d1b9ca7cbb9.nq.gz
    ├── 051a31ee85f7f26e909dc865d53a3b663961a2c7.nq.gz
    ├── 072f30ffeb3b3aa756bdfe76d0bcbe5880547309.nq.gz
    ├── 082ccbd123d15c18f14050260683f39c161440ed.nq.gz
    ├── 090efbf528e0b7333ea0ccaf2a02554548f98754.nq.gz
    ├── 09362da38765ae955c72f7b80e24298112edbe6a.nq.gz
    ├── 09b21e03c7f058af138ef3ae7767ee24477ef6d1.nq.gz
    ├── 0b71f3a2ae2537d2fb6425a97403444d9e384399.nq.gz
    ├── 0cc96e5af695e3d782e939dfead7f1865f3c6429.nq.gz
    ├── 0d38e33e94a0a25391238c4037f6155276c8f39c.nq.gz
    ├── 0dfee7ca83841ae8360a77087469c0c04253e8a2.nq.gz
    ├── 1030f9f8b958dbe77a2069134b49b129f5539353.nq.gz
    ├── 11d7aeceaa72903dfbc04437c0e63536ee7f8627.nq.gz
    ├── 13daca146b8d6def2c7f49ba03e6c37c8ab0123e.nq.gz
    ├── 155e4fdab0c35eb2e8a1befd86bafb2f7eba6d51.nq.gz
    ├── 158d1fb4933473bf0d62cc18deed3a6d414a9b4a.nq.gz
    ├── 1623b0932d73d1911d0c36489f6aa3ce5624e5a9.nq.gz
    ├── 163014172af05ed2fb0e75835ad90c5a680f4781.nq.gz
    ├── 194f16f50dbcf05856ce16285bd30269904d953f.nq.gz
    ├── 1af82c43f80fe0952e781d3e68a28851dd540b81.nq.gz
    ├── 1c7ee604796190126dc9aa15984e669563d5af58.nq.gz
    ├── 1ea45d46e9a3bcbda05c9047c6e9a1b8f2a506ae.nq.gz
    ├── 2447cffe38c51df8d1eabad1a8a76b5b11a99d98.nq.gz
    ├── 249e123bd2d533a1b579202bbee988292463b6cd.nq.gz
    ├── 24e2932c105cd6a49abb9fbf5cbcfaf912d09595.nq.gz
    ├── 26a0b650f2133cf543c1421c8dea77087da24e18.nq.gz
    ├── 26bc56bcad844ca6904463f1fa986c0423e941f2.nq.gz
    ├── 27b49b36f967bfd299790b775b5777a70967c402.nq.gz
    ├── 28ad7d2da49a4c326888ca160495f1f0642001bb.nq.gz
    ├── 29409d517a246ef00f13217bbb41a819557a0974.nq.gz
    ├── 2a5c59ce24bd118d149bc28a5edccb2af4aef09f.nq.gz
    ├── 2ad134c916f50b5902ca449fcab7f7fabf8d868e.nq.gz
    ├── 2b2086b16676c28cb9c4434232bb3d45d81a8517.nq.gz
    ├── 2e21eb643cbd0c3b77ee91387deadcbc317193e3.nq.gz
    ├── 2eba2f4966ede5e7b746e32318373a8ec7274160.nq.gz
    ├── 30e6df60bf1be117dc8b1d8f8e8616f2dd330eb5.nq.gz
    ├── 317dc4d9852df72ba34e10a6f61d1838cbbd969e.nq.gz
    ├── 3263667a4c5bd6f0be86b2169185f789ae597e45.nq.gz
    ├── 3283fbdae4bc7f30dba6d5ce56f03c4c1d73866d.nq.gz
    ├── 331b304b68325ac6c6d53f7f2248c25d070f5156.nq.gz
    ├── 3390a8549d1a4a32afab0eb2854536fd276fac5b.nq.gz
    ├── 34da8a066309f901187361d82ffda7746f98bd98.nq.gz
    ├── 34f4a92e72eee176f925e9210088b5e9f47639a9.nq.gz
    ├── 36b0b993da66144995e07dcfdc057ea8554e6cbc.nq.gz
    ├── 36ee2a6e65f754f3d3a6b2d81aa6ebd865310a12.nq.gz
    ├── 372dd4fb63dcf9538fac29e0680d7b83d126f484.nq.gz
    ├── 37606838eb64dfab474807427229017d50addf56.nq.gz
    ├── 3768f1aecf0152ccc1cb0e5843e97a0424a0f873.nq.gz
    ├── 37ded535bf3aedaab83178834d1bcb70a5e260a6.nq.gz
    ├── 38d7a840f658c1badd0c91c1f382a69498e51d76.nq.gz
    ├── 38f2ff8b06aeed5c083fb5fac13e899d33a6a526.nq.gz
    ├── 390741e565c0ce7dfd77700a75f13840ed2cacd9.nq.gz
    ├── 3ad581571cfcdb86e0c501463941bec741649ad5.nq.gz
    ├── 3b3078ba27aaaa17ac97a99e465384fb43b5822a.nq.gz
    ├── 3cdd1ed9b20edcadb25b560820fdab3eed6baa35.nq.gz
    ├── 3e7f9b66b887b551407cc3ca4c20c1bd492e1913.nq.gz
    ├── 3f0e38d1fb5b1ac150d0d3b50f8088cb9ac23bba.nq.gz
    ├── 3f6ba54bab4f7e46bbbf05c1316a822060d95b92.nq.gz
    ├── 415dd4abe88969c510a03f72c6277281d4638a3a.nq.gz
    ├── 420b1cbb88320934c3ed8ab0008f653a11305253.nq.gz
    ├── 433310b1702cc53b2885338f0130fadeaf0cf86c.nq.gz
    ├── 467764a63b14560dbb540c45bec0d044f954701f.nq.gz
    ├── 46c41fcd31d489a840b29e6fc1c5ad0d72cae71f.nq.gz
    ├── 47782ae09006eea5e971e5c6af24a8476bc9ed81.nq.gz
    ├── 47955742382e9f2d479c97408f8142327ecdaa59.nq.gz
    ├── 482936abaae6650299b6c3e1bfdda59e6f85d0a4.nq.gz
    ├── 48f9d098c8ab587b739ee24e6bf3fd2fd78cc730.nq.gz
    ├── 4916864df34b9f87b0b6b4680425fdc4088210c6.nq.gz
    ├── 4954d249d3640ba62485e74ca4662ccbcfcc0c11.nq.gz
    ├── 4a8721abbdb9b617a0419442c12c5a26d99f2147.nq.gz
    ├── 50821ed294bf2715ebb830098a8322a90b3a0c2c.nq.gz
    ├── 50ba96a350c27a77ecc4e9612b611f4d4655ccc5.nq.gz
    ├── 5205b9c2ed30c9cec657a5823d6be8a2328f51e9.nq.gz
    ├── 53b9c0fc3f37d546a2f8c1b8fedcf95de3f3331d.nq.gz
    ├── 53d7f17526ba31b873ab48fed6312cfb558ebc71.nq.gz
    ├── 54378b3bc8c38a3d96ae5ddc9cb7220d067aa1f4.nq.gz
    ├── 5568a70b8594eb9317e783df8c9fabf4dfbb792e.nq.gz
    ├── 558c846eab6b125b284784be23a1c015eadfe5eb.nq.gz
    ├── 56cdfe801a418978a64f04173e0e14fab2380379.nq.gz
    ├── 57a6c078402714e0dd863aad12c6af970b041c0e.nq.gz
    ├── 59742bbb92403cbdaba5f5656ba53238695af28d.nq.gz
    ├── 59be645c49a370a027379ea6a60559391a73bfc0.nq.gz
    ├── 5b0e03457a784ee76bf6720863b9045483c9de86.nq.gz
    ├── 5dd1dfe3f041283e7370e51e60337b6a9a717ed7.nq.gz
    ├── 5e5a5ff5f2a28ec9d05a7ec7464361ff54b56712.nq.gz
    ├── 5e5c0ea3429572a4be0db5fa835cf5a0d3ac75b8.nq.gz
    ├── 5e7ec8760ee66502c46034ebaa9ce926f22b127e.nq.gz
    ├── 6048d6da6dca807e0cf0a590d6eb6a81085090a9.nq.gz
    ├── 604ece7acb8e6a71aeeb18ee51107e96591b9454.nq.gz
    ├── 618f1d048d83dfe3ef8d3586cffb99bb0dece86b.nq.gz
    ├── 63ac1d9c3f1c0d7f0795fadda57134debe40ff99.nq.gz
    ├── 65f80470061873ac9058ec2b9276b79ce8108d35.nq.gz
    ├── 662317253d7ff3f1fc811d45529c420e96ad1ab9.nq.gz
    ├── 674ddcb14a356709eb57af52e9823270c36043fd.nq.gz
    ├── 680441be2a945a6571f0e8fbee16c1640f216839.nq.gz
    ├── 6997b489bb6b3aa4278e625779bbbda98aead602.nq.gz
    ├── 6bc9fdf59893ed3054c6c2c5fd3a10bc1b8c5d89.nq.gz
    ├── 6ca96fbcf7247b857b728c95c7d92c278a4b49bb.nq.gz
    ├── 6cccbcbe8efb207b571041aa7615cce481018e90.nq.gz
    ├── 6cec3dd7ee5090985afefd5b8a01870b5c1ab967.nq.gz
    ├── 6d012ee692e209e275b729d7aeb5e5c8fde1277b.nq.gz
    ├── 6dbf7e0d9a41201fe358bee1fa4ae886fc7742fd.nq.gz
    ├── 70c4a8901e092e58641be365478401c77e87ca51.nq.gz
    ├── 71e08bb0a50fdd1a3a9c5314ca55fec9ffa715ec.nq.gz
    ├── 73d1532ba60e30cdae6e84a805dbec55ac3a005b.nq.gz
    ├── 76fbd4c31fbc65ee5b4cc464320b4e89ffea801d.nq.gz
    ├── 770e97f972d8ecb34e8e46a6eaa923839816a034.nq.gz
    ├── 77593d8f07d016f4b6c0a8eff49eda97249af59c.nq.gz
    ├── 779cd66192c2c8df163b1fc795012cae17aa9657.nq.gz
    ├── 79764751e5ba1128175954bed9cc0bdc096afb4f.nq.gz
    ├── 79aa4e2b35d798e911fd677c78bb59b0ed556cf5.nq.gz
    ├── 79ec005bc2173ce0c42b3d32bfa356a8d98f8d1a.nq.gz
    ├── 7ab4d3ef9227c7bc2028bc7e8ff398d3d0747ca0.nq.gz
    ├── 7b42976d5725e61475e5e3099209a8f119737936.nq.gz
    ├── 7d4024e0afa9e4183884a42a61a62ea76d3fcf9b.nq.gz
    ├── 7dbf91c846ba33f873c2119690f016168c4d96b5.nq.gz
    ├── 7ddde47a5a9b949bfa5de2bc4a48e67e3bca6a04.nq.gz
    ├── 7e8e88f9a0ba4982dc78d0f71d876b26a5097b93.nq.gz
    ├── 7eb9bd3704377ef5e36dd85e51d3ce0eeb5ce01b.nq.gz
    ├── 80f75424711e838c71e1e76f53205d94e66afa47.nq.gz
    ├── 81aa66ba16764bd2113d0f1327cd6d13ee999287.nq.gz
    ├── 83e9e6b11ed7605615e4c4773e6808078466be1e.nq.gz
    ├── 860f9a50b1f23c5bc6265cfc48c0bf380777c462.nq.gz
    ├── 8649f0475d8d20793b2ec431fe25a186a414cf10.nq.gz
    ├── 86b1fdbe4b6d9fd5f8598b1f4298192a930b499a.nq.gz
    ├── 86c69cf504660f6beda6e250f5bf84562648132a.nq.gz
    ├── 882befb3f796528790b329b0e71098d4841a8c98.nq.gz
    ├── 8994a9e3d6051b709a58edf4771f79b6368d4f5f.nq.gz
    ├── 89c1c7658f020fbdce37b18670720dca865d8c03.nq.gz
    ├── 8a365958feb815273349b1aa8d2fd4c626c6b074.nq.gz
    ├── 8a3f8c227aacefe550b9d48fee0ffacefba5b713.nq.gz
    ├── 8b6651bc5bfac7aee2da17094b97b998b21e284d.nq.gz
    ├── 8c96c02fdcc057b2b7b804565ac72df8073620c1.nq.gz
    ├── 900da7318229d62a15cb686f8dfb469ded1808d2.nq.gz
    ├── 90875404e4ccbb64f8a6c4822b8485d33f31bbc8.nq.gz
    ├── 90d076f1429ee52f278060eff345cc1d6539f0c2.nq.gz
    ├── 924f9b772b2d2f4c3299a54d1d6f138f13cbbd31.nq.gz
    ├── 939386e3fd9bc0c5afb7199a83fa0fc2cd78cf24.nq.gz
    ├── 94669cdc9dcaea287163a548b6aecdeed0c53c4d.nq.gz
    ├── 946f8fcbde686306ab79a2badd08387afa608c98.nq.gz
    ├── 948ae697123085e580c575c2c1127bbe82570fcf.nq.gz
    ├── 95d12bf78698bb68bf908553b5161af11240b528.nq.gz
    ├── 9604e5c08c59f50ee7a3c4992d19a479e190bf8a.nq.gz
    ├── 97b4d88d3bc79acc6f543498e191c127743ed7cc.nq.gz
    ├── 984bf7483297f03d45d512c144c02384081d532a.nq.gz
    ├── 999ab6e557d68c1f98b1115f4aaf3ca3a9881d36.nq.gz
    ├── 9b9a997d8ae3a5162a30167388d45f18cf45b700.nq.gz
    ├── 9cb8f715b0a5ca78160c2fb9bff0c6b2cb70b719.nq.gz
    ├── 9dfc8f5ee431dc01f1f234516d16ab3f73cfa581.nq.gz
    ├── 9fd35dabf5cfde05acee6bd872eea5c789ffac00.nq.gz
    ├── a150fdfd0ff9bd9d06336a2066e1a36ec2b97816.nq.gz
    ├── a2188587edca0efd34bba23cbf2cade6dae5cea3.nq.gz
    ├── a27e7d981811b408cb640952b8c1fd75051e7148.nq.gz
    ├── a330167e20518f573385c76bd5ca8cf8de83a9e9.nq.gz
    ├── a34d036bb0a4d3a7933086012bf830b0d06de81d.nq.gz
    ├── a3f5daec7a128ba2d9b4919477268928aeb0341a.nq.gz
    ├── a48251fb983a7d8939dde7317778144f4a02b0f7.nq.gz
    ├── a4a460c008f00e3ab05baa99bc70dd79b976883f.nq.gz
    ├── a4f1790dd4dd0d892a1967a11b0ebf1ec7979692.nq.gz
    ├── a7eb11fccca4d574483d8793f802f08def12b129.nq.gz
    ├── a9cfcc2cf2c5fe111c21f72a888458616a2e34d4.nq.gz
    ├── ad717f5380cf32020d206c2c55f100add8988211.nq.gz
    ├── adbbc619017cf85b0831922c6145b8869d1e4c84.nq.gz
    ├── adce7989b4d9d6623e3a7b92bc6d2ffbf0f04433.nq.gz
    ├── aeb416e4060e784d8eef285c7cd6550f48ef885f.nq.gz
    ├── aec00c71b9ff2b7b7173bfafe0b4eb1fda3157ac.nq.gz
    ├── b023db0b333b9ab3d2fe48e9d24dc210a8f07522.nq.gz
    ├── b1611c1b8a7bd3f887933079957059c5aa79b37d.nq.gz
    ├── b2792c87760f3509053286513fd0ed15177e39ac.nq.gz
    ├── b2ccd67c04d85c4e79daeac1b47ca2de03ba7c67.nq.gz
    ├── b40a174b48e53b8c0c7265bf51a1bcb205e7adab.nq.gz
    ├── b45cba8cebba3fb5a2e4afe0ddcdba14332e3280.nq.gz
    ├── b4e18e81ac63fed97f6c956eb5250bdd130b7b25.nq.gz
    ├── b5cb0903924c8de4094e4475f0d4490fef762744.nq.gz
    ├── b5e413cc8d9d0f3b5d5e3ce4f3ddf237d586c2d8.nq.gz
    ├── b6361da5603145cdc490a2fd24efa8c8f2d8e95a.nq.gz
    ├── b895fc6086207f9ec749fcee114afc4d1792a6ab.nq.gz
    ├── b8985e4bbdb1b90ecd59b229a507b9d96153fe76.nq.gz
    ├── b903567ccf3b6bf56d30468f6dfb1268e53a5f20.nq.gz
    ├── b948aa7c1ae3f047950943d4b91fe8a6344ed47a.nq.gz
    ├── bf203189b10d7c8113204e4b1f3d2694948e7a3a.nq.gz
    ├── c0989f3de46eddbd902ccb87d6350d652ff7e8fb.nq.gz
    ├── c09d45f16d7e35a2a57d33b1ecd02e0b60f02e9f.nq.gz
    ├── c0d91bc99164c6475022e5b5990cc8be9da37a1a.nq.gz
    ├── c150087d275fa469513e3557e3b1b8694ce33789.nq.gz
    ├── c2151d34bca6b9bd008f8db0eec6ef08e792b876.nq.gz
    ├── c2b838dda64684b0999894c9c9935ba2a3f960b5.nq.gz
    └── c334628ad92044bd65bcc7ae7dd9c14eacc2ed25.nq.gz

8 directories, 200 files
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

## Source repository

[nedbat/coveragepy](https://github.com/nedbat/coveragepy)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
