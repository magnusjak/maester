---
title: AADSC.authenticationMethodsPolicy.displayLocationInformationRequiredStateIncluded
description: displayLocationInformationRequiredStateIncluded - Included users/groups to show geographic location in push and passwordless notifications
---

# Included users/groups to show geographic location in push and passwordless notifications

Object Id or scope of users which will be showing geographic location in the Authenticator App.

| | |
|-|-|
| **Name** | displayLocationInformationRequiredStateIncluded |
| **Control** | Authentication Method - Microsoft Authenticator |
| **Description** | Define configuration settings and users or groups that are enabled to use Authenticator App |
| **Severity** | Medium |

## How to fix
| | |
|-|-|
| **Recommendation** |  |
| **Configuration** | policies/authenticationMethodsPolicy/authenticationMethodConfigurations('MicrosoftAuthenticator') |
| **Setting** | `featureSettings.displayLocationInformationRequiredState.includeTarget.id` |
| **Recommended Value** | 'all_users' |
| **Default Value** | all_users |
| **Graph API Docs** | [microsoftAuthenticatorAuthenticationMethodConfiguration resource type - Microsoft Graph v1.0 - Microsoft Learn](https://learn.microsoft.com/en-us/graph/api/resources/microsoftauthenticatorauthenticationmethodconfiguration) |
| **Graph Explorer** | [View in Graph Explorer](https://developer.microsoft.com/en-us/graph/graph-explorer?request=policies/authenticationMethodsPolicy/authenticationMethodConfigurations('MicrosoftAuthenticator')&method=GET&version=beta&GraphUrl=https://graph.microsoft.com) |


