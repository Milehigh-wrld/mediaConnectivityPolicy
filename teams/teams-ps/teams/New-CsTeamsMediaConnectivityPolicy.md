---
Module Name: microsoftteams
applicable: Microsoft Teams
title: New-CsTeamsMediaConnectivityPolicy
online version: https://learn.microsoft.com/powershell/module/teams/New-CsTeamsMediaConnectivityPolicy
schema: 2.0.0
author: lirunping_MSFT
ms.author: runli
---


# New-CsTeamsMediaConnectivityPolicy

## SYNOPSIS
This cmdlet creates an Teams media connectivity policy.

## SYNTAX

```powershell
New-CsTeamsMediaConnectivityPolicy -Identity <String>
```

## DESCRIPTION
This cmdlet creates an Teams media connectivity policy. If you get an error that the policy already exists, it means that the policy already exists for your tenant. In this case, run Get-CsTeamsMediaConnectivityPolicy.

## EXAMPLES

### Example 1
```powershell
PS C:\> New-CsTeamsMediaConnectivityPolicy -Identity Test

Identity DirectConnection
-------------------------
Tag:Test Enabled
```

Returns the current value of "DirectConnection" policy with identity of "Test".


## PARAMETERS

### -Identity
Identity of the Teams media connectivity policy.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](https://go.microsoft.com/fwlink/?LinkID=113216).


## RELATED LINKS
[Remove-CsTeamsMediaConnectivityPolicy](Remove-CsTeamsMediaConnectivityPolicy.yml)

[Get-CsTeamsMediaConnectivityPolicy](Get-CsTeamsMediaConnectivityPolicy.yml)

[Set-CsTeamsMediaConnectivityPolicy](Set-CsTeamsMediaConnectivityPolicy.yml)