---
external help file: DuoSecurity-help.xml
Module Name: DuoSecurity
online version: https://duo.com/docs/adminapi#retrieve-groups
schema: 2.0.0
---

# Get-DuoGroups

## SYNOPSIS
Retrieve Groups

## SYNTAX

```
Get-DuoGroups [[-GroupId] <String>] [<CommonParameters>]
```

## DESCRIPTION
Returns a single group or a paged list of groups.
Requires "Grant read resource" API permission.

## EXAMPLES

### EXAMPLE 1
```
Get-DuoGroups
```

## PARAMETERS

### -GroupId
Group Id to retrieve

```yaml
Type: String
Parameter Sets: (All)
Aliases: group_id

Required: False
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[https://duo.com/docs/adminapi#retrieve-groups](https://duo.com/docs/adminapi#retrieve-groups)

[https://duo.com/docs/adminapi#get-group-info](https://duo.com/docs/adminapi#get-group-info)

