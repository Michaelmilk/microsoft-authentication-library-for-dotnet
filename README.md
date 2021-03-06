# Microsoft Authentication Library (MSAL) Preview for .NET, Windows Store, UWP, NetCore, Xamarin Android and iOS

| [Conceptual documentation](https://github.com/AzureAD/microsoft-authentication-library-for-dotnet/wiki) | [Getting Started](https://docs.microsoft.com/azure/active-directory/develop/guidedsetups/active-directory-mobileanddesktopapp-windowsdesktop-intro) | [Sample Code](https://github.com/Azure-Samples/active-directory-dotnet-desktop-msgraph-v2) | [Library Reference](https://docs.microsoft.com/en-us/azure/active-directory/develop/active-directory-v2-libraries) | [Support](README.md#community-help-and-support) |
| ------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------- |

The MSAL library for .NET gives your app the ability to begin using the [Microsoft Cloud](https://cloud.microsoft.com) by supporting [Microsoft Azure Active Directory](https://azure.microsoft.com/en-us/services/active-directory/) and [Microsoft Accounts](https://account.microsoft.com) in a converged experience using industry standard OAuth2 and OpenID Connect. The library also supports [Azure AD B2C](https://azure.microsoft.com/services/active-directory-b2c/).

## The nuget packages

Released     | Nightly
-----------------------------|-------------------------
 [![NuGet](https://img.shields.io/nuget/v/Microsoft.Identity.Client.svg?style=flat-square&label=nuget&colorB=00b200)](https://www.nuget.org/packages/Microsoft.Identity.Client/) | [![MyGet](https://img.shields.io/myget/aad-clients-nightly/vpre/Microsoft.Identity.Client.svg?style=flat-square&label=myget&colorB=ff0000)](https://www.myget.org/feed/aad-clients-nightly/package/nuget/Microsoft.Identity.Client)

## Where is the source code

The [ADAL GitHub repo](https://github.com/AzureAD/azure-activedirectory-library-for-dotnet) is used for future development of MSAL and ADAL.
We have done this to enable easier code sharing between the two libraries. You can see build status in that repo.

Read more about this change and the announced in the [msal.net 2 preview release](https://github.com/AzureAD/microsoft-authentication-library-for-dotnet/wiki/msal-net-2-released)

## Where do I find docs and file issues

This is the correct repo to file issues and to search for documentation related to MSAL.

## Important Note about the MSAL Preview

This library is suitable for use in a production environment.
We provide the same production level support for this library as we do our current production libraries.
During the preview we may make changes to the API, internal cache format, and other mechanisms of this library,
which you will be required to take along with bug fixes or feature improvements.
This may impact your application. For instance, a change to the cache format may impact your users,
such as requiring them to sign in again. An API change may require you to update your code.
When we provide the General Availability release we will require you to update to the General Availability version within six months,
as applications written using a preview version of library may no longer work.

## Requirements

* Windows 7 or greater
* .NET 4.5 or greater

## Community Help and Support

We use [Stack Overflow](http://stackoverflow.com/questions/tagged/msal) with the community to provide support. We highly recommend you ask your questions on Stack Overflow first and browse existing issues to see if someone has asked your question before.

If you find and bug or have a feature request, please raise the issue on [GitHub Issues](../../issues).

To provide a recommendation, visit our [User Voice page](https://feedback.azure.com/forums/169401-azure-active-directory).

## Contribute

We enthusiastically welcome contributions and feedback. You can clone the repo and start contributing now. Read our [Contribution Guide](Contributing.md) for more information.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Security Library

This library controls how users sign-in and access services. We recommend you always take the latest version of our library in your app when possible. We use [semantic versioning](http://semver.org) so you can control the risk associated with updating your app. As an example, always downloading the latest minor version number (e.g. x.*y*.x) ensures you get the latest security and feature enhancements but our API surface remains the same. You can always see the latest version and release notes under the Releases tab of GitHub.

## Security Reporting

If you find a security issue with our libraries or services please report it to [secure@microsoft.com](mailto:secure@microsoft.com) with as much detail as possible. Your submission may be eligible for a bounty through the [Microsoft Bounty](http://aka.ms/bugbounty) program. Please do not post security issues to GitHub Issues or any other public site. We will contact you shortly upon receiving the information. We encourage you to get notifications of when security incidents occur by visiting [this page](https://technet.microsoft.com/en-us/security/dd252948) and subscribing to Security Advisory Alerts.

Copyright (c) Microsoft Corporation.  All rights reserved. Licensed under the MIT License (the "License");

## Using MSAL

We recommend that you read about using MSAL in our [Wiki pages](http://aka.ms/msalnet).  