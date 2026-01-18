# Changelog

## 0.1.0 (2026-01-18)


### ⚠ BREAKING CHANGES

* v1.0.0 ([#147](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/147))
* **memu-js:** use fetch instead of axios

### Features

* add configurable batch_size for embedding API calls ([#114](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/114)) ([060067a](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/060067a5ebe8ad36c4ca4ad2cc6033303c3f1a36))
* add conversation created at ([#120](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/120)) ([825df56](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/825df5640037fa2345c3153c3df89174059551b3))
* add GitHub issue templates (bug report, designer feedback, feat… ([#132](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/132)) ([aee22ee](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/aee22ee94f275749f69367b83a02a2e819cfd001))
* add Linux ARM64 (aarch64) build target ([#156](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/156)) ([0c90fcf](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/0c90fcfb19fc3e91b951f4ba7454798e4b83e42c))
* add LLM wrapper and interceptors for LLM calls ([#131](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/131)) ([416e102](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/416e1029e7752f173c133ebc83bc42801a313059))
* add non-RAG retrieve solution ([#84](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/84)) ([fb96e54](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/fb96e5405f1c0e3477929b7d9874e624dd0453cb))
* add usecase examples ([#94](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/94)) ([47b5b39](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/47b5b390e065ccac1cd2173fa2d6c41549e01063))
* add user model and user context store ([#113](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/113)) ([7c37fb1](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/7c37fb166b0a85bf7c89d0b109cbaa882fa80064))
* add valcano model support ([#110](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/110)) ([704c302](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/704c3024946e8d4a1d1b13ffef33126bb68bd9c4))
* add workflow implementation and postgres store ([#122](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/122)) ([a175811](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/a1758110f859f3725960d308fa0344a1056be52c))
* initialize the memorize and retrieve workflows with the new 3-layer architecture ([#81](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/81)) ([4a2e86c](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/4a2e86c0e8bc3e50c82c4fde33d07ad741c8a65e))
* patch & crud workflows ([#127](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/127)) ([3cd3dc6](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/3cd3dc65ae9488207ff8fb0c81e4adb0d22c0f91))
* retrieve args change conversation_history to queries ([#98](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/98)) ([6370c6e](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/6370c6e968c9d0922120bf2a41e8b4206bab87cb))
* support summary in sdk ([c553dd1](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/c553dd1c070771f1d813b7a029f0efa0b321914f))


### Bug Fixes

* __version__ ([101eb85](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/101eb85a9e5bdb33f797ed2b95a265b69f657b0e))
* action & recall_agent behavior ([458eb50](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/458eb50b8ebfd209f8d498ecbd97f74a05dd4a62))
* api docs ([bd56372](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/bd563724756df43786990851cdc3b0e8ecd93b15))
* base url ([6156523](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/61565230ba5c6add52fc1afbd2111e7b7d4e828b))
* category summary & category user scopes ([#125](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/125)) ([a24efd5](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/a24efd57df2e305fa3eae8622ea889318979c2f7))
* client bugs ([585a6ab](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/585a6ab3f3bf62273144da27e283c4d8bb009a72))
* config & resource caption ([#142](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/142)) ([ea4be13](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/ea4be1396c0f55b02d706819f6c2b4d5c6e68be8))
* correct binary name after making a release ([#91](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/91)) ([0fa721a](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/0fa721aaae294c6f230221af11084a0a6c1f478d))
* custom memory type default prompt ([#169](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/169)) ([5a0032f](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/5a0032fc0f29229524d0356d454a3f5991e04f7b))
* default embed size ([#192](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/192)) ([144fd32](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/144fd32cfd6917b08f29cf56f251f239c360d2ae))
* delete memory api response ([da6ba8f](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/da6ba8f2914e6c916e9659ae3e659de8cb73b5df))
* dependency & logger ([b36e0be](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/b36e0be7bbc91ecacbecbe98db0c724414389b81))
* docker config ([57e2368](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/57e2368635731f3b5d3e082a4fe7e6557ed47fd1))
* docker setting ([5de93e0](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/5de93e0e79886f98aba7f80a5e899969d2f20f76))
* ensure both Linux x86_64 and ARM64 wheels are built ([#162](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/162)) ([51c9ea4](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/51c9ea4335a1e9eac227c79783d7aa8cca2b883b))
* example 3 output ([#117](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/117)) ([65ef7c6](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/65ef7c6a497047f0f86938cf77ee4602a630216b))
* file management ([e026bd3](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/e026bd330c7c0da7f786e2f4e19d03bdad0002ec))
* get embedding client ([#152](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/152)) ([76716a4](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/76716a4f00127a3cc21444996f32a9cf810c9282))
* javascript api & reference ([15d5f03](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/15d5f03cdb6d5fa37d8b5fb1328c04e2bef22885))
* js example ([2e60229](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/2e60229d56549415266614f6280a7b8e1245b0bc))
* llm client bugs ([f895283](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/f895283497cb9836c9ed1f592366ccfa02d72e56))
* llm client profile & wrapper ([#157](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/157)) ([e55c668](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/e55c66847eac3ceaf276587d58b76d953d7be9f8))
* llm model ([df7716d](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/df7716d80e9381cb77358c7b9bbc96579043f463))
* memory server remove agent id ([619187d](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/619187dfc8cd901695a10414f25329d453e129c0))
* memory type ([1b2acec](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/1b2acece8267180f47ac90b5b52fb3b601999161))
* **memu-js:** add wantSummary to retrieveDefaultCategories options ([b1a27eb](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/b1a27ebbefdb6465c2621d4102b75248e71db36b))
* **memu-js:** add wantSummary to retrieveDefaultCategories options ([22f0453](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/22f045384845ef9dbbccee52166ba4fdf061d511))
* **memu-js:** use globalThis.process instead of process ([64d59f0](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/64d59f0ca8738991e6d0af701dc7649e89735850))
* **memu-js:** use globalThis.process instead of process ([581805d](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/581805d3aaea93579fee7968519c8d4eeb4466c3))
* model definition ([2656ba5](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/2656ba59aad163bd9fe0144ac6e01a88ccc5c229))
* model name ([918dff6](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/918dff6891a530cfc7b9866a57382f35868f24e5))
* node-js sdk ([3b2c625](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/3b2c62569b8bdf75e68651ddf894012e402c92cf))
* path -&gt; str ([1d6f311](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/1d6f3116041cd045758069b3534a58f5f6f57057))
* postgres model definitions & database initialization ([#124](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/124)) ([7d5e0cb](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/7d5e0cb02837a6e2071d3c3344ef6dad613f9a43))
* prompt & item fallback ([#183](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/183)) ([bc95ade](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/bc95adeb26789104c0bbe199e126cf05def27941))
* pydantic model mismatch ([5ac250e](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/5ac250e6a189902ecfb13f43b6c89a2ede7c99a2))
* python sdk endpoint ([a05dfc8](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/a05dfc823d931c364460e9fbd0f3cdbda8bf7f8a))
* qrcode ([c160284](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/c1602846011f5659da8227bb116ad57a9f74ad14))
* Readme incomplete ([#148](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/148)) ([f8bc748](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/f8bc748b9ebfb652ca8a5e06edbbe7eb648ed4f6))
* remove duplicate and unnecessary issue templates ([#133](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/133)) ([559ec14](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/559ec14d2561ac09162bbb93f178e0f74cc58b23))
* resource caption miss problem ([#111](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/111)) ([85586f5](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/85586f52d6bd6355ae440ad06d8cc6779c689ce8))
* session_date ([27ba530](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/27ba5308dbc13a22184564b713c98167b5a8823e))
* storage path & cleanup ([c4e968a](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/c4e968a7e87af3a1208fdde2c1d7093d9f9d280f))
* v1.0.0 ([#147](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/147)) ([23f37ee](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/23f37ee403ecaf88b48af0144e3d701c22ccfddd))
* version number ([efa3534](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/efa35345754d41f453c11ae873837eaf2e3f9681))
* wechat img ([635bad8](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/635bad851e1a513e0303d6ddab35d953b14fd8be))


### Documentation

* add custom LLM and embedding configuration guide ([#160](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/160)) ([29c414a](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/29c414a84d1c9c2f989e2165d0b6508c3fe62862))
* add docs folder ([#181](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/181)) ([919d2ca](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/919d2caef23107d539c36f30c44d4fb5aa38b324))
* add German translation for README ([f6d6ab1](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/f6d6ab1a51b76bd4312542422aebac89410b8da9))
* add German translation for README ([76c3fc4](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/76c3fc4227a8e349fbcf1e5bfec29d68e984ff7a))
* Add memU-experiment link to README ([#119](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/119)) ([2d908e1](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/2d908e17ee2e15b95d4eb2f35dd09f924d57f8cf))
* add readme cloud api ([#144](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/144)) ([42fd5ba](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/42fd5babe6748ef54254cf114a54bdefea304f07))
* add template ([#158](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/158)) ([b79a78d](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/b79a78d25b96e670888c18b8f09277db33803865))
* clearer introduction and new agent examples ([#115](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/115)) ([da27875](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/da2787536d91490f7a96a0c7379abd1ad1c6d9ac))
* fix api doc link ([#146](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/146)) ([23ce7d1](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/23ce7d19b1d68f4fd0a5a5ac6b756f69fede8d09))
* fix example file path ([#105](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/105)) ([21aad6a](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/21aad6a7f070e7666ac6a41c91980a4fa9696918))
* fix issue template dropdown ([#167](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/167)) ([14d0333](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/14d03331ed14f1e593fdebbf561189a3775651be))
* fix README and CONTRIBUTING to match actual codebase ([#130](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/130)) ([65d7ef4](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/65d7ef414563395c6cfa0a75343864671c11b62d))
* fix readme test case ([#107](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/107)) ([228306c](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/228306c897402c633f57c7aa31e8c6cd4e995d5d))
* fix several words in README ([#89](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/89)) ([1e3baf9](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/1e3baf92d5a08ec51a7eda3249bbd4b40530f56c))
* highlight OpenAI key ([#106](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/106)) ([5b6ce54](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/5b6ce54def5aa7743a85bec629da65bfa9d8333b))
* highlight readme openai key ([#103](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/103)) ([fc4154a](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/fc4154a707220ced4359e7296218451c43cf0681))
* issue template fix ([#165](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/165)) ([5d91237](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/5d912372e1bf70d7ff573cd5b92e917118048e25))
* modify readme.md 0102 ([#136](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/136)) ([f114ee4](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/f114ee46c8639b256472a8e989695b2f2215f4d4))
* remove legacy docs ([#154](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/154)) ([11fda41](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/11fda41dda8a5c38b790d3c2fb7053b57b16606e))
* revise README for clarity and roadmap inclusion ([#86](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/86)) ([2235b09](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/2235b099acc7e92ac52b2613fa731f85259d58fd))
* update images and refine punctuation in README ([#88](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/issues/88)) ([cc375e8](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/cc375e89a9b49bda0b7057eee696d74c4c1d9cee))


### Code Refactoring

* **memu-js:** use fetch instead of axios ([19e934e](https://github.com/Vishesh-Paliwal/n8n-nodes-memu/commit/19e934e0bff3f6071c75277606d4b77835b1b040))
