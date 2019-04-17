# Results

## Tagged root commit

| Expected | Actual |
| -------- | ------ |
| 0.0.0    | 0.0.0  |

### Log

```
commit e8caf032b105c89ce00b0c1ca07c2602e8104daa (tag: v0.0.0)
Author: Wes Toleman <wesley.toleman@bankwest.com.au>
Date:   Wed Apr 17 12:00:33 2019 +0800

    Initial commit
```

### GitVersion output

```json
{
  "Major":0,
  "Minor":0,
  "Patch":0,
  "PreReleaseTag":"",
  "PreReleaseTagWithDash":"",
  "PreReleaseLabel":"",
  "PreReleaseNumber":"",
  "BuildMetaData":"",
  "BuildMetaDataPadded":"",
  "FullBuildMetaData":"Branch.master.Sha.f903e9e76ff87b77536752884ea2243f882eb98c",
  "MajorMinorPatch":"0.0.0",
  "SemVer":"0.0.0",
  "LegacySemVer":"0.0.0",
  "LegacySemVerPadded":"0.0.0",
  "AssemblySemVer":"0.0.0.0",
  "AssemblySemFileVer":"0.0.0.0",
  "FullSemVer":"0.0.0",
  "InformationalVersion":"0.0.0+Branch.master.Sha.f903e9e76ff87b77536752884ea2243f882eb98c",
  "BranchName":"master",
  "Sha":"f903e9e76ff87b77536752884ea2243f882eb98c",
  "ShortSha":"a9f24c8",
  "NuGetVersionV2":"0.0.0",
  "NuGetVersion":"0.0.0",
  "NuGetPreReleaseTagV2":"",
  "NuGetPreReleaseTag":"",
  "CommitsSinceVersionSource":0,
  "CommitsSinceVersionSourcePadded":"0000",
  "CommitDate":"2019-04-17"
}
```

## Minor version bump

| Expected | Actual |
| -------- | ------ |
| 0.1.0    | 0.2.0  |

### Log

```
commit f97f396167e2ea9784a15f682fdef23f04eaef11
Merge: e8caf03 c401d69
Author: Wes Toleman <wesley.toleman@hotmail.com>
Date:   Wed Apr 17 12:03:22 2019 +0800

    Merge branch 'feature/minor-bump'
```

### GitVersion output

```json
{
  "Major":0,
  "Minor":2,
  "Patch":0,
  "PreReleaseTag":".2",
  "PreReleaseTagWithDash":"",
  "PreReleaseLabel":"",
  "PreReleaseNumber":"",
  "BuildMetaData":"",
  "BuildMetaDataPadded":"",
  "FullBuildMetaData":"Branch.master.Sha.a2434c26090e97514b17fedd2a6acfe259b27b07",
  "MajorMinorPatch":"0.2.0",
  "SemVer":"0.2.0",
  "LegacySemVer":"0.2.0",
  "LegacySemVerPadded":"0.2.0",
  "AssemblySemVer":"0.2.0.0",
  "AssemblySemFileVer":"0.2.0.0",
  "FullSemVer":"0.2.0",
  "InformationalVersion":"0.2.0+Branch.master.Sha.a2434c26090e97514b17fedd2a6acfe259b27b07",
  "BranchName":"master",
  "Sha":"a2434c26090e97514b17fedd2a6acfe259b27b07",
  "ShortSha":"a2434c2",
  "NuGetVersionV2":"0.2.0",
  "NuGetVersion":"0.2.0",
  "NuGetPreReleaseTagV2":"",
  "NuGetPreReleaseTag":"",
  "CommitsSinceVersionSource":2,
  "CommitsSinceVersionSourcePadded":"0002",
  "CommitDate":"2019-04-17"
}
```

## Patch version bump

| Expected | Actual |
| -------- | ------ |
| 0.1.1    | 0.2.1  |

### Log

```
commit 2426637c9fba62203751b2fb18df960075c544bf
Merge: f97f396 33c143a
Author: Wes Toleman <wesley.toleman@hotmail.com>
Date:   Wed Apr 17 12:05:15 2019 +0800

    Merge branch 'bugfix/patch-bump'
```

### GitVersion output

```json
{
  "Major":0,
  "Minor":2,
  "Patch":1,
  "PreReleaseTag":".4",
  "PreReleaseTagWithDash":"",
  "PreReleaseLabel":"",
  "PreReleaseNumber":"",
  "BuildMetaData":"",
  "BuildMetaDataPadded":"",
  "FullBuildMetaData":"Branch.master.Sha.d28d0c381224253df9e8dce5d635077db83c5c32",
  "MajorMinorPatch":"0.2.1",
  "SemVer":"0.2.1",
  "LegacySemVer":"0.2.1",
  "LegacySemVerPadded":"0.2.1",
  "AssemblySemVer":"0.2.1.0",
  "AssemblySemFileVer":"0.2.1.0",
  "FullSemVer":"0.2.1",
  "InformationalVersion":"0.2.1+Branch.master.Sha.d28d0c381224253df9e8dce5d635077db83c5c32",
  "BranchName":"master",
  "Sha":"d28d0c381224253df9e8dce5d635077db83c5c32",
  "ShortSha":"d28d0c3",
  "NuGetVersionV2":"0.2.1",
  "NuGetVersion":"0.2.1",
  "NuGetPreReleaseTagV2":"",
  "NuGetPreReleaseTag":"",
  "CommitsSinceVersionSource":4,
  "CommitsSinceVersionSourcePadded":"0004",
  "CommitDate":"2019-04-17"
}
```

## Major version bump

| Expected | Actual |
| -------- | ------ |
| 1.0.0    | 1.0.0  |

### Log

```
commit 03a4836e8d10d71c9db4e09d279f56ac6cf990e4
Merge: 2426637 e4f952c
Author: Wes Toleman <wesley.toleman@hotmail.com>
Date:   Wed Apr 17 12:07:15 2019 +0800

    Merge branch 'breaking/major-bump'
```

### GitVersion output

```json
{
  "Major":1,
  "Minor":0,
  "Patch":0,
  "PreReleaseTag":".6",
  "PreReleaseTagWithDash":"",
  "PreReleaseLabel":"",
  "PreReleaseNumber":"",
  "BuildMetaData":"",
  "BuildMetaDataPadded":"",
  "FullBuildMetaData":"Branch.master.Sha.4f0c3e4029f2a44f2668017502934c39a1f9983d",
  "MajorMinorPatch":"1.0.0",
  "SemVer":"1.0.0",
  "LegacySemVer":"1.0.0",
  "LegacySemVerPadded":"1.0.0",
  "AssemblySemVer":"1.0.0.0",
  "AssemblySemFileVer":"1.0.0.0",
  "FullSemVer":"1.0.0",
  "InformationalVersion":"1.0.0+Branch.master.Sha.4f0c3e4029f2a44f2668017502934c39a1f9983d",
  "BranchName":"master",
  "Sha":"4f0c3e4029f2a44f2668017502934c39a1f9983d",
  "ShortSha":"4f0c3e4",
  "NuGetVersionV2":"1.0.0",
  "NuGetVersion":"1.0.0",
  "NuGetPreReleaseTagV2":"",
  "NuGetPreReleaseTag":"",
  "CommitsSinceVersionSource":6,
  "CommitsSinceVersionSourcePadded":"0006",
  "CommitDate":"2019-04-17"
}
```
