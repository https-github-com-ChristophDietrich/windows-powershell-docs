---
author: brianlic-msft
description: 
external help file: MultiPoint.dll-Help.xml
keywords: powershell, cmdlet
manager: alanth
ms.date: 2016-12-20
ms.prod: powershell
ms.technology: powershell
ms.topic: reference
online version: 
schema: 2.0.0
title: Clear-WmsStation
ms.assetid: CF10CF86-649C-441A-BFD3-A8C56C690080
---

# Clear-WmsStation

## SYNOPSIS
Clears station mapping information for all stations.

## SYNTAX

```
Clear-WmsStation [-Server <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
The **Clear-WmsStation** cmdlet clears station mapping information for all stations.

## EXAMPLES

### Example 1: Clear station mapping
```
PS C:\>Clear-WmsStation
```

This command puts all MultiPoint Server stations into an unmapped state.
All station mapping information is lost, along with any station friendly names and station autologon information.

If you subsequently run Get-WmsStation it returns no station information.

### 1:
```

```

## PARAMETERS

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -Server
Specifies the fully qualified host name of the MultiPoint Server that is the target of the command.
The default is localhost.

```yaml
Type: String
Parameter Sets: (All)
Aliases: ComputerName

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

###  
None.

## OUTPUTS

###  
None.

## NOTES

## RELATED LINKS

[Get-WmsStation](./Get-WmsStation.md)

[Join-WmsStation](./Join-WmsStation.md)

[Set-WmsStation](./Set-WmsStation.md)

[Split-WmsStation](./Split-WmsStation.md)

[Update-WmsStation](./Update-WmsStation.md)
