# PlatformAbstractions sample console

The `run` scripts expect the artifacts to be already built!
You can build the sample with Visual Studio or from the command line at the root of the repository with `build.ps1` or `build.sh`

Running it will output to console some of the APIs defined in the library.


```shell
λ run.cmd
Running any already built Console sample:

Running: C:\Users\bruno\git\dotnet-sentry-platform-abstractions\samples\Sentry.PlatformAbstractions.Console\bin\Release\net35\Sentry.PlatformAbstractions.Console.exe
Runtime.Current:

    ToString():               .NET Framework 3.5 SP 1

    Name:                     .NET Framework
    Version:                  3.5 SP 1
    Raw:                      Environment.Version=2.0.50727.8922

Runtime.Current.FrameworkInstallation:
    ShortName:                v3.5
    Profile:
    Version:                  3.5.30729.4926
    ServicePack:              1
    Release:
    ToString():               3.5.30729

Extension methods on Runtime:
    IsMono():                 False
    IsNetCore()               False
    IsNetFx():                True


Running: C:\Users\bruno\git\dotnet-sentry-platform-abstractions\samples\Sentry.PlatformAbstractions.Console\bin\Release\net471\Sentry.PlatformAbstractions.Console.exe
Runtime.Current:

    ToString():               .NET Framework 4.7.2

    Name:                     .NET Framework
    Version:                  4.7.2
    Raw:                      .NET Framework 4.7.3101.0

Runtime.Current.FrameworkInstallation:
    ShortName:
    Profile:
    Version:                  4.7.2
    ServicePack:
    Release:                  461808
    ToString():               4.7.2

Extension methods on Runtime:
    IsMono():                 False
    IsNetCore()               False
    IsNetFx():                True


Running: C:\Users\bruno\git\dotnet-sentry-platform-abstractions\samples\Sentry.PlatformAbstractions.Console\bin\Release\netcoreapp1.1\Sentry.PlatformAbstractions.Console.dll
Runtime.Current:

    ToString():               .NET Core 1.1.7

    Name:                     .NET Core
    Version:                  1.1.7
    Raw:                      .NET Core 4.6.26201.01
Extension methods on Runtime:
    IsMono():                 False
    IsNetCore()               True
    IsNetFx():                False


Running: C:\Users\bruno\git\dotnet-sentry-platform-abstractions\samples\Sentry.PlatformAbstractions.Console\bin\Release\netcoreapp2.0\Sentry.PlatformAbstractions.Console.dll
Runtime.Current:

    ToString():               .NET Core 2.0.7

    Name:                     .NET Core
    Version:                  2.0.7
    Raw:                      .NET Core 4.6.26328.01
Extension methods on Runtime:
    IsMono():                 False
    IsNetCore()               True
    IsNetFx():                False

```
