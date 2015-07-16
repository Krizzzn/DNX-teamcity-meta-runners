# DNX Meta Runners for Teamcity

## installations

Place xml files in %TEAMCITY%\config\projects\%Project%\pluginData\metaRunners (C:\ProgramData\JetBrains\TeamCity\config\projects\BaBuildServer\pluginData\metaRunners)

## prerequesites

If you're using the 'DNX - Install and configure DNX' meta runner, the Build Agent must feature the configuration property %teamcity.tool.nuget% 
pointing to the directory that contains the nuget.exe.

## attribution

This DNX Meta Runners for Teamcity is based on a package of meta runners for K. Unfortunately I can't find the original github repository anymore,
so I can't credit the original creator here. If you have any leads, just contact me or submit a pull request.