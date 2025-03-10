---
Module Name: microsoftteams
applicable: Microsoft Teams
title: Set-CsTeamsMediaConnectivityPolicy
online version: https://learn.microsoft.com/powershell/module/teams/Set-CsTeamsMediaConnectivityPolicy
schema: 2.0.0
author: lirunping_MSFT
ms.author: runli
---

# Set-CsTeamsMediaConnectivityPolicy

## SYNOPSIS

This cmdlet Set Teams media connectivity policy value for current tenant.

## SYNTAX

```
Set-CsTeamsMediaConnectivityPolicy -Identity <string> -DirectConnection <Enabled/Disabled>
```

## DESCRIPTION

This cmdlet Set Teams media connectivity policy DirectConnection value for current tenant. The value can be "Enabled" or "Disabled"

## EXAMPLES

### Example 1
```powershell
PS C:\> Set-CsTeamsMediaConnectivityPolicy -Identity Test -DirectConnection Disabled
Identity DirectConnection
-------- ----------------
Global   Enabled
Tag:Test Disabled
```

Set Teams media connectivity policy "DirectConnection" value to "Disabled" for identity "Test".

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
### -DirectConnection
Policy value of the Teams media connectivity DirectConnection policy.

```yaml
Type: Boolean
Parameter Sets: ("Enabled","Disabled")
Aliases:

Required: True
Position: Named
Default value: Enabled
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](https://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## RELATED LINKS

[New-CsTeamsMediaConnectivityPolicy](New-CsTeamsMediaConnectivityPolicy.md)

[Remove-CsTeamsMediaConnectivityPolicy](Remove-CsTeamsMediaConnectivityPolicy.yml)

[Get-CsTeamsMediaConnectivityPolicy](Get-CsTeamsMediaConnectivityPolicy.yml)
