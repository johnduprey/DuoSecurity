---
external help file: DuoSecurity-help.xml
Module Name: DuoSecurity
online version: https://duo.com/docs/adminapi#delete-group
schema: 2.0.0
---

# Remove-DuoGroup

## SYNOPSIS
Delete Group

## SYNTAX

```
Remove-DuoGroup [-GroupId] <String> [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Delete a group.
Requires "Grant write resource" API permission.

## EXAMPLES

### EXAMPLE 1
```
Remove-DuoGroup -GroupId SOMEDUOID
```

## PARAMETERS

### -GroupId
Group Id to remove

```yaml
Type: String
Parameter Sets: (All)
Aliases: group_id

Required: True
Position: 1
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
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[https://duo.com/docs/adminapi#delete-group](https://duo.com/docs/adminapi#delete-group)

