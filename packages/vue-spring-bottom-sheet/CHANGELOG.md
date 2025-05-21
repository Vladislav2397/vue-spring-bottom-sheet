# 1.0.0 (2025-05-21)


### Bug Fixes

* add delay to animation start in BottomSheet component ([10dc3ec](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/10dc3ec60d4f1c1d90661cef3f515d053a81ba79))
* add missing css variable and data attribute; ([ed9628c](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/ed9628cf6be2385be915e9ab48a835a60083075f))
* add missing external dependencies in Vite configuration; ([85324b8](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/85324b8db000cdacda812740c2d263335e7665a8))
* change windowSize from visual to inner; ([fbfa6d7](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/fbfa6d7560805ff261a6af145558326696d336fb))
* defaultBreakpoint renamed to defaultSnapPoint; ([384d5d1](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/384d5d1ade62ab3b9b8bd2b1efed2216046c33ac))
* document scroll on dragging; ([0cbb45b](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/0cbb45b2f40e6de261198735621ad7784345cab0))
* ensure height does not exceed window height and add missing drag event; ([1f9344d](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/1f9344de4d3ceccf170973449e3c50e6f20c6757))
* ensure height variable does not exceed window height; ([9855fd6](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/9855fd6d189f72a4cd0f70cc71fe48628c0178a4))
* ensure numeric sorting for snapPoints ([ac8c06f](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/ac8c06f19adc926fce7fa2b8ca0064a44151ac38))
* focus trap with fallback; ([a82e3a5](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/a82e3a5c7dad447dc2c492a8c6b62818350d2434))
* glitching when height exceeds window height; ([7d2295e](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/7d2295e3133f4539152eb4aa7aa39d60414d8028))
* https://github.com/megaarmos/vue-spring-bottom-sheet/issues/22 ([4cbbbcf](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/4cbbbcf5bf392b11e4752b14230c265063445ae8))
* **playground:** Local linked library name ([d35c03b](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/d35c03b563a56baab36ed390aeac108c6050e398))
* prevent height overflow beyond window height ([c75dc1a](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/c75dc1ab21b3fbec16b8ce4cd70d64af076b8870))
* scroll and drag at the same time; ([a355779](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/a35577946cd7eca460fd74f72dfa838e982f4e2f))
* scroll behavior for single snap point; ([e85d177](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/e85d177bfb844b3a3dbe12d959a5d5f378de8b4b))
* scrolling and dragging both with single and multiple snap points; ([2f1efe3](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/2f1efe399eff8672730a6838f6a9b7a58a304f48))
* sheet does not react to height change on minHeight; ([75499b9](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/75499b90b5fc78f365e8ea59ab36dc4b07bdee41))
* shorten scroll or drag condition; ([3d4fcdf](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/3d4fcdfbd9e3cd1a12f4c52db8b2c91e7727b83c))
* snapping when sheet changes height ([bf8ff93](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/bf8ff93dc34e3297abcbfd0d775e8d1de6335d6c))
* snapPoints no longer requeued; ([c2a4eb5](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/c2a4eb5612fff3d4c39ffde9da6205ba0ea3ab8c))
* the height of the sheetFooter is not being included in the calculations; ([9748c2d](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/9748c2db1f4eb4cce91c26474ff260598b00568c))
* update build step to change directory before running prepublishOnly ([08daeae](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/08daeae87171170f9b7cc1bb80cc28b61ffff8b3))
* update export statement to remove file extension from types ([fd1d1bd](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/fd1d1bd225c59ef7d2361205d4a160e227fbb0a1))
* update height calculations to use windowHeight ([6ecee8b](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/6ecee8b0d9e5d3cbcd263b54a1e6d23111bae553))
* update import names in README and improve package description ([ccc41df](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/ccc41df58a220fed6489eef2d303a8d1bbc3f5c1))
* update npm ci command to remove workspace specification ([95d69d6](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/95d69d6b6d677335493eb109900b611af5780e44))
* update package name in README and version in package.json; ([6120442](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/61204422fb61654aa350b451c7aa5c715a0b03df))
* update scroll prevention logic; ([450b2ae](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/450b2aeed44f57d78d1a965bb517a4c53c09693a))
* using useElementSize instead of useElementBounding; ([89963c2](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/89963c274a2094501a7ba590373e022dca19bd47))
* width on mobile devices; ([9ce9079](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/9ce9079d1812c376fef6f981bd70db597fd172f5))


### Features

* @vueuse/motion and @vueuse/gesture replaced by motion-v; ([e099ee3](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/e099ee3238a0190aed64fb14efb6b2c7f86ad720))
* add content drag; ([e45e049](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/e45e049434e7f16b8ad015b3dd20f7cbdcb2ca3c))
* add css variables for styling; ([45db5e2](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/45db5e25848c28551bd1177fc19b76c959ff19a8))
* add customizable header, content, and footer classes https://github.com/megaarmos/vue-spring-bottom-sheet/issues/20 ([fbb7b30](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/fbb7b301774803e51edfdce45a09cba3789bcea2))
* add dragging events; ([2d3a3b6](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/2d3a3b6b84ffb09ef77cf9f73b5fc94d4951631f))
* add dragging(panning) to header and footer; ([4595707](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/459570765a5050083b6e2e5b0e722126cbbe3688))
* add editorconfig and eslint configuration; ([ac9bc3e](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/ac9bc3e6b25648d7d76116b65273ec797fcbbf6f))
* add initialSnapPoint prop for customizable starting position ([689c54d](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/689c54d99dd2090d646b2322833f8a0e27573841))
* add licence ([965375d](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/965375d3dfb05dc100df963fe9fdafd60ec0c91c))
* add more CSS custom properties; ([9ebf84c](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/9ebf84cec603b6dde6e9df6fbb1e00a898a3df2a))
* add outer borders; ([e52a1a8](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/e52a1a843aa138e7d9ade29aee4be651a3655a8b))
* add rubber band effect; ([42f8d1d](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/42f8d1d5b03a30f9d04c1cf48e261acdac542bfc))
* add teleportTo and teleportDefer props; ([a656ea6](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/a656ea6db94080d370db85d9ed48649a89f93a16))
* adding easing to the animation and set duration to 300; ([3a036f0](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/3a036f07b2b6130fed64e5d7329e19769e776ff3))
* allow expandOnContentDrag to change dynamically; ([4f692c2](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/4f692c2b226ed4b627ed5e79a7de4db06d64851a))
* allow user to interrupt animation; ([be5612f](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/be5612fef6244ac000d915c53744060e56e0d573))
* duration can be changed; ([89d4269](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/89d42692ed5b18a26edc0168f2c2befc04444dea))
* enhance scroll prevention logic; ([f8d9084](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/f8d9084b65abee24268becac677f1debb786f070))
* expandOnContentDrag option; ([5a670fb](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/5a670fbac898f6c5d3c84e7fdd24bc1108122d1d))
* extracting span points logic to useSnapPoints composable; ([49f93cb](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/49f93cb2aba10df8ba5eb221134456fec0ad0f3b))
* focus trap and non-blocking mode; ([cd88cc8](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/cd88cc8c1490e8db0b585abed124c48d342d19b7))
* improve drag interspersion; ([988bef5](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/988bef5367b7eb6c3154332f52170be6beb20976))
* improve snapping instinct height adaptation; ([2d147ec](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/2d147eccaf3fee8efd4d5dd326dede38c7b6fad8))
* lock window scroll during drag events in BottomSheet component ([cdc6eda](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/cdc6edab7cefbf9f5c576b558dc027981816b32f))
* move sheet into a separate component; ([e94c123](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/e94c1231837e322b316f301477535d283cf04ff5))
* prevent scroll during drag on header and footer; ([d17434e](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/d17434ec0c7ea83253030ec19eaf6f3bccbfc8b2))
* **snap:** added snapped emit event ([c387e95](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/c387e954141e1a1cd822dfb16283d21ec6815001))
* snapToPoint exposed; ([adb05f2](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/adb05f2d06eef79d7cf49d90d6d3c89103f2b890))
* snapToPoint method accepts snapPoint instead of index ; ([f86d491](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/f86d49184327413fdd67cd33c07e53099af5239a))
* update playground with working component ([a540718](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/a540718da17269cc03cb7c88a0390f8a4fd4515b))
* using emit instead of v-model for passing variables to parent; ([8b5c50f](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/8b5c50f08ac798d37ae37ef7c9e5b6f18e5b19a4))
* using height and transforms for dragging; ([7416340](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/7416340264ca8b50a145311f0ab5333470956cc9))
* window resize handling; ([4ca0a73](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/4ca0a735f805c0aeb6edeb74471584b52023c72b))
* window scroll lock; ([da57b68](https://github.com/Vladislav2397/vue-spring-bottom-sheet/commit/da57b68bb8bc92130ac671fbe2ca66b2c98b5182))

# [2.3.0](https://github.com/megaarmos/vue-spring-bottom-sheet/compare/v2.2.2...v2.3.0) (2025-05-19)


### Features

* add customizable header, content, and footer classes https://github.com/megaarmos/vue-spring-bottom-sheet/issues/20 ([fbb7b30](https://github.com/megaarmos/vue-spring-bottom-sheet/commit/fbb7b301774803e51edfdce45a09cba3789bcea2))

## [2.2.2](https://github.com/megaarmos/vue-spring-bottom-sheet/compare/v2.2.1...v2.2.2) (2025-05-18)


### Bug Fixes

* https://github.com/megaarmos/vue-spring-bottom-sheet/issues/22 ([4cbbbcf](https://github.com/megaarmos/vue-spring-bottom-sheet/commit/4cbbbcf5bf392b11e4752b14230c265063445ae8))

## [2.2.1](https://github.com/megaarmos/vue-spring-bottom-sheet/compare/v2.2.0...v2.2.1) (2025-05-18)


### Bug Fixes

* update build step to change directory before running prepublishOnly ([08daeae](https://github.com/megaarmos/vue-spring-bottom-sheet/commit/08daeae87171170f9b7cc1bb80cc28b61ffff8b3))
* update npm ci command to remove workspace specification ([95d69d6](https://github.com/megaarmos/vue-spring-bottom-sheet/commit/95d69d6b6d677335493eb109900b611af5780e44))
