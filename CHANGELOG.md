# Changelog

## 1.0.0 (2023-06-27)


### ⚠ BREAKING CHANGES

* selecting multiple files only opens buffers, not windows ([#111](https://github.com/stevearc/oil.nvim/issues/111))
* make oil buffers unlisted by default ([#45](https://github.com/stevearc/oil.nvim/issues/45))
* change scp:// urls back to oil-ssh://

### Features

* action to copy path to entry under cursor ([#50](https://github.com/stevearc/oil.nvim/issues/50)) ([6581d76](https://github.com/stevearc/oil.nvim/commit/6581d76a74760be5fcc5ca562d5032dcba7e5d9a))
* action to open entry in new tab ([#52](https://github.com/stevearc/oil.nvim/issues/52)) ([48eec8b](https://github.com/stevearc/oil.nvim/commit/48eec8b7ef67a5d7a50869fedf0ebbc82a8183d7))
* action to open the cmdline with current entry as argument ([#38](https://github.com/stevearc/oil.nvim/issues/38)) ([75b710e](https://github.com/stevearc/oil.nvim/commit/75b710e311104bc51eb5d04d1ac5db5193f7e834))
* add `setup.view_options.is_excluded` ([19ab948](https://github.com/stevearc/oil.nvim/commit/19ab948e25825a1b8823a391b733cc461f3010f7))
* add action to open a terminal ([c6a2e3e](https://github.com/stevearc/oil.nvim/commit/c6a2e3e08f1f70e52bbfff2b52093c779b4f24ed))
* add bug_report template ([23d1ca7](https://github.com/stevearc/oil.nvim/commit/23d1ca7327413973bbf7aee09e9f25b6f887f370))
* add override config option to customize float layout ([#132](https://github.com/stevearc/oil.nvim/issues/132)) ([ac72a8d](https://github.com/stevearc/oil.nvim/commit/ac72a8df4afc1a543624c0eb1ebc0bedeb83c1a6))
* add toggle_float function ([#94](https://github.com/stevearc/oil.nvim/issues/94)) ([82c7068](https://github.com/stevearc/oil.nvim/commit/82c706822bb13a8ea7a21e0e3dccc83eaf40bfbc))
* added command ([af59e7b](https://github.com/stevearc/oil.nvim/commit/af59e7b53df66192d18170e56f018cbc736dd67f))
* API to change config.view.is_hidden_file at runtime ([#69](https://github.com/stevearc/oil.nvim/issues/69)) ([12bea0f](https://github.com/stevearc/oil.nvim/commit/12bea0f6466661b89a6293c090a415ad7a32d4c8))
* builtin support for editing files over ssh ([#27](https://github.com/stevearc/oil.nvim/issues/27)) ([ca4da68](https://github.com/stevearc/oil.nvim/commit/ca4da68aaebaebf5cd68151c2b5ad56e00c06126))
* can cancel out of progress window ([273c2ce](https://github.com/stevearc/oil.nvim/commit/273c2cecbfe3ddc9fc19446f59cc6e7ff8981cf2))
* can minimize the progress window ([f28e634](https://github.com/stevearc/oil.nvim/commit/f28e63460ae23d88ecca8ba7bb4201b682692bee))
* **columns:** Add compatibility with previous versions ([98a186e](https://github.com/stevearc/oil.nvim/commit/98a186e8f9bd12621f988e95e8dbc4c67f0f3167))
* **columns:** Change to use custom icons ([6dc65dc](https://github.com/stevearc/oil.nvim/commit/6dc65dcf83dbd68a031d848dde61d104e6209b0c))
* config for floating preview window ([#74](https://github.com/stevearc/oil.nvim/issues/74)) ([3e1affa](https://github.com/stevearc/oil.nvim/commit/3e1affa6c784ce6911895a63232fa6e1a6ff5b70))
* config function to define which files are hidden ([#58](https://github.com/stevearc/oil.nvim/issues/58)) ([e5acff1](https://github.com/stevearc/oil.nvim/commit/e5acff1b77ff4372c94ace7daec21f93810166f7))
* config option for trashing deleted files ([#99](https://github.com/stevearc/oil.nvim/issues/99)) ([496d60f](https://github.com/stevearc/oil.nvim/commit/496d60fcff7af652e67c217aa82ab8d219a3f54e))
* config option to disable directory hijacking ([#76](https://github.com/stevearc/oil.nvim/issues/76)) ([3d3df74](https://github.com/stevearc/oil.nvim/commit/3d3df74532eaea2b071da03079c3a4c8e4fe5aeb))
* config option to skip the disclaimer ([adff3b9](https://github.com/stevearc/oil.nvim/commit/adff3b91541cde52793e41b34338f1f9cc19b3a6))
* **config:** Add custom icons ([bf20bca](https://github.com/stevearc/oil.nvim/commit/bf20bca78ddae7fd98ba98046014f3b06c8352ce))
* **config:** Change custom icons to columns config ([cb54e03](https://github.com/stevearc/oil.nvim/commit/cb54e034905ea67c7dd20008952203f0f7b4ed08))
* convert oil://path/to/file.lua to normal file path ([#77](https://github.com/stevearc/oil.nvim/issues/77)) ([d7805c7](https://github.com/stevearc/oil.nvim/commit/d7805c77515082d9e287feb010b3132dde838b3d))
* dispatch autocmd when oil buffer finishes rendering ([3ac035e](https://github.com/stevearc/oil.nvim/commit/3ac035e5ac448ce898c9aad7158a47378be4e85a))
* display shortened path as title of floating window ([#12](https://github.com/stevearc/oil.nvim/issues/12)) ([9f7c4d7](https://github.com/stevearc/oil.nvim/commit/9f7c4d74e1fefc7d88ff5094027b447eadecd787))
* expose buf_options in config ([#28](https://github.com/stevearc/oil.nvim/issues/28)) ([997d9cd](https://github.com/stevearc/oil.nvim/commit/997d9cd78a512d940e3a329e2746d20d77285189))
* extension for resession.nvim ([2bca582](https://github.com/stevearc/oil.nvim/commit/2bca582d935b723e67a41ec8c2d00684a3d1fc8a))
* first draft ([fefd6ad](https://github.com/stevearc/oil.nvim/commit/fefd6ad5e48ff5fcd04fa76d1410a65c40376964))
* inform user how to disable netrw ([6b10a36](https://github.com/stevearc/oil.nvim/commit/6b10a366414578022165fb1e2effea6362bf8ced))
* more actions for interacting with preview window ([#41](https://github.com/stevearc/oil.nvim/issues/41)) ([b3c4ff3](https://github.com/stevearc/oil.nvim/commit/b3c4ff340bed8bb88dc87f054334d67e47aae492))
* new action open_cmdline_dir ([#44](https://github.com/stevearc/oil.nvim/issues/44)) ([6c4a3da](https://github.com/stevearc/oil.nvim/commit/6c4a3dafcadec5f6818135e11c27250a9bdcbbff))
* Oil command supports split and vert modifiers ([#116](https://github.com/stevearc/oil.nvim/issues/116)) ([f322209](https://github.com/stevearc/oil.nvim/commit/f322209a4a2b4685adeda5df00b29cdfd64db08e))
* oil.select can close oil buffer afterwards ([#121](https://github.com/stevearc/oil.nvim/issues/121)) ([a465123](https://github.com/stevearc/oil.nvim/commit/a4651236594cd7717c9b75c43ede0ed5fd4a7dc9))
* option to disable all default keymaps ([#16](https://github.com/stevearc/oil.nvim/issues/16)) ([28da68a](https://github.com/stevearc/oil.nvim/commit/28da68ac5ca451a1f882ecc1eb720295e8c8fd51))
* prompt user to save changes before editing moved file/dir ([#93](https://github.com/stevearc/oil.nvim/issues/93)) ([6b05c2e](https://github.com/stevearc/oil.nvim/commit/6b05c2e91378960be7f7e73867112cee0b4a408a))
* restore window view in oil.close() ([#65](https://github.com/stevearc/oil.nvim/issues/65)) ([33ee724](https://github.com/stevearc/oil.nvim/commit/33ee724c2d25358917147718c3b108a90b571e20))
* set filetype='oil_preview' for preview buffer ([a587977](https://github.com/stevearc/oil.nvim/commit/a587977edda67fd6f506da11e55e3c27727df646))
* sort symbolic directory links like directories ([98fcc2d](https://github.com/stevearc/oil.nvim/commit/98fcc2d0d77f16941d5aac2e0dcf4cffd3cf699a))
* support custom trash commands ([#110](https://github.com/stevearc/oil.nvim/issues/110)) ([f535c10](https://github.com/stevearc/oil.nvim/commit/f535c1057c8d7ce2865bfff1881cc99aa726a044))
* update preview window when cursor is moved ([#42](https://github.com/stevearc/oil.nvim/issues/42)) ([6c6b767](https://github.com/stevearc/oil.nvim/commit/6c6b7673af1314dd7c8254a95eb8d331f6b76ac6))
* Use &lt;C-l&gt; to refresh directory ([#7](https://github.com/stevearc/oil.nvim/issues/7)) ([d019d38](https://github.com/stevearc/oil.nvim/commit/d019d38a3ef4926308735a00bd919a5666c464b6))


### Bug Fixes

* add autocmd to augroup ([5e2f1ce](https://github.com/stevearc/oil.nvim/commit/5e2f1ced9fae1b1dfec45f11f42d49ac9e299bc2))
* add WinLeave autocmd to augroup ([6a227e9](https://github.com/stevearc/oil.nvim/commit/6a227e932fb5e5cac9d4c0fef2a500cac047e99e))
* allow calling oil.open() with a url ([be695dc](https://github.com/stevearc/oil.nvim/commit/be695dc3502f8fb052a83720f3a4dd9578cacdf0))
* alternate buffer preservation ([#43](https://github.com/stevearc/oil.nvim/issues/43)) ([4e853ea](https://github.com/stevearc/oil.nvim/commit/4e853eabcb002650096ef78f098253fe12ba3d8f))
* always close keymap help window ([#17](https://github.com/stevearc/oil.nvim/issues/17)) ([7b703b4](https://github.com/stevearc/oil.nvim/commit/7b703b42da815fb280c6fd7b73961c2e87bcff07))
* always enter directory entries as a directory ([0d5db08](https://github.com/stevearc/oil.nvim/commit/0d5db08015d41a0e3da727bf70796f3a4abcfa76))
* another case of incorrect alternate buffers ([#60](https://github.com/stevearc/oil.nvim/issues/60)) ([b36ba91](https://github.com/stevearc/oil.nvim/commit/b36ba91b7a4d05ee43617383f68cf6ed6fc2f08e))
* bad interaction with editorconfig-vim ([7371dd2](https://github.com/stevearc/oil.nvim/commit/7371dd220f1d08789cc225846d8cafed938777e9))
* better behaved lazy loading in autocmds ([7f17648](https://github.com/stevearc/oil.nvim/commit/7f176487052a155d43c6b64ef44b6dd775e94f99))
* block quit if changes during :wq ([#98](https://github.com/stevearc/oil.nvim/issues/98)) ([37cb6be](https://github.com/stevearc/oil.nvim/commit/37cb6be6f6f98c4616ca382ad955c709dc38f39d))
* bug when copying saved win options to split ([#89](https://github.com/stevearc/oil.nvim/issues/89)) ([caa65e5](https://github.com/stevearc/oil.nvim/commit/caa65e5bfcc98a1450f6a5659fe0f4d28a311967))
* catch errors opening preview window ([#113](https://github.com/stevearc/oil.nvim/issues/113)) ([64d2f30](https://github.com/stevearc/oil.nvim/commit/64d2f305d30cec13938aa99f8f13bd84c502e020))
* close floating oil window on WinLeave ([#17](https://github.com/stevearc/oil.nvim/issues/17)) ([0f10485](https://github.com/stevearc/oil.nvim/commit/0f104854dab0b9edc9dd90bb70fdd782568283ef))
* copying symlinks ([dc18d06](https://github.com/stevearc/oil.nvim/commit/dc18d06bcbf02d84ed48cfa250582c0bb7aa6a02))
* detect duplicate filenames in buffer ([bcb99ae](https://github.com/stevearc/oil.nvim/commit/bcb99ae95a349d33dac9ea54dff0f8915e567eec))
* don't close floating windows we didn't open ([#64](https://github.com/stevearc/oil.nvim/issues/64)) ([073ecb3](https://github.com/stevearc/oil.nvim/commit/073ecb3d68580cd131cd30d83163576807172a77))
* don't show preview if there are no changes ([#19](https://github.com/stevearc/oil.nvim/issues/19)) ([6d0b6ac](https://github.com/stevearc/oil.nvim/commit/6d0b6ac43ce368e5d7aca1798339b597ef6c9981))
* double callback in mutator ([0046508](https://github.com/stevearc/oil.nvim/commit/00465089cb4fdf2c9fb491cd63e36ca135ac6291))
* edge case where cursor position was not set ([#37](https://github.com/stevearc/oil.nvim/issues/37)) ([64d7763](https://github.com/stevearc/oil.nvim/commit/64d7763ac69c581bf1c28492994567c05ddff28a))
* edge case where opening a file would delete its contents ([2e95b9d](https://github.com/stevearc/oil.nvim/commit/2e95b9d42467168185cc5a505ef4288de4c5670f))
* edge case where window options were not set ([b8eaf88](https://github.com/stevearc/oil.nvim/commit/b8eaf88c127b7807fa3a8b00be881ab94f5168b3))
* error messages opening terminal in dir ([90acbdb](https://github.com/stevearc/oil.nvim/commit/90acbdbbffcb461bc6de3544bf8b695f7abeb168))
* error when editing a dir, and still missing parent window ([#40](https://github.com/stevearc/oil.nvim/issues/40)) ([a688443](https://github.com/stevearc/oil.nvim/commit/a6884431b0d7adccf9f4756ca543bf175052f742))
* error when float border is 'none' ([#125](https://github.com/stevearc/oil.nvim/issues/125)) ([4ad1627](https://github.com/stevearc/oil.nvim/commit/4ad162756b800fee4542726b48e98125fb5d7913))
* Error when saving blank lines and quitting. ([2bc63f7](https://github.com/stevearc/oil.nvim/commit/2bc63f7059050f6b172be6aea0402e8b177bde58))
* error when use_default_keymaps = false ([#56](https://github.com/stevearc/oil.nvim/issues/56)) ([f1ea6e0](https://github.com/stevearc/oil.nvim/commit/f1ea6e0ad03e1d7b1acad4d0796d39c4a82b3463))
* escape special characters when editing buffer ([#96](https://github.com/stevearc/oil.nvim/issues/96)) ([339ade9](https://github.com/stevearc/oil.nvim/commit/339ade9dc387958c714a98741cda9e722a931410))
* expand terminal path ([20e4ff1](https://github.com/stevearc/oil.nvim/commit/20e4ff1838d384141f6252520ae572a63abff2cd))
* float positioning and width calculation ([#32](https://github.com/stevearc/oil.nvim/issues/32)) ([f8ca564](https://github.com/stevearc/oil.nvim/commit/f8ca5648021ac6a59e016d81be594fa98f0705c2))
* guard against invalid buffer ([#90](https://github.com/stevearc/oil.nvim/issues/90)) ([a9556aa](https://github.com/stevearc/oil.nvim/commit/a9556aa872215f5956062f24064ade55cf2baeb9))
* icon column does nil-check of config ([f6d2102](https://github.com/stevearc/oil.nvim/commit/f6d2102e2b671ffe28029c0b4b0915e625c3f09f))
* ignore errors when unlocking buffers ([e58f347](https://github.com/stevearc/oil.nvim/commit/e58f347c674332d2ece6a0ff6da05cf93bf0f0b9))
* invalid filetype of oil buffer ([#47](https://github.com/stevearc/oil.nvim/issues/47)) ([2b0b938](https://github.com/stevearc/oil.nvim/commit/2b0b9382d77c4a9ff471a999bddb2f9cc945a300))
* more detailed information when ssh connection fails ([#27](https://github.com/stevearc/oil.nvim/issues/27)) ([f5961e7](https://github.com/stevearc/oil.nvim/commit/f5961e731f641206727eaded197e5879694c35f7))
* new oil buffers are nomodifiable during mutation processing ([d631d9f](https://github.com/stevearc/oil.nvim/commit/d631d9fc5a958c7c9ee0717b1fe040a3ec951c63))
* no error if opening file that has swapfile ([a60639d](https://github.com/stevearc/oil.nvim/commit/a60639db358c0b40f9fe297b1f52f3eb62c190c6))
* off-by-one errors in tests ([6062ad6](https://github.com/stevearc/oil.nvim/commit/6062ad6737d36e8a1cc10696cf5e870057eba20c))
* oil buffers load properly after loading a session ([#29](https://github.com/stevearc/oil.nvim/issues/29)) ([bb5201c](https://github.com/stevearc/oil.nvim/commit/bb5201c9cd422e7b145699b5dccd8e70e4630a9d))
* oil buffers remain unmodified after saving changes ([931453f](https://github.com/stevearc/oil.nvim/commit/931453fc09085c09537295c991c66637869e97e1))
* oil can open when terminal is focused ([#51](https://github.com/stevearc/oil.nvim/issues/51)) ([0e53d40](https://github.com/stevearc/oil.nvim/commit/0e53d402219c74d351fffb18d97d7e350f87bfd8))
* oil loses track of buffers after refresh ([9871ca9](https://github.com/stevearc/oil.nvim/commit/9871ca9737d4ffd68b40ad68b8f89848d835b286))
* oil-ssh assume target machine's locales ([c72bcb4](https://github.com/stevearc/oil.nvim/commit/c72bcb45b2e824150cbf356c2e13e37d6863369b))
* oil.close doesn't error when no other buffers exist ([#79](https://github.com/stevearc/oil.nvim/issues/79)) ([4b05ebd](https://github.com/stevearc/oil.nvim/commit/4b05ebdf202bf61ce240f40558822fe5564d02ea))
* oil.close() sometimes closes window too ([#64](https://github.com/stevearc/oil.nvim/issues/64)) ([d48fa09](https://github.com/stevearc/oil.nvim/commit/d48fa09c82b133d384c84c98725b722fd06f38af))
* opening with lowercase drive letters ([29808f2](https://github.com/stevearc/oil.nvim/commit/29808f273c817543d049f6d2541a550e233de4ff))
* preserve alternate buffer when using floating window ([#20](https://github.com/stevearc/oil.nvim/issues/20)) ([d8a1e7c](https://github.com/stevearc/oil.nvim/commit/d8a1e7ca4e599c43dda1849a66b19d9fbff12310))
* preserve the alternate buffer ([#20](https://github.com/stevearc/oil.nvim/issues/20)) ([e4c4110](https://github.com/stevearc/oil.nvim/commit/e4c411002272d6eed159afdf4cae2e74dc7fc813))
* prevent double-delete autocmd ids ([#97](https://github.com/stevearc/oil.nvim/issues/97)) ([4107784](https://github.com/stevearc/oil.nvim/commit/41077847b98d6d3b88b6d31864bb20a664e88574))
* preview window renders on top of floating window title ([#72](https://github.com/stevearc/oil.nvim/issues/72)) ([383971b](https://github.com/stevearc/oil.nvim/commit/383971b0cfd8248ec3d00d4a3154d69ebd5e394e))
* renaming buffers doesn't interfere with directory hijack ([#25](https://github.com/stevearc/oil.nvim/issues/25)) ([b4ccc16](https://github.com/stevearc/oil.nvim/commit/b4ccc16944a3678558ab8f73fa803409b38f58d6))
* reposition preview window if vim is resized ([8cbb104](https://github.com/stevearc/oil.nvim/commit/8cbb104e76efee35ca8125da8d441c395e568e23))
* reposition progress window if vim is resized ([092f4b1](https://github.com/stevearc/oil.nvim/commit/092f4b1c7c14633cd58659dc93eed92c5c26810c))
* restore modified state of current buffer if actions are canceled ([#6](https://github.com/stevearc/oil.nvim/issues/6)) ([2e6d684](https://github.com/stevearc/oil.nvim/commit/2e6d68453f98d3d69cd5c36577f7a381aa7399f3))
* restore window options on split windows ([#36](https://github.com/stevearc/oil.nvim/issues/36)) ([fb69775](https://github.com/stevearc/oil.nvim/commit/fb697752b28ecc41ecaab4206b41e61496ab87f2))
* selecting multiple files only opens buffers, not windows ([#111](https://github.com/stevearc/oil.nvim/issues/111)) ([393f0dc](https://github.com/stevearc/oil.nvim/commit/393f0dcf82f04de597e194ec120d8cbe6fe212a8))
* set alternate buffer when inside oil ([#60](https://github.com/stevearc/oil.nvim/issues/60)) ([f1131b5](https://github.com/stevearc/oil.nvim/commit/f1131b5e90ce5cdbbd122e298d62726dfa4b808a))
* set bufhidden = 'hide' by default ([#104](https://github.com/stevearc/oil.nvim/issues/104)) ([19563c3](https://github.com/stevearc/oil.nvim/commit/19563c365800ab519e46a08a0aa59d5677b329b6))
* shortened path for current directory is '.' ([7649866](https://github.com/stevearc/oil.nvim/commit/76498666500c2aee94fd07366222d76c4d13ee2f))
* silence doautocmd errors ([9dbf18a](https://github.com/stevearc/oil.nvim/commit/9dbf18a524df1a563b2a8f46b14645aa47022f9e))
* some autocmds skipped when opening files from oil ([#120](https://github.com/stevearc/oil.nvim/issues/120)) ([61f8655](https://github.com/stevearc/oil.nvim/commit/61f8655e03dea805bb77aad5b4ca99d1176510b7))
* ssh adapter handles character and block files ([aa68ec4](https://github.com/stevearc/oil.nvim/commit/aa68ec4d988be3c898341f65f54c1620986240dd))
* stop using vim.wo to set window options ([6f8bf06](https://github.com/stevearc/oil.nvim/commit/6f8bf067c09e96d6bff548b5e6addb6d9c25a678))
* symbolic link target parsing fails if it has a trailing slash ([#131](https://github.com/stevearc/oil.nvim/issues/131)) ([9be36a6](https://github.com/stevearc/oil.nvim/commit/9be36a648889c37d11bc65e8422049dc33dd6a3f))
* unexpected behavior from BufReadPost autocmds ([716dd8f](https://github.com/stevearc/oil.nvim/commit/716dd8f9cf1ff2b9cda03497025612ce3c366307))
* unlock buffers if we cancel the actions ([#4](https://github.com/stevearc/oil.nvim/issues/4)) ([0d6ee14](https://github.com/stevearc/oil.nvim/commit/0d6ee144d210b8627e9c3fd98dc32ec3e9360aa2))
* update preview window in-place ([#74](https://github.com/stevearc/oil.nvim/issues/74)) ([57451c5](https://github.com/stevearc/oil.nvim/commit/57451c517d96ad856ed418203729f5d3cb200de6))
* url formatting errors when ssh connection specifies port ([9a03af7](https://github.com/stevearc/oil.nvim/commit/9a03af7cb752f46b9efa85fc132d9281f5672f23))
* warning when :tabnew from oil buffer ([#40](https://github.com/stevearc/oil.nvim/issues/40)) ([73c6fcf](https://github.com/stevearc/oil.nvim/commit/73c6fcf519afbd99b8cef00d8663bed20f87a1df))


### Code Refactoring

* change scp:// urls back to oil-ssh:// ([3164537](https://github.com/stevearc/oil.nvim/commit/31645370a105e59270634ec14665149e919f7432))
* make oil buffers unlisted by default ([#45](https://github.com/stevearc/oil.nvim/issues/45)) ([1d54819](https://github.com/stevearc/oil.nvim/commit/1d548190cf4a032d0354c0bf84d042a618152769))
