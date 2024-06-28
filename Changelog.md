# Changelog

## Version v2.0.12 (2024-06-28)

### Security Fixes

- Update go-dependency to fix security issue (bab37a57)

### Fixes

- fix dockerfile (471347ca)
- Fix broken graphviz font rendering, switch to ttf-freefont (#22) (ad79c07a)
- typo and missing import: no click events anymore (a5f1e159)
- root group has been added twice. (b565ceb9)
- Fix nil pointer on missing dependency and output cyclic dependencies (863fec04)

### Tests

- test again (5f12a7fc)
- test (87b164b2)
- test without npm shizzle (28f5aaab)

### Ops and CI/CD

- **semanticore:** add semanticore (998caa9b)

### Chores and tidying

- fix leading v in docker image tag (eb0f8472)
- try macos (1a24c1cf)
- test build (cc18d860)
- fix failing parcel build for ARM images (e3cfee0f)
- fix ref name for image tag (f5e670eb)
- add build steps for ARM architecture (#42) (04c255ff)
- **frontend:** Update parcel to 2.7.0 (#40) (0f5680e1)
- bump nancy from 1.0.1 to main (#39) (91bb8cc3)
- **deps:** minor dependency updates (#34) (f6e58d6f)
- bump npm-audit-action from 1.7.1 to 2.3.0 (#35) (d9b9d153)
- Update Readme.md (ee01f6aa)
- Update Readme.md (f8f9c6c4)
- update version (5d4acf95)

### Other

- readd docker login (5d430dbd)
- try another context (cf26fc59)
- show files (cef7c38f)
- use arsch as arg (406bb408)
- try another way (5fd5eaea)
- use latest and greatest (364736ab)
- yolo (b192f7da)
- ¯\_(ツ)_/¯ (0250dacd)
- adds display of unincluded(outside) apps that are linked through provided service dependencies when view is filtered (9c03f931)
- Bump elliptic from 6.5.3 to 6.5.4 in /controller/web/template (f38031f2)
- Bump color-string from 1.5.4 to 1.6.0 in /controller/web/template (472be1e6)
- Bump browserslist from 4.16.1 to 4.17.3 in /controller/web/template (ed163c3f)
- Bump lodash from 4.17.20 to 4.17.21 in /controller/web/template (e557f8ab)
- Bump path-parse from 1.0.6 to 1.0.7 in /controller/web/template (60e48718)
- Bump ws from 5.2.2 to 5.2.3 in /controller/web/template (23d435eb)
- Clean up dependencies, replace packr with go.embed (go 1.16+), update urfave/cli to the latest version (#23) (05718b85)
- remove formatting (6e6e79dd)
- Added popper.js and formatted code (d3214e32)
- #17 - Add team to Common pane (9faaf85e)
- #17 - Add Group and Team to title (c6ff32dd)
- Add Markdown parser to Project / Service Description + Field Dependency.Events (#11) (56a91c94)
- TASK: Automatic Release creation by tag pushes (985b13cf)
- TASK: Create security scanning workflow (fbc07d1d)
- TASK: Add github actions (9f5111ee)
- CLEANUP: minor strict comparison fixes in JS (b9030251)
- TASK: adapt demo data (03e7b2d6)
- CLEANUP: remove Travis (de6fdabf)
- CLEANUP: typo (f9ff2c05)
- CLEANUP: Rename method and add description (f78b9045)
- Publish 2.5.0 (072953a4)
- Publish 2.1.0 with go 1.15, updated dependencies and up-to-date alpine base image (2ff62daa)
- Add packed files to support go get installs better (94ab21ae)

