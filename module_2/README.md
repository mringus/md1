Abiem failiem is.jpeg hash ir 5905dc289107eb1ec70bc666ccbe1681ad1f18f1

16.v1
Fri Apr 15 14:40:01 2022 -0600 - Brandon Croft: Merge pull request #30878 from hashicorp/brandonc/periods_env_creds
Fri Apr 15 11:19:46 2022 -0600 - Brandon Croft: fix(creds): allow periods in TF_TOKEN_... credentials vars
Fri Apr 15 08:41:49 2022 -0700 - Martin Atkins: Update CHANGELOG.md
Wed Apr 13 14:52:08 2022 -0600 - Brandon Croft: Update CHANGELOG.md
Thu Apr 14 13:33:41 2022 -0400 - Sebastian Rivera: Minor changelog modifications
Thu Apr 14 12:04:35 2022 -0400 - Kevin Wang: chore: move content into `docs` (#30837)
Thu Apr 14 16:39:36 2022 +0100 - Radek Simko: Update CHANGELOG.md
Thu Apr 14 09:31:49 2022 -0600 - Brandon Croft: Merge pull request #30850 from hashicorp/brandonc/cloud_test_revisions
Thu Apr 14 16:14:50 2022 +0100 - Radek Simko: internal/getproviders: Add URL to error message for clarity (#30810)
Thu Apr 14 10:39:56 2022 -0400 - Laura Pacilio: Merge pull request #30865 from sdinay/patch-1
Thu Apr 14 09:47:25 2022 -0400 - James Bardin: Merge pull request #30832 from hashicorp/jbardin/data-readResourceInstanceState
Thu Apr 14 09:46:59 2022 -0400 - James Bardin: Merge pull request #30830 from hashicorp/jbardin/data-schema-change
Wed Apr 13 16:13:20 2022 -0700 - Shanee D: fix: Fix typo in v1.0 upgrade guide
Wed Apr 13 17:07:20 2022 -0400 - Sebastian Rivera: Merge pull request #30836 from hashicorp/sebasslash/env-cloud-e2e-tests
Wed Apr 13 16:39:28 2022 -0400 - Laura Pacilio: Clarify that users can set TF_WORKSPACE and use tags
Wed Apr 13 14:35:12 2022 -0600 - Brandon Croft: Merge pull request #30797 from hashicorp/brandonc/env_credentials
Wed Apr 13 14:06:25 2022 -0600 - Brandon Croft: Update credentials_test.go
Wed Apr 13 13:48:17 2022 -0600 - Brandon Croft: Apply suggestions from documentation review
Tue Apr 12 17:34:22 2022 -0600 - Brandon Croft: feat(credentials): allow hyphens to be encoded as __ in variables
Tue Apr 5 13:23:46 2022 -0600 - Brandon Croft: Apply doc suggestions from code review
Mon Apr 4 17:43:34 2022 -0600 - Brandon Croft: allow remote service creds to be configured using env
Wed Apr 13 15:40:49 2022 -0400 - Alisdair McDiarmid: Merge pull request #30855 from hashicorp/alisdair/fix-diff-map-key-quoting
Wed Apr 13 18:30:46 2022 +0000 - hc-github-team-tf-core: Cleanup after v1.2.0-alpha20220413 release
Wed Apr 13 18:14:12 2022 +0000 - hc-github-team-tf-core: Release v1.2.0-alpha20220413
Wed Apr 13 09:27:13 2022 -0600 - Brandon Croft: test(cloud): nonexisting org not a valid test when using mocks
Tue Apr 12 13:14:01 2022 -0600 - Brandon Croft: test(cloud): ensure mocks are used for backend configure tests
Wed Apr 13 09:10:00 2022 -0400 - Alisdair McDiarmid: cli: Fix double-quoted map keys in diff UI
Tue Apr 12 17:32:39 2022 -0400 - Sebastian Rivera: Add skip test if missing vars helper
Tue Apr 12 12:19:28 2022 -0400 - Kevin Wang: chore: vercel config (#30831)
Mon Apr 4 15:37:44 2022 -0400 - Sebastian Rivera: Cloud e2e tests for configuring with env vars
Mon Apr 11 14:38:23 2022 -0400 - Sebastian Rivera: Merge pull request #30787 from hashicorp/sebasslash/tf-workspace-cloud-config
Mon Apr 11 14:33:13 2022 -0400 - Sebastian Rivera: Update website/docs/cli/cloud/settings.mdx
Mon Apr 11 13:55:19 2022 -0400 - Sebastian Rivera: Update docs to explain new TF_WORKSPACE behavior for cloud config
Tue Apr 5 18:27:39 2022 -0400 - Sebastian Rivera: Add TF_WORKSPACE validation method
v2

commit 173e21a0e27dfec9615ac2cfc694dd5cc6365177
Merge: 3a7263990 1943af51a
Author: Brandon Croft <brandon.croft@gmail.com>
Date:   Fri Apr 15 14:40:01 2022 -0600

    Merge pull request #30878 from hashicorp/brandonc/periods_env_creds
    
    fix(creds): allow periods in TF_TOKEN_... credentials vars

commit 1943af51a22c1453f032df5b5653e9382296ab06
Author: Brandon Croft <brandon.croft@gmail.com>
Date:   Fri Apr 15 11:19:46 2022 -0600

    fix(creds): allow periods in TF_TOKEN_... credentials vars

commit 3a7263990d283e5166e847389ea9d1929d9c8880
Author: Martin Atkins <mart@degeneration.co.uk>
Date:   Fri Apr 15 08:41:49 2022 -0700

    Update CHANGELOG.md

commit dc9940332537d56b4d620cab536f574983618333
Author: Brandon Croft <brandon.croft@gmail.com>
Date:   Wed Apr 13 14:52:08 2022 -0600

    Update CHANGELOG.md

commit ad15263cf74fa6481ffb9a8befe47ba69a4263c5
Author: Sebastian Rivera <sebastian.rivera@hashicorp.com>
Date:   Thu Apr 14 13:33:41 2022 -0400

    Minor changelog modifications
    
    Removed the run task entry since the feature will be backported to v1.1. I've also added the missing
    enhancement entry for using `TF_WORKSPACE` to configure your cloud block.

commit 545346b331baf84336498fc021b3cae50c3d36b7
Author: Kevin Wang <kwangsan@gmail.com>
Date:   Thu Apr 14 12:04:35 2022 -0400

    chore: move content into `docs` (#30837)

commit ad86e5a06f45425421145ec974d7106c0a143ed9
Author: Radek Simko <radek.simko@gmail.com>
Date:   Thu Apr 14 16:39:36 2022 +0100

    Update CHANGELOG.md

commit 42da0300908d7e8e9ba7e18243d59c972ca78779
Merge: 746af015e 0dc26a958
Author: Brandon Croft <brandon.croft@gmail.com>
Date:   Thu Apr 14 09:31:49 2022 -0600

    Merge pull request #30850 from hashicorp/brandonc/cloud_test_revisions
    
    test(cloud): ensure mocks are used for backend configure tests

commit 746af015ea34b44daa188ab82a139b508383928d
Author: Radek Simko <radek.simko@gmail.com>
Date:   Thu Apr 14 16:14:50 2022 +0100

    internal/getproviders: Add URL to error message for clarity (#30810)
    
    * internal/getproviders: Add URL to error message for clarity
    
    Occasionally `terraform init` on some providers may return the following error message:
    
    Error while installing citrix/citrixadc v1.13.0: could not query provider
    registry for registry.terraform.io/citrix/citrixadc: failed to retrieve
    authentication checksums for provider: 403 Forbidden
    
    The 403 is most often returned from GitHub (rather than Registry API)
    and this change makes it more obvious.
    
    * Use Host instead of full URL

commit 696bd4c794aeae99e2cc00ef625f50cb4f09f3d2
Merge: d360a7877 ed59bd729
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Apr 14 10:39:56 2022 -0400

    Merge pull request #30865 from sdinay/patch-1
    
    docs: Fix typo in v1.0 upgrade guide

commit d360a787717833f2e94f6a43fb531a9ac4f7dec0
Merge: f31dab483 74885b110
Author: James Bardin <j.bardin@gmail.com>
Date:   Thu Apr 14 09:47:25 2022 -0400

    Merge pull request #30832 from hashicorp/jbardin/data-readResourceInstanceState
    
    remove the use of data source prior state from planning

commit f31dab4838eba63bbb218854f221bd7770cb2458
Merge: 3ebd8c948 01628f0d5
Author: James Bardin <j.bardin@gmail.com>
Date:   Thu Apr 14 09:46:59 2022 -0400

    Merge pull request #30830 from hashicorp/jbardin/data-schema-change
    
    data schema changes may prevent state decoding

commit ed59bd7299d07f26973098b06a349a62c235eba5
Author: Shanee D <sdinay@gmail.com>
Date:   Wed Apr 13 16:13:20 2022 -0700

    fix: Fix typo in v1.0 upgrade guide

commit 3ebd8c94837c935f2888c8a745fe9a08107dc640
Merge: bb7f4f8b8 b191faf8a
Author: Sebastian Rivera <sebastian.rivera@hashicorp.com>
Date:   Wed Apr 13 17:07:20 2022 -0400

    Merge pull request #30836 from hashicorp/sebasslash/env-cloud-e2e-tests
    
    Cloud e2e tests for configuring `cloud` with env vars

commit 201c9168fa2939b224d1d1dc81de786d386fd89e
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 13 16:39:28 2022 -0400

    Clarify that users can set TF_WORKSPACE and use tags

commit bb7f4f8b8f42bcf18a59ed46e7c02e2fb9885153
Merge: 714740454 f04202d22
Author: Brandon Croft <brandon.croft@gmail.com>
Date:   Wed Apr 13 14:35:12 2022 -0600

    Merge pull request #30797 from hashicorp/brandonc/env_credentials
    
    Allow remote service creds to be configured using env

commit f04202d222b673caa7a8f3bf8e3d97a07802dedd
Author: Brandon Croft <brandon.croft@gmail.com>
Date:   Wed Apr 13 14:06:25 2022 -0600

    Update credentials_test.go

commit 8138fb7b292ad3a48bf3001458e495af9cc98826
Author: Brandon Croft <brandon.croft@gmail.com>
Date:   Wed Apr 13 13:48:17 2022 -0600

    Apply suggestions from documentation review
    
    Co-authored-by: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>

commit fda05f3d4453c461ba172f01ecabefea1c037da1
Author: Brandon Croft <brandon.croft@gmail.com>
Date:   Tue Apr 12 17:34:22 2022 -0600

    feat(credentials): allow hyphens to be encoded as __ in variables
    
    Hyphen characters are allowed in environment variable names, but are not valid POSIX variable names. Usually, it's still possible to set variable names with hyphens using utilities like env or docker. But, as a fallback, host names may encode their hyphens as double underscores in the variable name. For the example "café.fr", the variable name "TF_TOKEN_xn____caf__dma_fr" or "TF_TOKEN_xn--caf-dma_fr"
    may be used.

commit dff6a8431ce0d0e391dcb1352f16ba7964793cfb
Author: Brandon Croft <brandon.croft@gmail.com>
Date:   Tue Apr 5 13:23:46 2022 -0600

    Apply doc suggestions from code review
    
    Co-authored-by: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>

commit 307326fa3a8e5f1de2747f6ba1abd71f1ae08af6
Author: Brandon Croft <brandon.croft@gmail.com>
Date:   Mon Apr 4 17:43:34 2022 -0600

    allow remote service creds to be configured using env
    
    Introduces a new method of configuring token service credentials using a host-specific environment variable. This configuration was previously possible using the [terraform-credentials-env](https://github.com/apparentlymart/terraform-credentials-env) credentials helper.
    
    This new method is now consulted first, as it is seen to be the most proximate source of credentials before CLI configuration while still falling back to the credentials helper.

commit 714740454eaf504ff9b8110a9fa80cafcb6ee15f
Merge: 854654350 fadcaaaad
Author: Alisdair McDiarmid <alisdair@users.noreply.github.com>
Date:   Wed Apr 13 15:40:49 2022 -0400

    Merge pull request #30855 from hashicorp/alisdair/fix-diff-map-key-quoting
    
    cli: Fix double-quoted map keys in diff UI

commit 854654350946a4c764a4ac604a47958e6486acc0
Author: hc-github-team-tf-core <hc-github-team-tf-core@users.noreply.github.com>
Date:   Wed Apr 13 18:30:46 2022 +0000

    Cleanup after v1.2.0-alpha20220413 release

commit 7f84fd7308f8b1e9af09724d7ae48ce00c530a0c (tag: v1.2.0-alpha20220413)
Author: hc-github-team-tf-core <hc-github-team-tf-core@users.noreply.github.com>
Date:   Wed Apr 13 18:14:12 2022 +0000

    Release v1.2.0-alpha20220413

commit 0dc26a9585556dfbf86bc4769facb6cacf0f87f9
Author: Brandon Croft <brandon.croft@gmail.com>
Date:   Wed Apr 13 09:27:13 2022 -0600

    test(cloud): nonexisting org not a valid test when using mocks

commit a38a0ee8a8ca486037f326fa8e3e3c4c8b87532b
Author: Brandon Croft <brandon.croft@gmail.com>
Date:   Tue Apr 12 13:14:01 2022 -0600

    test(cloud): ensure mocks are used for backend configure tests
    
    Also adds a few new tests for cloud configuration using environment variables

commit fadcaaaad2e6c075a4427437fca80d315369c9af
Author: Alisdair McDiarmid <alisdair@users.noreply.github.com>
Date:   Wed Apr 13 09:10:00 2022 -0400

    cli: Fix double-quoted map keys in diff UI
    
    A previous change added missing quoting around object keys which do not
    parse as barewords. At the same time we introduced a bug where map keys
    could be double-quoted, due to calling the `displayAttributeName` helper
    function (to quote non-bareword keys) then using the `writeValue` method
    (which quotes all strings).
    
    This commit fixes this and adds test coverage for map keys which require
    quoting.

commit b191faf8a4b363336950a1ba1a0b04d5689296e9 (origin/sebasslash/env-cloud-e2e-tests)
Author: Sebastian Rivera <sebastian.rivera@hashicorp.com>
Date:   Tue Apr 12 17:32:39 2022 -0400

    Add skip test if missing vars helper

commit 8eaf7fe85e7242bf2e88b4d649d45ffdc6afa7aa
Author: Kevin Wang <kwangsan@gmail.com>
Date:   Tue Apr 12 12:19:28 2022 -0400

    chore: vercel config (#30831)
    
    - follows: https://github.com/hashicorp/terraform-cdk/pull/1611

commit 34114286ffed6ab5d312f05ea178907e72757e34
Author: Sebastian Rivera <sebastian.rivera@hashicorp.com>
Date:   Mon Apr 4 15:37:44 2022 -0400

    Cloud e2e tests for configuring with env vars

commit 8040dfec3467d9dca7561d944ff9642bd0699ff0
Merge: 51178958f f95c7935c
Author: Sebastian Rivera <sebastian.rivera@hashicorp.com>
Date:   Mon Apr 11 14:38:23 2022 -0400

    Merge pull request #30787 from hashicorp/sebasslash/tf-workspace-cloud-config
    
    Add cloud config support for TF_WORKSPACE

commit f95c7935c9706ff4a7c1b21e460f6491c7e210b6 (origin/sebasslash/tf-workspace-cloud-config)
Author: Sebastian Rivera <sebastian.rivera@hashicorp.com>
Date:   Mon Apr 11 14:33:13 2022 -0400

    Update website/docs/cli/cloud/settings.mdx
    
    Co-authored-by: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>

commit 4c3429f1a0335ef8226e56524f493ef458f82a5b
Author: Sebastian Rivera <sebastian.rivera@hashicorp.com>
Date:   Mon Apr 11 13:55:19 2022 -0400

    Update docs to explain new TF_WORKSPACE behavior for cloud config

commit dd864b1bace26f4387e0dd9a07bce86e83c7f1b1
Author: Sebastian Rivera <sebastian.rivera@hashicorp.com>
Date:   Tue Apr 5 18:27:39 2022 -0400

    Add TF_WORKSPACE validation method

commit 74885b1108090461879b0e0aeadb13dabafe0f46
Author: James Bardin <j.bardin@gmail.com>
Date:   Mon Apr 11 11:55:53 2022 -0400

    remove data sources from state read and upgrade
    
    Data sources should not require reading the previous versions. While we
    previously skipped the decoding if it were to fail, this removes the
    need for any prior state at all.
    
    The only place where the prior state was functionally used was in the
    destroy path. Because a data source destroy is only for cleanup purposes
    to clean out the state using the same code paths as a managed resource,
    we can substitute the prior state in the change change with a null value
    to maintain the same behavior.

commit 29ecac08084970842c2dd0016400aa7753c9f4d5
Author: James Bardin <j.bardin@gmail.com>
Date:   Mon Apr 11 10:19:45 2022 -0400

    remove the use of data source prior state entirely
    
    After data source handling was moved from a separate refresh phase into
    the planning phase, reading the existing state was only used for
    informational purposes. This had been reduced to reporting warnings when
    the provider returned an unexpected value to try and help locate legacy
    provider bugs, but any actual issues located from those warnings were
    very few and far between.
    
    Because the prior state cannot be reliably decoded when faced with
    incompatible provider schema upgrades, and there is no longer any
    significant reason to try and get the prior state at all, we can skip
    the process entirely.

commit a7987dec9fc75798283cae647ab1a92f26461c72
Author: James Bardin <j.bardin@gmail.com>
Date:   Mon Apr 11 10:12:35 2022 -0400

    remove redundant readResourceInstanceState

commit 01628f0d50361cc957f7d6b9e2ea48d098aa959f
Author: James Bardin <j.bardin@gmail.com>
Date:   Mon Apr 11 09:41:22 2022 -0400

    data schema changes may prevent state decoding
    
    Data sources do not have state migrations, so there may be no way to
    decode the prior state when faced with incompatible type changes.
    
    Because prior state is only informational to the plan, and its existence
    should not effect the planning process, we can skip decoding when faced
    with errors.

commit 51178958f34e1d24c273646721206455811e0570
Merge: fedd31527 d23f0998f
Author: Alisdair McDiarmid <alisdair@users.noreply.github.com>
Date:   Mon Apr 11 08:05:19 2022 -0400

    Merge pull request #30825 from hashicorp/alisdair/fix-nested-attr-sensitive-collections
    

17.
commit e68ad5ec463fbfa2a9c19abc54f60efb4b779141
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 18:57:50 2022 -0400

    more edits

commit 912e6ff6de5d79bdd5e0ea3672817be3f12d9779
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 18:54:50 2022 -0400

    Apply suggestions from PR review

commit a0ebb94fb598a5822fdab6c6575fae55f3a8efff
Merge: 201c9168f 2f7aa2fcb
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 18:40:26 2022 -0400

    Merge branch 'main' into update-TF-WORKSPACE-variable

commit d3e660d91272c239350f0cf9a01ca94c7437f775
Merge: eb2724d37 b1d933936
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 12:25:43 2022 -0400

    Merge pull request #30772 from hashicorp/laura-update-pre-post-conditions
    
    [WIP] Preconditions and Postconditions Content Updates

commit b1d9339368563b3e76e0b71fd200cafb02870853
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 12:19:29 2022 -0400

    Final formatting nits

commit 3c7c5bbd21dc32fa650c2b3505c77315838421aa
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 12:06:50 2022 -0400

    add links to function and expressions; move result types back to conditionals page (oops)

commit 2a206c7984573d054c1dd6ea2b7eb2a733da01be
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 11:49:33 2022 -0400

    fix incorrect HCL syntax for example

commit 7a43db405c8da55f918b64b37aae59be2a8180b7
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 11:46:37 2022 -0400

    Add link to operators page and all out other types

commit ba3bb5ad5dcfc63c0c72f9ed569f3bf603e191da
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 11:30:20 2022 -0400

    Apply suggestions from PR review

commit 686dbcdb8dfcf45b2063bb28960310b243847614
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 11:24:23 2022 -0400

    fix confusing sentence on lifecycle page

commit 4d4d774aef4a7abbc77b0c951e2f124af1a2327c
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 11:23:15 2022 -0400

    fix confusing sentence on resources page

commit ce757244f284a8270210b6dd85bea554a9fb5b7f
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 11:22:11 2022 -0400

    fix confusing sentence in outputs

commit f660f54b87dc5b8239517560ef3626f16c907f8b
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 11:21:11 2022 -0400

    Final nits from review

commit e8743143e33a2a8c55ebf0fc04438aeff135272b
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 11:17:45 2022 -0400

    Update website/docs/language/data-sources/index.mdx
    
    Co-authored-by: Alisdair McDiarmid <alisdair@users.noreply.github.com>

commit 87b09b1ee173e3b92c1d08ffae6c44242600c62b
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 11:17:16 2022 -0400

    Fix broken HCL in example

commit 696bd4c794aeae99e2cc00ef625f50cb4f09f3d2
Merge: d360a7877 ed59bd729
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Apr 14 10:39:56 2022 -0400

    Merge pull request #30865 from sdinay/patch-1
    
    docs: Fix typo in v1.0 upgrade guide

commit 201c9168fa2939b224d1d1dc81de786d386fd89e
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 13 16:39:28 2022 -0400

    Clarify that users can set TF_WORKSPACE and use tags

commit f9462d5d518a5946b932fc7d188308740f863b73
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Apr 7 16:25:09 2022 -0400

    Update links to say "Custom Condition Checks"

commit 3ed8c5c4679fb4b5d8f8efc11dd52812dc9fd453
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Apr 7 13:51:56 2022 -0400

    Fix in-text link

commit 4c097842df71d42a3c4e6c19ceec22c5e54c1014
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Apr 7 13:48:44 2022 -0400

    Move conditionals information to conditional expressions page

commit 375b3583fdc23076c603e7768bbe75e7de82e9a6
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Apr 7 12:12:13 2022 -0400

    APply suggestions from PR review

commit 3bc3bc52f855dec39ffa1876f6df41ff5f250c9d
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Apr 7 11:40:01 2022 -0400

    Update website/docs/language/expressions/custom-conditions.mdx
    
    Co-authored-by: Martin Atkins <mart@degeneration.co.uk>

commit b997c983a53932787360d30c45ad14915e20cfda
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Apr 7 11:39:41 2022 -0400

    Update website/docs/language/expressions/custom-conditions.mdx
    
    Co-authored-by: Martin Atkins <mart@degeneration.co.uk>

commit 4ab955eeab799e05636eef502424babb2c016f6c
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Apr 7 10:13:41 2022 -0400

    Update website/docs/language/expressions/custom-conditions.mdx
    
    Co-authored-by: Martin Atkins <mart@degeneration.co.uk>

commit 6b986c94bc4389336b354357fa28def7245ee7c9
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Apr 7 10:12:49 2022 -0400

    Update website/docs/language/expressions/custom-conditions.mdx
    
    Co-authored-by: Martin Atkins <mart@degeneration.co.uk>

commit d69cb58ff5be227ac9aa8395d7a83b3c184e798e
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 6 17:01:04 2022 -0400

    Add additional sections to condition expressions section

commit eea860e0cfe711b5aa832c4231f97bdd002eddb8
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 6 16:55:43 2022 -0400

    Fixing typos and doing a read through

commit 04d329a9e1341cbaa30e94feb9d970f4e852091a
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 6 16:11:36 2022 -0400

    Add references to custom conditions on related pages

commit 5803963be8dfb0ec93229013a1e8bddfd389675c
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 6 15:45:27 2022 -0400

    more nitpicks

commit 62a7b51ba786e5a17a7ea8041dab459befa38785
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 6 15:41:02 2022 -0400

    more edits

commit 3ae238a448c4150dc8b4b68e1d79db3486c2b575
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 6 14:57:20 2022 -0400

    More language edits

commit af7e6888599c4b53e31f29de85f9d9baee52260a
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Apr 5 17:01:21 2022 -0400

    more language cleanup for clarity

commit b2576a3df366b54c31aaaf520819b38e2643134b
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Apr 5 15:50:24 2022 -0400

    Update page name to Custom Conditions per feedback

commit 040985f6e10b245a1f870f9c8c0bff7de8de3984
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Mar 30 17:59:03 2022 -0400

    more edits

commit b0f491f2d1360b2d6d5ba2e01cb86e2478dee18f
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Mar 30 17:57:03 2022 -0400

    update section title

commit d12b170ef23e00bf1dbe9449488f946d4b281564
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Mar 30 17:48:43 2022 -0400

    more page edits for flow and style

commit 5effda41704cf33334ca5918b8ccac1651df7ab0
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Mar 30 17:18:16 2022 -0400

    Rename page again

commit 42d73fe3242495349a054101fe3303bf833e22d5
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Mar 30 17:11:23 2022 -0400

    Rename page in sidebar and change filename

commit 2449fadf0639f3be8fd1f959e69ff60890621dd2
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Mar 30 17:00:13 2022 -0400

    Revising preconditions and postconditions

commit 38dd0ef2f37db9a4c720e12ec5e03bdad99008cf
Merge: 032a4d083 a813854a8
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Mar 29 15:20:49 2022 -0400

    Merge pull request #30423 from noce2/patch-1
    
    Docs Update: Show example of state lock table access control

commit b5c0955cb9d5353ed42e3128df21f7ff04245574
Merge: 11aaff859 d74c4972d
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Mar 28 11:13:28 2022 -0400

    Merge pull request #30712 from hashicorp/file-provisioner-powershell-warning
    
    Add PowerShell note to file provisioner page

commit d74c4972d7c4e74f2ef168d4092f48f4ce121b93
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Mar 21 14:09:25 2022 -0400

    Add more context to note

commit 881fbd1971af4ecf229a06e6afc678f1f0c5beea
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Mar 21 14:03:18 2022 -0400

    Add PowerShell note to file provisioner page

commit 20e9d8e28c32de78ebb8ae0ba2a3a00b70ee89f4
Merge: b386f76b6 0ba0fe667
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Mar 21 12:28:25 2022 -0400

    Merge pull request #30702 from hashicorp/add-powershell-warning
    
    Add note about powershell formatting

commit 0ba0fe667c294f8b073155e90cf2a7b8705fb0f1
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Mar 18 17:18:25 2022 -0400

    Add period

commit c7afb7db940ec9143e2e24b0d2ae9994a580f379
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Mar 18 17:15:24 2022 -0400

    Add note about powershell formatting

commit 7c0cbaa4070f9c2fc7600edd1c2b99a3f53522fd
Merge: 50d49d0b0 53e3f044b
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Mar 15 16:50:36 2022 -0400

    Merge pull request #30281 from Mukesh05/patch-3
    
    Terraform may be misled, not provider

commit 50d49d0b0d0b5ee25dccef53993bfec865357e1a
Merge: 24d174d36 659fb09fc
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Mar 15 16:47:23 2022 -0400

    Merge pull request #30649 from dragondrop-cloud/main
    
    Documentation Update: Capture `cloud`/ `backend` block override behavior in docs

commit 53e3f044b020d5c200b79c676cbb0b4119c15eaa
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Mar 14 12:18:54 2022 -0400

    Update website/docs/cli/commands/refresh.mdx

commit c74937dc9318ab4b8a4c95ae198d08ba0bf716b5
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Mar 14 12:18:50 2022 -0400

    Update website/docs/cli/commands/refresh.mdx

commit 63e0b4a5afb41a38fadb2659fb16366c036bedc4
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Mar 14 12:18:45 2022 -0400

    Update website/docs/cli/commands/refresh.mdx

commit 821064edd38fb5c6bc46349a7812a6fe27eccff7
Merge: 63fa72022 0ea6874bc
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Mar 10 18:08:29 2022 -0500

    Merge pull request #30637 from kderck/patch-2
    
    Change aws.dest to aws.dst

commit 63fa72022f0ca932b415cd317ec2b6d5cc291acd
Merge: 2aa1613c1 d6a98ac22
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Mar 10 18:03:47 2022 -0500

    Merge pull request #30631 from savage-tm/patch-1
    
    Document logical operators not short-circuiting

commit e8364b2505d39113e001255a94c61479a2fffad5
Merge: 195adc042 ad1ba5ef1
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Feb 25 11:25:27 2022 -0500

    Merge pull request #30580 from hashicorp/fix-broken-link
    
    Fix broken link on provisioners connection page

commit ad1ba5ef125f72135c4b8ba964ca71e4df1dd810
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Feb 24 18:15:05 2022 -0500

    fix broken link on provisioners connection page

commit 68e70d71d48151986698db29235f2ff47a685895
Merge: aed7162e9 252865c6a
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Feb 15 11:27:47 2022 -0500

    Merge pull request #30483 from bpar476/patch-1
    
    Adds documentation to `substr` function to cover when `length` exceeds input length

commit c5740baa772fc65dcce5cb33be4b56f181073278
Merge: c1dc94a3d 24cffb5ff
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Feb 9 17:47:13 2022 -0500

    Merge pull request #30503 from hashicorp/fix-workspace-name-docs
    
    Clarify workspace.name expression

commit 24cffb5ff3046530537473c0b2336e8ed5cbc430
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Feb 9 17:41:12 2022 -0500

    Soften language for determining run environment

commit 422b47618c7919fbca1a1197d4e51760e1334903
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Feb 9 17:37:06 2022 -0500

    Change name example to match new edits

commit 8be2c4a3972f706c52c4b8df88e37cd2fd0ca6a2
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Feb 9 14:30:02 2022 -0500

    fix link

commit faffa11e08d0be227682d7dc3fd09472abce613a
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Feb 9 14:21:46 2022 -0500

    Update workspaces page

commit ba0e2c1133f0ec26445aa478fada1897e2311e20
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Feb 9 14:10:11 2022 -0500

    Update remote backend page to clarify workspace.name expression

commit c1dc94a3d20d32a3a58c988d84de87d4fbf16864
Merge: 3af6e8246 3c40dac0b
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Feb 8 16:36:36 2022 -0500

    Merge pull request #30488 from hashicorp/update-console-docs
    
    Update Console Command Documentation

commit 3c40dac0bc9a45d83a5e6987e3632ffa2be51c8d
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Feb 8 16:22:44 2022 -0500

    Fix according to PR comments

commit b6dd327fd3d78807e1291055e18c0d9b796c3778
Merge: 2a3b0f9c1 7eee8c674
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Feb 7 18:52:57 2022 -0500

    Merge pull request #30487 from hashicorp/update-depends-on-docs
    
    Update depends_on documentation

commit fe6092f325a494e0029b26829c8d0f455c0e5161
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Feb 7 18:45:07 2022 -0500

    Add line about how you can't use console during a run

commit 7eee8c674e44a8bc8a69a3e5af61c497dd253dfc
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Feb 7 18:16:16 2022 -0500

    Remove extra spaces

commit 879edcae726ba93a18b9615ba42942ced298a2d7
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Feb 7 18:09:07 2022 -0500

    wording changes

commit 2a3b0f9c1ee33597a67bb5152baf0f49ff0b93da
Merge: dbc143a04 ffcb167bc
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Feb 7 14:23:52 2022 -0500

    Merge pull request #30017 from RubyElders/internal-contributing-docs
    
    Update go test commands in .github/CONTRIBUTING.md.

commit dbc143a043eb33736c8415d6ec77850b5b59394a
Merge: d1ac8b71d 6e399dfbe
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Feb 7 13:19:24 2022 -0500

    Merge pull request #30484 from hashicorp/fix-preconditions
    
    Preconditions and Postconditions - Quick Fixes

commit 6e399dfbe02098deb22c89a1dd069a2931964cd6
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Feb 7 12:04:50 2022 -0500

    Update filename

commit 834f65e4f068c99a76d071f3ab4e46f250521018
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Feb 7 11:59:28 2022 -0500

    Fix formatting issues that would prevent website from loading

commit d3bc3a63ddd4e760ac73eafd9ffea0b408d5f9b5
Merge: 0900c7e0b a794c80e0
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Feb 1 10:47:04 2022 -0500

    Merge pull request #30431 from hashicorp/replace-flag-clarifications
    
    Make -replace flag clearer

commit a794c80e0d6e9c0aa390f261b745c79cdad746eb
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Jan 31 14:17:36 2022 -0500

    final nits

commit d14e04bf36139721284aa03e970916126f516915
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Jan 31 14:03:03 2022 -0500

    Fix notes according to PR feedback

commit a2f83ef7b61e14d858c87f0b25b769852a6c86a3
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jan 28 15:28:35 2022 -0500

    Try to fix wording so it's clearer and more cohesive

commit 6e80276cc9dd11b42240c57e6441e852c92891fb
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jan 28 14:44:56 2022 -0500

    Remove invisible space

commit f56c7c1c85fabdb9ddda02729516b5c785dadbc7
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Jan 27 17:05:45 2022 -0500

    Make language in callouts more user friendly

commit dca94a9eaf4012250c9fe8ddbb15cea9ef84f8a7
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Jan 27 16:58:17 2022 -0500

    fix verb tense

commit aa3a046af3747256bdd3bd464234008775d5c431
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Jan 27 16:56:50 2022 -0500

    final nits

commit 1a66861aaff4de88b3db0008715a37d4cd0036d6
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Jan 27 16:53:25 2022 -0500

    A couple other tweaks

commit 238396567d32e95a2e6159b6f8c33e72e9433bfa
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Jan 27 16:00:08 2022 -0500

    Making replace flag clearer and making plan options clearer

commit a855f042811742a548c4d4e2c2e8c7e9e1b76a7a
Merge: b8709d369 6a02fbaef
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Jan 27 10:52:30 2022 -0500

    Merge pull request #30428 from hashicorp/fix-last-intro-nits
    
    Fixing some final typos and nits

commit 6a02fbaef386aad36b8819b59a3dc04904a1ba89
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 26 20:06:49 2022 -0500

    Fixing some final typos and nits that robin found!

commit df745af29fa8ee4eda2be70388b93357d64f9191
Merge: fb4b5c4d8 4188c4c51
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 26 18:42:53 2022 -0500

    Merge pull request #30425 from hashicorp/fix-intro-page-images
    
    fix image references on intro page

commit 4188c4c518651b408eb14d4bf8a07922b49b2f80
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 26 18:21:09 2022 -0500

    fix image references on intro page

commit fb4b5c4d815ab1544b4771c0c07ba5fb28686d85
Merge: fb61a3d08 4ced2181c
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 26 17:57:50 2022 -0500

    Merge pull request #30399 from hashicorp/add-new-intro-docs
    
    Revamp Into to Terraform

commit 4ced2181ca0db0e25943330c24e8d6f90ba855e8
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 26 16:30:05 2022 -0500

    Update SDN tutorials to recommended ones

commit d5b0f44e37488662959509af95e0b4b597eb56a9
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 26 16:12:12 2022 -0500

    Update website/intro/index.mdx
    
    Co-authored-by: Judith Malnick <judith.patudith@gmail.com>

commit 8ab9edf8caef81773ede888385e1ef0125f8e113
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 26 16:12:04 2022 -0500

    Update website/intro/index.mdx
    
    Co-authored-by: Judith Malnick <judith.patudith@gmail.com>

commit 4a8b4b311d9630e23fe8ddc72082c29f3f27b57e
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 26 16:11:52 2022 -0500

    Update website/intro/use-cases.mdx
    
    Co-authored-by: Judith Malnick <judith.patudith@gmail.com>

commit 2201ebc0751d9547463688a99a2ffafde570d4a0
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 26 16:11:47 2022 -0500

    Update website/intro/use-cases.mdx
    
    Co-authored-by: Judith Malnick <judith.patudith@gmail.com>

commit 2209b00167e48c227887d5823f1ed98db06f1a91
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 26 16:11:42 2022 -0500

    Update website/intro/use-cases.mdx
    
    Co-authored-by: Judith Malnick <judith.patudith@gmail.com>

commit 05391559438a2aeed96b0c3524ff53757192acda
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 26 16:11:31 2022 -0500

    Update website/intro/use-cases.mdx
    
    Co-authored-by: Judith Malnick <judith.patudith@gmail.com>

commit 283e3c8ddb0e298e52017a0ac045fb79cc5f24a1
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 26 16:11:24 2022 -0500

    Update website/intro/use-cases.mdx
    
    Co-authored-by: Judith Malnick <judith.patudith@gmail.com>

commit 10b1f8599109e449952191033be60a485a0500f1
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 26 16:11:16 2022 -0500

    Update website/intro/use-cases.mdx
    
    Co-authored-by: Judith Malnick <judith.patudith@gmail.com>

commit 240243167968428454235e7ba52874d33c5a2305
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 26 16:11:10 2022 -0500

    Update website/intro/terraform-editions.mdx
    
    Co-authored-by: Judith Malnick <judith.patudith@gmail.com>

commit f76762816304b88cd720b79196f708c66e92d609
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 26 16:10:54 2022 -0500

    Update website/intro/terraform-editions.mdx
    
    Co-authored-by: Judith Malnick <judith.patudith@gmail.com>

commit 749507dd6aa025e6da5923baec1378e0cbdcdd46
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 26 16:10:34 2022 -0500

    Update website/intro/terraform-editions.mdx
    
    Co-authored-by: Judith Malnick <judith.patudith@gmail.com>

commit 044ed1c65aef06805e7a26998846f56b860e0435
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 26 16:10:27 2022 -0500

    Update website/intro/terraform-editions.mdx
    
    Co-authored-by: Judith Malnick <judith.patudith@gmail.com>

commit fb61a3d0862f1de2fa7606a32e3a87c5b8ad2da2
Merge: c849e6163 9e28fc44c
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 26 12:01:02 2022 -0500

    Merge pull request #30235 from hashicorp/fix-remote-backend-references
    
    [WIP] Fix remaining remote backend references

commit 9e28fc44cdd5fb824f3c7b5121e53044908a9f0e
Merge: 53aa84576 c849e6163
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 26 11:47:19 2022 -0500

    Merge branch 'main' into fix-remote-backend-references

commit 53aa84576f6ce8294adba8e78658417f920ece45
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 26 11:43:16 2022 -0500

    Update website/docs/language/state/remote-state-data.mdx
    
    Co-authored-by: Nick Fagerlund <nick.fagerlund@gmail.com>

commit 1b1b5225a2a954d2ff2741b2db49a80fa3c8e01f
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 26 11:42:22 2022 -0500

    Update website/docs/language/state/remote-state-data.mdx
    
    Co-authored-by: Nick Fagerlund <nick.fagerlund@gmail.com>

commit e9d79f52848d4b93369936c7b45e335859a5cf5c
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 26 11:41:57 2022 -0500

    Update website/docs/cli/import/index.mdx
    
    Co-authored-by: Nick Fagerlund <nick.fagerlund@gmail.com>

commit 11a450d3414b03e0c220fb7ada308bbb7b668c03
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 26 11:18:18 2022 -0500

    Final editing pass

commit 9953260083d35d9fb08d136320c8f104d79a13e4
Merge: 5a9bc76d1 20e740ef8
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Jan 24 13:49:28 2022 -0500

    Merge pull request #30296 from hashicorp/fix-provisioners-content
    
    Fix provisioners content

commit 95adde5dc9236078313d0dc53702881320b3af5b
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Jan 24 12:29:54 2022 -0500

    Update vs. index page to say "Alternatives" and include a list on the page for SEO

commit f1b36873e1ab403fe789f951a52991029b570a9d
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Jan 24 12:25:20 2022 -0500

    Update Use Cases page copy

commit 5e618901396be01e5d50ac80452e5eb5c787aaa7
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Jan 24 12:19:19 2022 -0500

    Add editions page and update sidebar

commit a00306474d07c1a0d610c82bc5fa17454926bd88
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Jan 24 12:09:13 2022 -0500

    Add new content for intro page

commit 20e740ef8830d211396a8d5e1b7bf284a441d665
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jan 21 11:01:37 2022 -0500

    Final formatting and langauge nits

commit 9f4c4ff093828b5ba54e9bd8a58c5dd07ad6a95c
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jan 21 10:48:27 2022 -0500

    Update note to be more direct :)

commit 1d53273b7a7b945a3dc681d0f4632255fd937236
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Jan 20 11:28:52 2022 -0500

    Language nits

commit 29a4591cf2042b4718cfb29f97c2d0d735ae6117
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Jan 20 10:57:38 2022 -0500

    Fix warning notes

commit ec17cbaeee44730c23f88c92138b0f1bbf5608da
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 5 12:10:01 2022 -0500

    update additional references to overview page

commit 20e9f30c3d364502ba388a6c10a990917c16db30
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 5 12:02:04 2022 -0500

    formatting nits

commit 63106da0b9bc9de334a967516b0a896bbaed0aa8
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 5 11:53:39 2022 -0500

    Language updates

commit 5cb8be0d500f16ac5c4c7c02a0e7a9425b734853
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 5 11:13:27 2022 -0500

    Update nav to remove overview page that no longer exists

commit 5d24146f1748c198f230ec3411d8c1be2ea70248
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 5 11:12:49 2022 -0500

    Oops edited the wrong layout file

commit bfefb7405eefdbc8f74e82669148eb1379c0ec73
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 5 11:09:43 2022 -0500

    Update layout file to remove deleted page

commit fc4ceedc6d2b5d2a93511e5dadd442c984044745
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jan 5 11:08:33 2022 -0500

    Remove overview page and update notes on provisioner pages

commit 5f61140655a2f257eb704cf69a951e473bf5ee1d
Merge: beb943215 1b7e7b967
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Jan 11 10:40:12 2022 -0500

    Merge pull request #30332 from hashicorp/fix-broken-links-1-10
    
    Fix broken links to external docs

commit 1b7e7b967dca992d04a093b3ae1c6b03f6cc267f
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Jan 10 17:49:49 2022 -0500

    Fix broken links to external docs

commit f4eb0ed24d50a5906797e2a1f31880d9b7f43b14
Merge: 4ec1feaa3 3ac334f26
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jan 7 10:22:57 2022 -0500

    Merge pull request #30280 from Mukesh05/patch-2
    
    Update local values definition

commit 870116c5091d9d0606f04da1daceea70a0b99923
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Jan 6 11:48:13 2022 -0500

    more langauge edits

commit fbf02d63429098c2a8e4c0220df77c7d9485bbf5
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Jan 6 11:46:08 2022 -0500

    Language edits

commit 6ef9cf652e30b3615c3cd09ad2ca926c7c24101f
Merge: 662301610 01be55b5c
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Jan 6 11:14:46 2022 -0500

    Merge pull request #30270 from addison-grant/patch-1
    
    Update variables.mdx to fix typo

commit 662301610daddd2433689110d71b53fc1ad3b2b9
Merge: 28a6036cf bdf683802
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Jan 6 11:13:36 2022 -0500

    Merge pull request #30264 from minamijoyo/fix-typo-in-doc
    
    docs: Fix typo in docs/plugin-protocol/releasing-new-version.md

commit 8b69d24147ff6350ab21c93065bc607357bfddca
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Jan 4 16:31:52 2022 -0500

    Update remote state data source page

commit 96b31fb1d351b472595f8b44fec8c45486d41bce
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Jan 4 15:43:52 2022 -0500

    Update core workflow page

commit 5792973dd6ff57e9709afac9108f8f9142ef6d25
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Jan 4 15:22:12 2022 -0500

    Update language on import command page

commit cab5305191e21f9226681c52a2f1118f0bced260
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Jan 4 14:58:31 2022 -0500

    Fix formatting

commit 138ca02b90442ca69ea9025ea6e10faa2383c17b
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Dec 21 17:51:06 2021 -0500

    More mentions of remote backend

commit caf0bdbe8d43c3acca0494e8e5145dede723e6b3
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Dec 21 17:39:30 2021 -0500

    fix push

commit 9022b23d574b0c1f160033178f56959ee50f2cdc
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Dec 21 17:37:35 2021 -0500

    Fixing references again

commit 3adcc0158c854fb725438e31383ccb77eaa337b2
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Dec 21 17:19:05 2021 -0500

    Add cli integration to command pages

commit f55af420869e12f816e7e62e731853373dd66ea2
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Dec 21 17:10:29 2021 -0500

    Update module sources page

commit 04fb42cb05ad0d68f907a87fa99eb9063952a250
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Dec 21 17:05:09 2021 -0500

    Update push CLI command page

commit cd7277128f5a3cf706307b4d11837b57b8028988
Merge: 8b6522169 2a530639f
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Dec 21 10:42:46 2021 -0500

    Merge pull request #30223 from hashicorp/replace-flag-updates
    
    Update taint command page to make alternative clearer

commit 2a530639f8906ca3f420963243c67bf63246b0a2
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Dec 20 16:01:03 2021 -0500

    Tweaks

commit 410e45673d27ef33fef1cc1396991e380889b554
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Dec 20 15:43:31 2021 -0500

    Update taint command page to make alternative clearer

commit 7ae574ba6a6eec23273ae98271c291d0bf584093
Merge: cd8b458b9 775602356
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Dec 9 16:35:50 2021 -0500

    Merge pull request #30082 from c00k133/docs-vars-typo
    
    Docs: Change misspelling of variable in documentation

commit cd8b458b9c9ddfa3599aedf3d6755dcb5aa488cd
Merge: b27c28f34 b202eefc7
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Dec 9 16:35:12 2021 -0500

    Merge pull request #30118 from marcusway/patch-1
    
    Update docs to use `assume_role` block

commit 839458c1929df2a4172daecaf931ee5bcc576a48
Merge: 533a29ede 168c2885e
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Dec 8 18:04:30 2021 -0500

    Merge pull request #30116 from hashicorp/fix-links-release
    
    Update broken links

commit 168c2885e353e06858a1727c84a655b1635ae0c0
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Dec 8 18:03:26 2021 -0500

    Fix link text

commit 22d80df0ba07adea6a4f388097f0cc4ee0ced6f1
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Dec 8 18:01:48 2021 -0500

    Fix extra space in link

commit 2edd9f4e10faf38e65d5fc5ce4e29c3c4e3b59b0
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Dec 8 17:53:18 2021 -0500

    Update broken links

commit 70740e9493b4e8d0f65e85a14072ea867d580a3c
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Dec 8 14:13:47 2021 -0500

    Add tutorial to moving resources page

commit 91755d380ff13b6657e62f86b279cfe5fdf9ee70
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Dec 8 14:01:58 2021 -0500

    udpate to migrating page

commit 0bd3491ef8b9e5e3449f506b31540b40123a7776
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Dec 8 13:55:45 2021 -0500

    Fix typo and update note

commit d0cb88f0915f7f5e5983e5d56f4ad6bbbe4e0494
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Dec 8 13:49:58 2021 -0500

    Updates to TFC page in Language

commit ab23ecb210894ab107d7099b5f81612c9269f0d1
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Dec 8 13:47:42 2021 -0500

    Change "see" to "refer to"

commit 829e9b4842d5a419de2e27da33a5b89d3a11a076
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Dec 8 13:45:14 2021 -0500

    Update settings page

commit 502ec81ae20049fa1a8de040305f6352c70cdd92
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Dec 8 13:37:22 2021 -0500

    Update initializing page

commit c713815e332f1cb1c8977729c0d8261cb92615a7
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Dec 8 13:09:12 2021 -0500

    Add learn callout to usiing TFC index page

commit c17317ded4f2615cc85e578b2be947677fdf46dc
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Dec 8 13:05:24 2021 -0500

    Update website/docs/cli/cloud/index.html.md
    
    Co-authored-by: Judith Malnick <judith.patudith@gmail.com>

commit 02aed8a4dffe51bc813ae8adfd79ad6e5775701c
Merge: fc7358611 529a2c34d
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Dec 7 17:18:17 2021 -0500

    Merge pull request #30100 from hashicorp/add-learn-callout-moved-blocks
    
    Update note and add learn call out

commit 529a2c34dfd14d8b41c9d5caf68415ec750dd825
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Dec 7 17:09:13 2021 -0500

    Update note and add learn call out

commit fc7358611c817c5546fe0c27382bc6eb6030b898
Merge: 16800d130 4f634bf8d
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Dec 6 11:06:13 2021 -0500

    Merge pull request #29931 from alekssaul/patch-1
    
    Website/Docs: debian install - run apt update first

commit 01dbfd2d30b80f4805799f1c0bc226bd61ccb633
Merge: 528b51386 ecc8bcfe5
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Dec 3 11:06:32 2021 -0500

    Merge pull request #30028 from multani/patch-1
    
    Improve `.terraformignore` doc formatting

commit 528b5138694e5f3cd336f9017a3e8d3e23206535
Merge: ba6a64eb3 fba26b10e
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Dec 3 10:59:23 2021 -0500

    Merge pull request #30037 from DanHatesNumbers/patch-1
    
    Fix example for values-representation in docs for JSON Format internals

commit 7e41803418cee8ecc479702913da82e95698de15
Merge: bf76cc98e bd64d07e6
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Nov 15 11:17:27 2021 -0500

    Merge pull request #29891 from hashicorp/update-for-each-example
    
    Add cidr block output example to setproduct function page

commit bd64d07e6b9e97dfadc036318ebc96ad4edf1bad
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Nov 15 10:49:37 2021 -0500

    Apply suggestions from code review

commit 19101df1d4d04cab44d169b0177817ea711dc39b
Merge: 4f6647950 8367c049c
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Nov 5 11:08:05 2021 -0400

    Merge pull request #29887 from strugee/patch-1
    
    Fix typo in 0.13 upgrade guide

commit b838a9302375498fda49fdc4551bd22c434fa3a8
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Nov 5 10:51:59 2021 -0400

    Add cidr block output example to setproduct function page

commit 0ef4fe0aabf76890daeea1af5e0ab95f6e239a0a
Merge: 9bb5a58e3 45dab1b95
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Oct 26 09:49:46 2021 -0400

    Merge pull request #29691 from ramj9/patch-1
    
    replace an with a

commit 8f09e27597c9e792d7d9acea158429f10269572d
Merge: 5386d6c5b c8e2be76d
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Sep 20 17:24:31 2021 -0400

    Merge pull request #29567 from drasko95/patch-1
    
    Fix a documentation typo

commit dfbef12a6ca4ba95531bef09ac6c7edc3cc2868b
Merge: 1bd5987a8 a8e5b6a4a
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Sep 16 17:30:37 2021 -0400

    Merge pull request #29598 from hashicorp/laura-add-mrui-to-sidebar
    
    Add Machine-Readable UI to sidebar

commit a8e5b6a4ad1747d95a6f00acde01d68f3fc5b3b8
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Sep 16 17:11:31 2021 -0400

    Fix alphabetical order of sidebar

commit 4d1baaceabaa968c1e5009536a70341b1657b7fe
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Sep 16 17:06:52 2021 -0400

    Add Machine-Readable UI to sidebar and add hyphen :-)

commit dcf2d3c1efa2165cfe953794bcfcb8d074d2ed9b
Merge: 8ed9a270e f238e9395
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Sep 13 10:39:02 2021 -0400

    Merge pull request #29494 from magnetikonline/docs-s3-backend-dynamodb-partition-key
    
    S3 backend documentation update - DynamoDB uses Partition keys, not primary keys - redux

commit 43f960b19736cf6f7d6413a85b3d33f88a1e5a6c
Merge: 48768a003 a303a03f2
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Sep 9 15:09:31 2021 -0400

    Merge pull request #28579 from ChadBailey/patch-2
    
    Added clarity: remote-exec connection requirement

commit 48768a0037c27dad8fd09de6383455ada77b9275
Merge: 64a95fc29 49b31d005
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Sep 9 14:54:17 2021 -0400

    Merge pull request #29451 from kmadof/patch-1
    
    Added required paramter `resource_group_name` for MSI

commit a819d7db3ad489e91aff0f295f9d0d44b34ecc81
Merge: 1cd6c9fae b60f201ee
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Sep 9 11:06:58 2021 -0400

    Merge pull request #29502 from hashicorp/alisdair/json-format-version
    
    json-output: Release format version 1.0

commit 3c518880d39b5d7abf118440241e3e26f4184a72
Merge: 1e1d47d16 e3b6c6403
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Sep 3 12:11:34 2021 -0400

    Merge pull request #29509 from drewmullen/d-module-source-revision-option
    
    documentation: commit sha can be passed to ref

commit 1e1d47d16d343e5bd917c24ce24d8675431435dd
Merge: 4f10de2ac fa4c590f5
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Sep 3 10:19:30 2021 -0400

    Merge pull request #28345 from yvespp/destroy_provisioners_doc
    
    document that destroy provisioners don't run with create_before_destroy

commit 73a3bb27029054a0c14f2aef8081900bf821c809
Merge: 05f21cdff b8a0929a5
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Sep 2 14:47:38 2021 -0400

    Merge pull request #28334 from paultyng/patch-1
    
    Add null to type conversion docs

commit c29e10b0f10e845e0d36a89b9cc83a5bd6c36fa8
Merge: fee0bffed b1d56076a
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Aug 30 12:04:30 2021 -0400

    Merge pull request #29480 from Lasthalf/patch-1
    
    generated -> generate

commit daad109067931a4b5e5056877ded4c25b9dc686d
Merge: cb6218ac6 21228e19d
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Aug 25 10:14:12 2021 -0400

    Merge pull request #29063 from moskyb/s3-backend-kms-permissioning-note
    
    Add a note to the docs on the S3 backend around permissions needed for encrypted state storage

commit cb6218ac650342a1d5c3afc1b34498972fb057a8
Merge: 0a78072a2 e3258b6f3
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Aug 23 18:05:28 2021 -0400

    Merge pull request #28310 from gastrodon/main
    
    docs: fix link to index

commit 0a78072a2bffda9239a048d6974be9c754315051
Merge: 03849d850 ede75a944
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Aug 23 18:00:42 2021 -0400

    Merge pull request #28089 from jnerin/patch-1
    
    Update expressions.html link to operators.html

commit 03849d850a0020c7a1eb3c631e472ddb4ba6fc15
Merge: 3018289bb cb41b158f
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Aug 23 15:49:51 2021 -0400

    Merge pull request #28486 from joshschmitter/patch-1
    
    setsubtract doc: use "Relative Complement" correctly

commit 3018289bbff26199f20a1b5a499382536c160043
Merge: dffb8b4a1 d427c81a8
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Aug 23 15:33:55 2021 -0400

    Merge pull request #29449 from hashicorp/laura-fix-jsonencode-note
    
    Update jsonencode minified note

commit d427c81a89178da55bcb433525bbae2193bd73e1
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Aug 23 15:01:38 2021 -0400

    Update jsonencode minified note

commit dffb8b4a1669c5313f555afe4cbe968c64360b9d
Merge: 5863af448 ed84cb886
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Aug 23 14:24:37 2021 -0400

    Merge pull request #29088 from brenthc/minify_jsonencode
    
    note that output of jsonencode is minified

commit 5863af448fe4cf40b4ea55b4241d16f4db5c8d0c
Merge: c1d16c742 511011335
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Aug 23 14:07:15 2021 -0400

    Merge pull request #28784 from TAYTS/patch-2
    
    Update range.html.md

commit c1d16c74212f313733bd3a1c355f398c663d5a62
Merge: 6235453d2 0103f5829
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Aug 23 14:00:43 2021 -0400

    Merge pull request #29311 from NargiT/patch-1
    
    fix syntax

commit 6235453d21c2b65682c9d3526f1d0a230eee8f87
Merge: d0bc38279 b3e1a4049
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Aug 23 13:59:48 2021 -0400

    Merge pull request #29358 from moajo/add-s3-delete-object-to-document
    
    Update website/docs/language/settings/backends/s3.html.md

commit d0bc382797eb6113357ae6c80344113ef332ee63
Merge: c8dfaa12c 494043ed2
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Aug 23 13:57:27 2021 -0400

    Merge pull request #29359 from 45deg/45deg-patch-1
    
    Fix a result in examples for urlencode.html.md

commit c8dfaa12cc35bf5b5414ff3b9f29cf7eea8aa169
Merge: d2f80f35b 4fd3bd491
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Aug 23 13:35:31 2021 -0400

    Merge pull request #29433 from fedorg/patch-1
    
    remove large sections of empty space

commit d2f80f35b14749cd3743df6936b537e0cb316ca2
Merge: 960f736bc 1f5069d9d
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Aug 23 12:31:43 2021 -0400

    Merge pull request #29316 from alkis-hexa/patch-1
    
    Update for.html.md

commit e1b702b8d0e40b769c2e697c9348120e11f7c289
Merge: b574c03dd e4e5f5a1a
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Aug 18 18:24:54 2021 -0400

    Merge pull request #29417 from jonesetc/patch-1
    
    Fix link to index function

commit b574c03dd1579365fe1f20788af4d6eeefb40b60
Merge: 9dde62ef5 f5cbe5938
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Aug 18 18:22:06 2021 -0400

    Merge pull request #29271 from kebroad/patch-1
    
    Fixed cidrhost() example 1 and 2 with correct function parameter

commit 9dde62ef5d86f91604957f2252331b2289e3462c
Merge: 58aabb54c 880f846f4
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Aug 18 18:15:09 2021 -0400

    Merge pull request #29257 from robe007/patch-1
    
    Remove repeated word 'the' in some lines.

commit 3376752b0814fb50277a5f809dd22597f28a7469
Merge: 10e431487 c69024783
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Aug 9 11:44:33 2021 -0400

    Merge pull request #29273 from mellab/patch-1
    
    Fixed typo on type-constraints.html.md

commit 5b07bb70401093a9ddbb3f2ebc3e2598ec9642d7
Merge: 97a269452 31af9adc0
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 14:49:36 2021 -0400

    Merge pull request #29216 from hashicorp/laura-description-metadata-cli
    
    Laura description metadata cli

commit 31af9adc005258de7d5c15ee7257e10e23dfe827
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 14:44:17 2021 -0400

    Make all sentences start with caps + additional tweak wording edits

commit 845470617dfa4fa1474ed2096a443304f31c0a45
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 14:25:01 2021 -0400

    Address PR comments for manipulating state index

commit 2034c179482fda698e606eb30d5d7fca537a07b7
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 14:22:16 2021 -0400

    Address PR comments on inspect index page

commit 0abd79c9b443dd8548e0aa049c97e89c1b5822d0
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 14:19:14 2021 -0400

    Address PR comments on workspace command index page

commit 18a314349513d9bc984e3c60a8f15651add0265e
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 14:15:46 2021 -0400

    Address PR comments for init page

commit e94bf7bc1622a419f2beeef639abfa6f02315ac5
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 14:13:04 2021 -0400

    Address PR comments for cli index page

commit 342335003d0214700eaf3b0cf0c3a474e358cfde
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 14:10:32 2021 -0400

    Update website/docs/cli/commands/import.html.md
    
    Co-authored-by: Tu Nguyen <im2nguyen@users.noreply.github.com>

commit d59777c12fa1b069aabd7bcaf00111a14379010e
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 14:07:45 2021 -0400

    Update website/docs/language/modules/sources.html.md
    
    Co-authored-by: Tu Nguyen <im2nguyen@users.noreply.github.com>

commit 6874aad76df5652a9b43475f1ab6efef050021c5
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 14:07:19 2021 -0400

    Update website/docs/language/meta-arguments/resource-provider.html.md
    
    Co-authored-by: Tu Nguyen <im2nguyen@users.noreply.github.com>

commit 809f50fbf2a5502a1f421fb40c59adac9baf61d0
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 14:07:03 2021 -0400

    Update website/docs/language/meta-arguments/module-providers.html.md
    
    Co-authored-by: Tu Nguyen <im2nguyen@users.noreply.github.com>

commit 87348f97f8951de611fa9fee6dbc2f686f5ca7dc
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 14:06:20 2021 -0400

    Update website/docs/language/expressions/dynamic-blocks.html.md
    
    Co-authored-by: Tu Nguyen <im2nguyen@users.noreply.github.com>

commit 507ad21a91e126e593145e71be34bd0c18e8cafd
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 14:05:06 2021 -0400

    Update website/docs/cli/import/index.html.md
    
    Co-authored-by: Tu Nguyen <im2nguyen@users.noreply.github.com>

commit fb6ff1f4408710bddc7248dd42605f5fc2a54d37
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 14:04:39 2021 -0400

    Update website/docs/cli/state/inspect.html.md
    
    Co-authored-by: Tu Nguyen <im2nguyen@users.noreply.github.com>

commit f2552e502ab5b0f1a8a613741b67c3b27668b499
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 11:21:10 2021 -0400

    Update metadata on graph command page

commit 58bc29b61b65cc2f5d755d5bba790950ec7934bd
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 11:19:44 2021 -0400

    update metadata on get command page

commit fef4ccb7950dcac92c3c35758079b9fa69faff2e
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 11:18:58 2021 -0400

    Update metadta on force-unlock command page

commit e326a7b1a51cdfefe1af82f77b6d504d99f7b953
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 11:17:17 2021 -0400

    Update metadata on providers command page

commit 7105ed7a1e0ff4d688782e0a1711abb51a37e2c5
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 11:16:08 2021 -0400

    Update metadata on version command page

commit 5a6d2e42ef9df365f24d915693152c2971611a77
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 11:14:37 2021 -0400

    Update metadata on init command page

commit 2ba0dcb8c89c70a2a401f1470e9a1c3e5f3e90de
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 11:08:48 2021 -0400

    Update metadata on provisioning infrastructure index page

commit 99039137970c851e27b01cb5dc1001461f53c11d
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 11:08:02 2021 -0400

    Remove back ticks from run index page

commit 5387f248c9425efc4946c584549e24257c31e147
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 11:06:00 2021 -0400

    Remove back ticks from workspace index page

commit 99cc8c02c6ae9bf34aac7982ad8c69a18393819e
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 11:05:19 2021 -0400

    Remove back ticks from plan command page

commit a5e98df3395b0e18a96c8a264227fe7a403dc0fb
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 11:04:30 2021 -0400

    Remove back ticks from CLI commands index page

commit 1419315f3a2c5dfc82c220d7ffc4ed3a774b0efd
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 11:03:03 2021 -0400

    Remove back ticks from terraform import page

commit 294a1fdd2c070b4c3c0d1954de76171f29b8481a
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 11:02:31 2021 -0400

    Remove back ticks from terraform fmt page

commit 706611e2c8b1fa8df93c85f093fb7e56e4f0643c
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 11:02:03 2021 -0400

    Remove back ticks from env command page

commit 661b7703eab01c62c8a69c45104ffa86e9671f8f
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 11:01:28 2021 -0400

    Remove back ticks from destroy command page

commit d081fe41a4291c0f79caa5bcd6b89cbeb33d523e
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 11:01:00 2021 -0400

    Remove back ticks from console command page

commit e7a8595e1dfa612294c5a776e2f7f2d2d876e3ae
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 11:00:23 2021 -0400

    Remove back ticks from apply command page

commit 4e40ce13dbec8f651a84034f35b822f048a7959d
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 10:59:45 2021 -0400

    Remove back ticks from auth index page

commit 3ae552fbc9d15320b3292d3a1c74e2e1eab466df
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 10:57:44 2021 -0400

    Remove back ticks from syntax index page

commit 2970efff00130b01c88b6888dae450d4c010f312
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 10:56:11 2021 -0400

    Remove back ticks from settings index page

commit e6903e860a88cc2b24d59319fc9af8fba3e6d816
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 10:55:13 2021 -0400

    Remove back ticks from null_resource_page

commit 22588ca1056ea3b1af5628e2fa151277b6f8c846
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 10:54:39 2021 -0400

    Remove back ticks from connection block page

commit 058fa43d5d4bfa8c2c343e8247fd1859479efa6e
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 10:53:58 2021 -0400

    Remove back ticks from resource index page

commit 8a919d98d4df8e2770fec127a54397375dfbdf32
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 10:53:17 2021 -0400

    Remove back ticks from resource behavior page

commit 6e0349645ef7133a359338859b1c7ffa218511f8
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 10:52:25 2021 -0400

    Remove back ticks from configuration page

commit 277fe647b95e32b9ca0738cd20af09735954dfd8
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 10:51:46 2021 -0400

    Remove back ticks from source module page

commit 2e34e7a727c4265ff818639ea5ea76aca854b1d0
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 10:50:39 2021 -0400

    Remove back ticks from module providers meta argument page

commit 512bb1a3c56d4958019676043f1a30871adac9cc
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 10:49:28 2021 -0400

    Remove back ticks from provider meta argument page

commit 051ce2ae6c68e402e0498106d11e339170e25afc
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 10:47:31 2021 -0400

    Remove back ticks from lifecycle page

commit a7c1ae72a4572f4dc9218f3fbbee2a2d91ce3b9a
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 10:45:39 2021 -0400

    Remove back ticks from for_each page

commit 01f993b6f71dfda381602964c58d2d20e3d67585
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 10:45:13 2021 -0400

    Remove back ticks from depends_on page

commit a448eaa41f6249b93d8e2856ac712991707f2d5c
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 10:44:44 2021 -0400

    Remove back ticks from count page

commit 20bdc25ffd8e84fa43917ab303770349cd3a799a
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 10:43:30 2021 -0400

    Remove back ticks from for expressions page

commit ad9fb34c0b1a3640a17b6e8d50b05ece498c88f4
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 10:42:57 2021 -0400

    Remove backticks from dynamic blocks page

commit f75acc7129232bb57ca1274320bde1af567b603a
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 30 10:42:15 2021 -0400

    Remove backticks from Dependency lock page

commit 2e82e55268d5c44fd16899d06dcfe9eddecf60a1
Merge: f1f2cc6fb a14272d02
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Jul 26 15:07:58 2021 -0400

    Merge pull request #29244 from hashicorp/laura-fix-providers-page
    
    Update extending link to "plugin development"

commit a14272d02279406b28c1b671810cf30ae06b648e
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Jul 26 14:52:44 2021 -0400

    Update extending link to "plugin development"

commit f1f2cc6fb1ca0706e3e9394878c4d022eb07018f
Merge: 7d52e3c47 6993bad75
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Jul 26 11:45:45 2021 -0400

    Merge pull request #29003 from tjabbour/patch-1
    
    fix: Fix typo in provider documentation

commit 7d52e3c4732f748914d47592bd644f86318b582c
Merge: 282a02de4 59dd7f8f5
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Jul 26 11:34:51 2021 -0400

    Merge pull request #29241 from hashicorp/DanielMSchmidt-patch-1
    
    terraform-workspace should be terraform.workspace

commit 282a02de42a110592ce6b3293de5c863a300e564
Merge: e09b831f6 6b0be752b
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Jul 26 11:14:59 2021 -0400

    Merge pull request #29234 from susenj/patch-2
    
    Conciseness and fixed some typos in apt.html.md

commit e09b831f6ee35d37b11b8dcccd3a6d6f6db5e5ff
Merge: 34c992369 e119b4b4c
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 23 16:51:36 2021 -0400

    Merge pull request #28782 from TAYTS/patch-1
    
    Update one.html.md

commit 34c99236928cd008ddaadb891a1112ae0bb951e1
Merge: d572ebf38 a9cc4360f
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 23 16:48:46 2021 -0400

    Merge pull request #28989 from madjava/patch-1
    
    Update configuration.html.md

commit d572ebf3874e4ef765c67e80046be9d1e131231a
Merge: 08df639a4 7fd6019b6
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 23 16:47:34 2021 -0400

    Merge pull request #28910 from brenwhyte/patch-1
    
    Update configuration.html.md (typo)

commit 08df639a425312720ee654757980d8103a9fc533
Merge: 0729e9fdd 2b3d6f992
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 23 16:45:42 2021 -0400

    Merge pull request #29228 from susenj/patch-1
    
    Minor typo in apt.html.md

commit f590c0f5bca7e05730b6b3a0fefc42fc6525f7ca
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 23 16:35:07 2021 -0400

    Update metadata for fmt command

commit 5046e38228c63d8854a4bab8e02686c18abb7322
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 23 16:33:37 2021 -0400

    Update metadata for env command

commit 027dbe40cd73aac7e15fcb1da0eda657e2a5b737
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 23 16:31:43 2021 -0400

    Update metadata for console command

commit ae2ff87598c3a370926f9aa211a8ec7fc48de6c6
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 23 16:30:11 2021 -0400

    Updates to page metadata for plan, apply, import, and destroy

commit dc0dd75b602fef76d55a67f0aab0eb7016b995ce
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 23 16:28:11 2021 -0400

    Update description metadata for import command

commit 2233ef1782b61877a7c4bf280140c6aa976bd3b6
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 23 16:26:29 2021 -0400

    Update description metadata for apply command

commit f0796733c7a42ac44142ac38a36e82921f761856
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 23 16:23:52 2021 -0400

    Update page metadata for plan command

commit 4a7221d57406731fb96a09c30c66f1f04ebe3f50
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 23 16:21:41 2021 -0400

    Update metadata description on internals overview page

commit 8141af763227222180c44bbd3c3c17b4ad2c4cf7
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 23 16:17:47 2021 -0400

    Update description medata on plugin signing page

commit 18b7b4012c5de682570e9373b496d215ee57c017
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 23 16:15:14 2021 -0400

    Add metadata description to cli configuration file page

commit 03e1818c74b97197b532f05ddb0b04afe426dc1f
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 23 16:10:12 2021 -0400

    Add description to environment variables page

commit 5399376263c1328f1032ea58ba65ecf90bd7f7c3
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 23 16:06:43 2021 -0400

    Add description to cli configuration overview page

commit 749d5ce98fe2f3855e3336e42164bf3ee8158d7c
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 23 16:04:12 2021 -0400

    Add metadata to managing plugins overview page

commit 2ef32997ab967bc95ceb0cf8f056c4c62053b68c
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 23 15:57:48 2021 -0400

    Add metadata to workspace subcommand overview page

commit e432d85c5c9810ffb66abc86828c07501b42aece
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 23 15:55:23 2021 -0400

    Add description metadata to managing workspaces overview page

commit 585b609fff331976c65d8e9b6fbd2f6c891903c8
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 23 15:47:49 2021 -0400

    Add page metadata to state recovery page

commit a8ffd119aa9dd6c4288cfae595969255cc4122cf
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 23 14:53:20 2021 -0400

    Add page metadata to moving resources overview

commit 46b56f4540d6162e618e33d01567214c0cf4f99e
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 23 14:44:21 2021 -0400

    Add page metadata to taint overview page

commit d41ee62785ff00f08d43e7e966a2c928895f2195
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 23 14:43:55 2021 -0400

    update state overview page metadata

commit 72181dfc1c25d0b870491425e961a882fc59b725
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 23 14:38:23 2021 -0400

    Add description metadata to inspecting state overview page

commit 733655ef039e12c7ce9c970fe9bad11ebcc9227c
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 23 14:30:01 2021 -0400

    Add description metadata to manipulating state overview page

commit a8b8f4c103316f249513ad46ccd3c9f6ba3411fc
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 23 14:25:58 2021 -0400

    Update metadata on import overview page

commit b37eab61513389188506fac901befea6a953709c
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 23 14:21:14 2021 -0400

    Update metadata on inspecting infrastructure home page

commit f465294ddd5a4f72a22a0caa10ed235b69215cfb
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 21 17:42:57 2021 -0400

    Add metadata to Inspecting Infrastructure overview page

commit 6f7056ea839d061df7b0818d0fd4f88bdf90ccd2
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 21 17:37:54 2021 -0400

    Add metadata to Writing and Modifying Code overview page

commit 5f0a4a080d3ad3301af4c3d8305641da47ebe2b4
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 21 17:35:13 2021 -0400

    Add metadata to provisioning infrastructure overview page

commit 1243ae832e85f76cb849d2ef6a50c2239585f17b
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 21 17:29:25 2021 -0400

    Add metadata to authentication overview page

commit 1c2559f7f1b2c2bf6bd81854d9109ce2b665af38
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 21 17:25:15 2021 -0400

    Add metadata to initializing working directories overview page

commit b18298cdc4acde2f12b9dc72b1f54de2cc0f7dc6
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 21 17:21:25 2021 -0400

    Add metadata to basic cli features page

commit 591bc1e1d9c2ac48645830e58309b3a64153cd8e
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 21 17:15:02 2021 -0400

    Add metadata to CLI overview page

commit b9c0cbb1fd07b82961737b47624aae2db9b21e11
Merge: b12502679 06a2fdcf9
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 21 16:30:05 2021 -0400

    Merge pull request #29117 from hashicorp/description-metadata-language-docs
    
    Description metadata -  language docs

commit 06a2fdcf9d9d59e188a4004a0d0aa3eeacacf28c
Merge: a780f625e 6d65c1913
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 21 16:24:59 2021 -0400

    Merge branch 'main' into description-metadata-language-docs

commit a780f625e901430897132438aedeae98dafe09cc
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Jul 19 12:11:10 2021 -0400

    Fix metadata description format on all pages

commit fd3b5a48c7a03807e6c170fe93ecf9fe85956809
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 16 17:35:08 2021 -0400

    Update provider documentation page metadata

commit 603e156bb9a4725579c4c888b188c3d58ba691d3
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 16 17:32:24 2021 -0400

    Update input variables page metadata

commit 1f1563b8890b9405818c13161c6fb8f3b3fba7d2
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 16 17:28:40 2021 -0400

    Fix formatting error on language home page

commit 725c1c2a86271bab92d6913bf587219e99faf70d
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 16 17:28:13 2021 -0400

    Update style conventions page metadata

commit f67e7f6a9fa4a56d413f6e23f273c48cde8cffb4
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 16 17:21:16 2021 -0400

    Update json configuration syntax page metadata

commit df6135e4c79cbd0d69d0777a2a62cdb00eebe3ad
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 16 17:17:39 2021 -0400

    Update languge syntax overview page metadata

commit b6b434021462a5a6cc2e499683f39f620f0fd0b2
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 16 17:08:24 2021 -0400

    Add detail to backend overview page metadata

commit f46974dbb275605ea8c79b04605b0e702eb5b9e4
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 16 17:01:36 2021 -0400

    Add detail to settings intro page metadata

commit 80fee567a291322c185ddf115fab3e29a20fc88b
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 16 16:55:13 2021 -0400

    Add detail to resource block page metadata

commit 77c208d02f0994dc70a6c914b403f6d303788b40
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 16 16:50:55 2021 -0400

    Add detail to declare provisioners page metadata

commit 6f056af08e5395d89965ac036bc93a51c60df8dd
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 16 16:46:16 2021 -0400

    Update null resource page metadata

commit 55ebc7eef41dd7700980eb99d831d6a4e51519cf
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 16 16:43:12 2021 -0400

    Add detail to provisioners overview page metadata

commit bc9065334e4de62e73d2b943bfbe2e808a079bd5
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 14 16:54:26 2021 -0400

    Update description metadata per PR feedback

commit 7cd333dea17e1ecac81d0bdbf865d39c1383c0a6
Merge: b6614cf2b 3174dfd63
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 14 14:45:35 2021 -0400

    Merge pull request #29163 from hashicorp/rar-docs-update-add-anchor
    
    website: Adds anchor for TF_CLI_ARGS.

commit eebbdd6778d4a6db5cfead0198163c38f64ea0f7
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Jul 13 17:48:28 2021 -0400

    Update dynamic blocks description with more detail and to remove 'ing'

commit 8abbbc7c7fefd3920cdaca19c73b991496a58ef6
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Jul 13 17:40:16 2021 -0400

    Update conditionals metadata to include more detail and remove 'ing'

commit a740d758825f99cc22b4542cc77d16cc96b8c372
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Jul 13 17:34:34 2021 -0400

    Update dependency lock file description with more detail and remove 'ing'

commit 12d1706562054479358282da28f6bef55f405faf
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Jul 13 17:23:07 2021 -0400

    Update data sources metadata to remove ing and include more detailXy

commit 36f51e2790a95876e60f5a719e2cf4424bbb9eb8
Merge: 72a7c9535 557b8df31
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Jul 13 11:23:13 2021 -0400

    Merge pull request #29133 from hashicorp/add-deploy-to-readme
    
    Add deploy information to website folder readme

commit 557b8df31b1058d6b78fcd7b6898789544c66f6b
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Jul 12 09:22:16 2021 -0400

    Active voice and link fix
    
    Co-authored-by: Tu Nguyen <im2nguyen@users.noreply.github.com>

commit 6cf2ad27a7af25eecb7ef862b57169f66ff678f6
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 9 17:26:30 2021 -0400

    Fix typo in description on expressions overview page

commit 5b187a16666812207bf766d99e86dd8424dbe819
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 9 17:24:21 2021 -0400

    Update language on provider docs page

commit eadbb7cd1377bc64b1e7c6b49a34426bdee30219
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 9 17:16:41 2021 -0400

    Remove temporary providers doc reference

commit 69ebfd6f037f8d51709770cc36d266bb86cf950d
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 9 15:56:12 2021 -0400

    Add/update description metadata on backend and state overview pages

commit a37fd2f5f794057a01a80d7e02af34fc064da23e
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 9 15:46:07 2021 -0400

    Upate description metadata on terraform settings overview

commit 952cb331037067965e4f18932b2355988fc0ed06
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 9 15:42:58 2021 -0400

    Add description metadata to functions overview page

commit 7dba0e511f92e16bac204894d26ea688dac933cc
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 9 15:40:05 2021 -0400

    Add description metadata to remaining expressions pages

commit 2718d2addcdfc634001dcabc5501b20cccd2cf01
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 9 15:32:25 2021 -0400

    Add description metadata to module block page

commit df160961416456e76ba196b864b651244e922897
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 9 15:28:28 2021 -0400

    Add description metadata to dynamic blocks, types, and module providers

commit d9f7ce19fe74f01f28621ee25143d497a7f0f64a
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 9 15:17:18 2021 -0400

    Add description metadata to conditionals page

commit aeee849e6c11eafe1cb36e703ede7b2d54089424
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 9 15:02:15 2021 -0400

    Add deploy information to website folder readme

commit 3baddbef0e0286d73a2606a887a55aca1c8719d0
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 9 12:14:58 2021 -0400

    Add description metadata to creating modules pagey

commit e348477c793f6a050a69534e511e67d68d38b023
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 9 12:08:48 2021 -0400

    Add description metadata to module sources

commit 4044fe30d38f538310e1d0e521db9376dd3f33e9
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 9 11:59:38 2021 -0400

    Add description metadata to modules overview page

commit f4f8d7a6c59c8ccfde64657ab4ae3b0c7eb2edb9
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 9 11:50:19 2021 -0400

    Change use to using for consistency with other docs

commit adf4dbdf84df2da976c0f2166e1897faec2fa948
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 9 11:45:42 2021 -0400

    Update description metadata

commit 14d6e0dea9b99caab22153c741bb9278e6f4056a
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 9 11:37:01 2021 -0400

    Add Terraform key work to description metadata

commit 07accd7a386bc84fb213e8b019b9a92030e71c8e
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 9 11:34:02 2021 -0400

    Add page metadata to variables and outputs overview

commit fabd5abf2cfe15a266bfa4826deb92b07607a37a
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 9 11:30:13 2021 -0400

    Make description metadata shorter

commit 9dc008fa1062f09436d790e0fd241feeb99aaf1c
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 9 11:25:55 2021 -0400

    Add metadata description to dependency lock file page

commit 62b11f02e2108e90c440e5661daf9357ac5a5dd9
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 9 11:15:10 2021 -0400

    Make metadata description more concise

commit 62b444504d5edf8a945d9a510e2334119691912e
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 9 11:07:37 2021 -0400

    Add description metadata to provider requirements

commit d107b46270ab493c42fd7bcc54ee9dd70fdc8533
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 9 11:01:32 2021 -0400

    Make description metadata more concise

commit bca3957e1730bdcf82735a5f9833e652e0931846
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 9 10:53:37 2021 -0400

    Update description metadata for input variables

commit 134170c1216341ebc110e6cb67d79ab2877f1c7a
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 9 10:32:17 2021 -0400

    Fixing broken link on syntax page

commit f5c463c27e6467d91e6cf1aaef7f77302f56bd69
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 9 10:30:35 2021 -0400

    Update broken link oon provisioners connection page

commit 493d4b8dc80e13f13f5fdfbdd3c01218155145cc
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 7 17:37:19 2021 -0400

    Update description metadata

commit f25d993b47f5c7c222dfaff55bddf5760b4807c9
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 7 17:34:03 2021 -0400

    Update description metadata to include key words

commit 6f8774a8ed7f39275d6754400116b22609969629
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 7 17:24:58 2021 -0400

    Add Terraform to description metadata for SEO

commit 2e25fd04c037951d487c3753c028524b2a0c61ec
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 7 15:10:14 2021 -0400

    Add description metadata to provisioners index page

commit 6d0569ac4515d4429029edc8c785831d22584c98
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 7 15:07:00 2021 -0400

    Add description metadata to lifecycle page

commit 66103f273efd8fe7d23c5eef406d6abd181debc8
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 7 15:05:02 2021 -0400

    Add description metadata to resource provider page

commit 96994d0b01865d463773f3d962f93607ec1dc856
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 7 15:02:01 2021 -0400

    Add description metadata to for_each page

commit 4a2a6e8b526c21b728a2f0391194167f6f1c4ea7
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 7 14:59:20 2021 -0400

    Add description metadata to count and update depends_on

commit ddabca8c72366e329c26ac69646c9461d9b86b9e
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 7 14:54:51 2021 -0400

    Add description metadata to depends_on page

commit e60e77c68fb9418d7bd15164da45216e256e4705
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 7 14:29:03 2021 -0400

    Add description metadata to behavior page

commit 66dfb56d4f21af9465792f3f4fb5b8c38a6d13d0
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 7 14:20:57 2021 -0400

    Update description metadata to include key words

commit 810543b997306ed930ab3e75c8e30f3881cd3a3e
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 7 14:09:20 2021 -0400

    Add description metadata to resources overview page

commit 08f1d6c9e0952631a8a24eb5db16e2b188659f0f
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 7 14:05:27 2021 -0400

    Update description metadata for style page

commit c33970bfa449df54c199d32808183975e6db6e7b
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 7 14:02:23 2021 -0400

    Add description metadata to JSON syntax page

commit 5384aacb5ebf67a54bfa06906993d5475cab7152
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 7 13:39:14 2021 -0400

    Update description metadata for key words

commit 887b019761cdc6bdfe0111c41be5ac5819f3dd5a
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 7 13:33:51 2021 -0400

    Fix capitalization on Terraform language

commit a62e2825c7bec17551a72c2b087db47dda19997a
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 7 13:23:48 2021 -0400

    Add description metadata to syntax overview

commit f6b500379d1b8d90a22ec498ae47f388c88df6c3
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 7 13:17:42 2021 -0400

    Update description metadata to include Terraform key word

commit ab06843f1da867f92dab972852e64f95d55fcaca
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 7 13:11:17 2021 -0400

    Add description metadata to files and directories

commit 8525befc22363b22d345d86660d71070d5f1e90a
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jul 7 12:58:28 2021 -0400

    Add description metadata to index page

commit 19eaba888eba8d2f2304fb219faee1848bebe351
Merge: 341b1d762 a8d949a59
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Jul 6 14:08:05 2021 -0400

    Merge pull request #29066 from hashicorp/add-compatibility-promises-toc
    
    Add compatibility promises to sidebar toc

commit 341b1d7628b7c04e5bec4e17ab9ea3987f661816
Merge: dfc12a6a9 a8600ca2e
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 2 14:06:33 2021 -0400

    Merge pull request #29085 from hashicorp/add-local-preview-instr-readme
    
    Add instructions to preview docs site locally to /website readme

commit a8600ca2e4e8f925577a993b61bdcb9bae94da1d
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 2 14:02:03 2021 -0400

    Fix numbering for second step

commit 13d690081c47e057f04e5fab70df111dfb1e5839
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 2 13:52:15 2021 -0400

    Fix numbering in first section

commit d3b9d5cddaf7c3216e7eb9c2163f6a3d397122c1
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 2 13:51:00 2021 -0400

    Update website/README.md
    
    Co-authored-by: Tu Nguyen <im2nguyen@users.noreply.github.com>

commit b3736334f7828df3a306c05a39a30162341ae00e
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 2 13:50:09 2021 -0400

    Update website/README.md
    
    Co-authored-by: Tu Nguyen <im2nguyen@users.noreply.github.com>

commit 52e209472638e9fc4f80b8161e3afb82f1abcae4
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 2 13:49:59 2021 -0400

    Update website/README.md
    
    Co-authored-by: Tu Nguyen <im2nguyen@users.noreply.github.com>

commit f2d89464ef5224a7cd56fcafc16840619b76dcf7
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 2 12:29:35 2021 -0400

    Revise grouping in steps

commit 10ccf2bd7f5107148ec5b2ea430fea17ce00d681
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 2 12:26:33 2021 -0400

    Add more context to run instructions

commit 0fc32e5858278cda49f3b65cb72c477f9ab3b7f9
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 2 12:19:28 2021 -0400

    Fix indentation

commit 03e6f0d3851595fc1056c2f5fde415c665d0086f
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 2 12:16:45 2021 -0400

    Update formatting for terminal commands

commit c2b492a8144ae35e7c55d51b9b7bab462e7608e5
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Jul 2 12:08:00 2021 -0400

    Add initial run local instructions to readme

commit dfc12a6a9e1cff323829026d51873c1b80200757
Merge: 6b8e103d6 e6f125586
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Jul 1 14:44:15 2021 -0400

    Merge pull request #29051 from hashicorp/add-page-metadata
    
    Add page metadata

commit e6f1255869fa1c2d1afa93f946536c42878a5735
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Jul 1 11:07:23 2021 -0400

    Update vs Cloudformation description

commit ab9b9a445f2bf6eac78e67e8e433b329ac3ac951
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Jul 1 11:01:21 2021 -0400

    Update vs pages to address PR comments

commit 09c79994f5518855d6a81fc4eb47e8fe356431bc
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Jul 1 10:43:24 2021 -0400

    Update use cases page for PR comments

commit 04385bb9fc5c2713dd5edb053276948528a4a603
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Jul 1 10:39:15 2021 -0400

    Update website/intro/use-cases.html.markdown
    
    Co-authored-by: Judith Malnick <judith.patudith@gmail.com>

commit a9e09a3ed9dc87fc065a9d29dbb8cc4408dfc250
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Jul 1 10:34:41 2021 -0400

    Edit copy to address PR comments

commit a8d949a590e3b962c25bcfb51aeb219b5370c364
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jun 30 10:10:25 2021 -0400

    Add compatibility promises to sidebar toc

commit 577c3653f2667fa567279e04160ed903fb553845
Merge: a7e24c384 165b2a250
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jun 30 08:54:04 2021 -0400

    Merge pull request #28983 from KurtLehnardt/patch-1
    
    fixed typo

commit a7e24c384baf3408231487738c9bb552d705a205
Merge: f9ec36383 176cfad1d
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jun 30 08:52:51 2021 -0400

    Merge pull request #28842 from iaoiui/patch-1
    
    remove extra "be"

commit f9ec36383d501a610409667b9efb3fe26eaff34a
Merge: 4f12b8d91 d4d56a96b
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jun 30 08:51:47 2021 -0400

    Merge pull request #29011 from vlad-ro/patch-1
    
    Add back missing closing quote character

commit 4f12b8d917997b34ad8032dfbe55614276f99186
Merge: f200c5d0e b487b9f8f
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jun 30 08:50:24 2021 -0400

    Merge pull request #28863 from stensonb/patch-1
    
    typo

commit f200c5d0ef69563be6123cb9fee0849ea204d143
Merge: de97a0352 231175204
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jun 30 08:44:11 2021 -0400

    Merge pull request #29032 from hashicorp/izaaklauer/typo
    
    Small comment typo

commit de97a035283f134b228d7c0b717163482837a814
Merge: 35c19d7c9 58a5207dc
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Jun 30 08:43:26 2021 -0400

    Merge pull request #28908 from kondr57/patch-1
    
    fix typo

commit a2cab95dac97f3b180cc2658382d97efb28be352
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Jun 29 09:15:01 2021 -0400

    Update copy for active voice and concision

commit 740343cfd23734b69b1aa8b5d5a42db8398dfd85
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Jun 29 09:02:02 2021 -0400

    Update website/intro/use-cases.html.markdown
    
    Co-authored-by: Tu Nguyen <im2nguyen@users.noreply.github.com>

commit 2cb8bbaacd4578550a94b5fc49f91de661bc33e0
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Jun 29 09:01:25 2021 -0400

    Update website/intro/use-cases.html.markdown
    
    Co-authored-by: Tu Nguyen <im2nguyen@users.noreply.github.com>

commit 16bea6a949734091b2b5d566c523d0dc5d9534a5
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Jun 29 09:01:13 2021 -0400

    Update website/intro/use-cases.html.markdown
    
    Co-authored-by: Tu Nguyen <im2nguyen@users.noreply.github.com>

commit 7cb7d641b7fd26a5ed29bf0a1694eff953e716f3
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Jun 29 08:56:04 2021 -0400

    Remove top header and add provider language

commit 46708ea4bcc23646191913369d15ed385d851bda
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Tue Jun 29 08:44:53 2021 -0400

    Update website/intro/vs/chef-puppet.html.markdown
    
    Co-authored-by: Tu Nguyen <im2nguyen@users.noreply.github.com>

commit f526e6eadcdacafc30609dd325f27b7244878948
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Jun 28 17:14:34 2021 -0400

    Update page description metadata

commit 5e89ac590e04e10a2c7178ef6e11df939166bb59
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Jun 28 17:10:11 2021 -0400

    Update page description metadata

commit 908ceec8c15c5c6f3a765d9d9d98f5fef7e29426
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Jun 28 17:06:50 2021 -0400

    Update page description metadata

commit fc772aec86360e6ee17e49918fdf4ea8abf88941
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Jun 28 17:03:30 2021 -0400

    Update page content for clarity, concision, and flow

commit 2f67c788216c4feff0629df0f1eee9c8b2acbe28
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Jun 28 16:50:37 2021 -0400

    Update page description metadata

commit 4111b1298dd81c63711ff1fed03068ccaf66822e
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Jun 28 16:47:37 2021 -0400

    Update page description metadata

commit 5344ba0fa5cfe39e589c18286b3590f121ae812b
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Jun 28 16:00:16 2021 -0400

    Update page description metadata

commit 0ab2012d77cd8353e791cfff7760a7d2233a2bbd
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Jun 28 15:59:36 2021 -0400

    Update page description metadata

commit e92f030662ca2539429188114a706662f16adb85
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Jun 28 11:38:21 2021 -0400

    Make get started bullet more concise

commit 60f240f8cf49c0c409a705cfed53c3736e5145be
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Jun 28 11:33:06 2021 -0400

18.
Mon Sep 20 17:24:31 2021 -0400 - Laura Pacilio: Merge pull request #29567 from drasko95/patch-1
Thu Sep 16 17:30:37 2021 -0400 - Laura Pacilio: Merge pull request #29598 from hashicorp/laura-add-mrui-to-sidebar
Thu Sep 16 17:11:31 2021 -0400 - Laura Pacilio: Fix alphabetical order of sidebar
Thu Sep 16 17:06:52 2021 -0400 - Laura Pacilio: Add Machine-Readable UI to sidebar and add hyphen :-)
Mon Sep 13 10:39:02 2021 -0400 - Laura Pacilio: Merge pull request #29494 from magnetikonline/docs-s3-backend-dynamodb-partition-key
Thu Sep 9 15:09:31 2021 -0400 - Laura Pacilio: Merge pull request #28579 from ChadBailey/patch-2
Thu Sep 9 14:54:17 2021 -0400 - Laura Pacilio: Merge pull request #29451 from kmadof/patch-1
Thu Sep 9 11:06:58 2021 -0400 - Laura Pacilio: Merge pull request #29502 from hashicorp/alisdair/json-format-version
Fri Sep 3 12:11:34 2021 -0400 - Laura Pacilio: Merge pull request #29509 from drewmullen/d-module-source-revision-option
Fri Sep 3 10:19:30 2021 -0400 - Laura Pacilio: Merge pull request #28345 from yvespp/destroy_provisioners_doc
Thu Sep 2 14:47:38 2021 -0400 - Laura Pacilio: Merge pull request #28334 from paultyng/patch-1

19.

    Update description and edit for concision and clarity
18