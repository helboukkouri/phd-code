# Code Compilation

This is compilation of the open-source code that was produced as part of my PhD:

| Repository | Publication | Short Description |
|------|-------------|-------------|
| [helboukkouri/acl_srw_2019](https://github.com/helboukkouri/acl_srw_2019) | ACL SRW 2019 [[paper]](https://aclanthology.org/P19-2041/) | Better in-domain word representations by leveraging a (small) target task corpus along with pre-trained embeddings from the general domain. |
| [helboukkouri/recital_2020](https://github.com/helboukkouri/recital_2020) | RECITAL 2020 [[paper]](https://aclanthology.org/2020.jeptalnrecital-recital.3/) | Comparing in-domain BERT [(Devlin et al., 2019)](https://aclanthology.org/N19-1423/) models trained from scratch with a medical WordPiece [(Wu et al., 2016)](https://arxiv.org/abs/1609.08144) vocabulary vs. versions re-trained from general-domain checkpoints with a vocabulary from the general domain. |
| [helboukkouri/character-bert](https://github.com/helboukkouri/character-bert) | COLING 2020 [[paper]](https://aclanthology.org/2020.coling-main.609/) | Variant of BERT [(Devlin et al., 2019)](https://aclanthology.org/N19-1423/) that consults a word's characters to produce word-level open-vocabulary representations. This model is shown to improve over original BERT in both performance (medical domain) and robustness to misspellings. |
| [helboukkouri/character-bert-pretraining](https://github.com/helboukkouri/character-bert-pretraining) | - | Code for pre-training BERT [(Devlin et al., 2019)](https://aclanthology.org/N19-1423/) and CharacterBERT [(El Boukkouri et al., 2020)](https://aclanthology.org/2020.coling-main.609/) models. |
| [helboukkouri/mesh-embeddings](https://github.com/helboukkouri/mesh-embeddings) | - | Pre-trained concept representations for [MeSH](https://www.nlm.nih.gov/mesh/meshhome.html) (a medical knowledge base) built using the *node2vec* algorithm [(Grover and Leskovec, 2016)](https://snap.stanford.edu/node2vec/). |
| [Anonymous 🥷🏼] | [Under Submission 🔨👷🏻‍♂️] | Code for enhancing general-domain representations with knowledge base information. |

Moreover, there is an [ongoing pull request](https://github.com/huggingface/transformers/pull/10053) for integrating CharacterBERT into the [`transformers`](https://github.com/huggingface/transformers) library.
